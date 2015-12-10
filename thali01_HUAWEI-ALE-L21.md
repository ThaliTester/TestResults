#### Test 50650278b86327b_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 7536): CLASSPATH=/system/framework/am.jar
I/appproc ( 7536): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 7536): app_process:number,5,0
I/AndroidRuntime( 7536): readDownloadBoosterConfig: 'false'
I/        ( 7536): power log dlsym ok
E/android_hardware_fm.cpp( 7536): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 7536): ========64bit long size = 8
E/FM_HAL  ( 7536): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 7536): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 7536): 
I/fm_hisi ( 7536): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 7536): 
I/fm_hisi ( 7536): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 7536): 
E/android_hardware_fm.cpp( 7536): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 3039): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3039): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3039): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3039): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3638): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3846): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3846): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3846): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3638): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwSystemManager( 3638): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3846): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3846): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 7556): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 7556): Loading: webviewchromium
I/LibraryLoader( 7556): Time to load native libraries: 52 ms (timestamps 1186-1238)
I/LibraryLoader( 7556): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 7556): Expected native library version number "",actual native library version number ""
I/chromium( 7556): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7556): Initializing chromium process, renderers=0
W/art     ( 7556): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7556): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/PG Utils( 7276): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/chromium( 7556): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 7556): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/PG Utils( 7276): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 7276): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 7276): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/chromium( 7556): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7556): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 7556): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 7556): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7556): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 7556): Can not find class: Landroid/widget/ViewStub;
I/art     ( 7556): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 7556): Can not find class: Landroid/app/ViewStub;
W/art     ( 7556): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7556): Attempt to remove local handle scope entry from IRT, ignoring
I/qtaguid ( 7276): Failed write_ctrl(u 46) res=-1 errno=22
I/qtaguid ( 7276): Untagging socket 46 failed errno=-22
W/NetworkManagementSocketTagger( 7276): untagSocket(46) failed with errno -22
I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 4
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=30 dispatchEvent: HEART-BEAT-ACK: 4
E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
I/PhoneStatusBar( 3401): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3401): shouldTranslucent:true
I/PhoneStatusBar( 3401): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 7556): Initialized EGL, version 1.4
,I/ActivityManager( 3039): Displayed com.test.thalitest/.MainActivity: +1s36ms (total +1s108ms)
,W/IInputConnectionWrapper( 7556): showStatusIcon on inactive InputConnection
,I/chromium( 7556): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7556): 
,W/jxcore-log( 7556): Initializing JXcore engine
W/jxcore-log( 7556): JXcore engine is ready
,W/jxcore-log( 7556): Starting JXcore engine
,W/jxcore-log( 7556): Platform android
W/jxcore-log( 7556): 
W/jxcore-log( 7556): Process ARCH arm
W/jxcore-log( 7556): 
,I/art     ( 3039): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 7556): JXcore Cordova bridge is ready!
I/jxcore-log( 7556): 
W/jxcore-log( 7556): JXcore engine is started
,I/art     ( 5984): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,I/jxcore-log( 7556): Toggling radios to true
I/jxcore-log( 7556): 
,I/HwSystemManager( 3638): HoldService:checkBeforeShowDialog: uid:10295 pid:7556, permissionType:2097152
I/HwSystemManager( 3638): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 3039): allowOpenWifi blocked:false
,E/WifiStateMachine( 3039):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 3039): [105,823,242 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/jxcore-log( 7556): Radios toggled
I/jxcore-log( 7556): 
,I/wpa_supplicant( 3410): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/wpa_supplicant( 3410): check_associate_result func start
,W/System.err( 3039): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3039): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3039): This is not beta user build
,I/jxcore-log( 7556): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 7556): 
,I/jxcore-log( 7556): Perf Test app loaded loaded
I/jxcore-log( 7556): 
,I/Choreographer( 7556): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 7556): check test folder
I/jxcore-log( 7556): 
,I/jxcore-log( 7556): found test : ./testFindPeers.js
I/jxcore-log( 7556): 
,E/WifiMonitor( 3039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,W/wpa_supplicant( 3410): STA MODE: Set shutdown wlan cmd SUCCESS
,W/wpa_supplicant( 3410): check_associate_result func start
,I/wpa_supplicant( 3410): set current WIFI status to BT!
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
E/WifiStateMachine( 3039): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3039): setScanAlarm false period 20000 initial delay 0
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 3039): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3039): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 3039): do suspend true
,I/wpa_supplicant( 3410): set current WIFI status to BT!
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
,I/jxcore-log( 7556): found test : ./testSendData.js
I/jxcore-log( 7556): 
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/ArpVerifier( 3039): current SSID is empty.
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3039):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3039):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 3039):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 3039): [105,933,154 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
W/wpa_supplicant( 3410): check_associate_result func start
,I/wpa_supplicant( 3410): wlan is down..., now start up...
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 3039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105942
,E/WifiStateMachine( 3039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105942
,E/native  ( 3039): do suspend true
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3401): stop
,I/WifiTracker( 3401): STATE =1
W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,W/wpa_supplicant( 3410): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3410): set current WIFI status to BT!
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4936): btcoex_set_a2dp_priority: bdaddr: 000000000000
,I/bluetooth-coex( 4936): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3410): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3039):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
,E/WifiStateMachine( 3039): setScanAlarm true period 0 initial delay 200,
,E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=106757  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,I/art     ( 3039): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=106767  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,I/HwSystemManager( 3638): aor:Network Stats Updated
,I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/chromium( 7556): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,I/HwSystemManager( 3638): aor:Network Stats Updated
I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=106794  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=106802  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/chromium( 7556): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=36 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 3039): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
,E/WifiStateMachine( 3039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:325 bcn=0
,E/WifiStateMachine( 3039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:325 bcn=0
,E/WifiStateMachine( 3039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:325 bcn=0
,E/WifiStateMachine( 3039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:325 bcn=0
E/WifiStateMachine( 3039): [1,449,756,678,478 ms] noteScanEnd no scan source
,I/wpa_supplicant( 3410): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=37 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/wpa_supplicant( 3410): check_associate_result func start
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 3410): set current WIFI status to BT!,
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4936): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4936): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,E/WifiStateMachine( 3039): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@37efcd6c sup_state=SCANNING debouncing=false
,E/WifiAutoJoinController ( 3039): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 3039): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-88 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS] is not scored
E/WifiAutoJoinController ( 3039): Gonzos 38:f8:89:11:e9:11 rssi=-90 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
,E/WifiAutoJoinController ( 3039): ageScanResultsOut delay 40000 size 3 now 1449756678485
E/WifiAutoJoinController ( 3039): newSupplicantResults size=3 known=1 true
,E/WifiAutoJoinController ( 3039): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController ( 3039): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3039): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3039): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
,E/WifiAutoJoinController ( 3039): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiStateMachine( 3039):  DisconnectedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107451
,E/WifiStateMachine( 3039):  ConnectModeState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107451
E/WifiStateMachine( 3039):  DriverStartedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107452
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107452
,E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=107452  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=107459  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3401): stop
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,W/wpa_supplicant( 3410): check_associate_result func start
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,I/wpa_supplicant( 3410): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=107981  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=107982  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 3039): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72 SSID=0x
W/wpa_supplicant( 3410): check_associate_result func start
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 3039):  DisconnectedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107993
E/WifiStateMachine( 3039):  ConnectModeState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107993
,E/WifiStateMachine( 3039):  DriverStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107994
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107994
,E/WifiStateMachine( 3039):  DefaultState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107994
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=107997  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=108004  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/wpa_supplicant( 3410): check_associate_result func start
W/wpa_supplicant( 3410): check_associate_result func start,
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,W/WifiMonitor( 3039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3410): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/wpa_supplicant( 3410): set current WIFI status to BT!
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 3039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3410): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
W/wpa_supplicant( 3410): check_associate_result func start
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=108019  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 3039): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=108021  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 3039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108022
E/WifiStateMachine( 3039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108022
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/System.err( 3039): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
,W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3039): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3039): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 3039): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
,W/System.err( 3039): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 3039): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3039): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3039): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ReportTools( 3039): This is not beta user build
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE,
E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/WifiStateMachine( 3039): setScanAlarm false period 0 initial delay 0
E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3039): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 3039): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3039): obtaining wifi is conencted
,E/WifiStateMachine( 3039): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any,
E/WifiStateMachine( 3039): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3039): obtaining wifi is conencted
,E/WifiStateMachine( 3039): Start Dhcp Watchdog 2
,E/WifiStateMachine( 3039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=108055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 3039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=108055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=108056  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
E/WifiStateMachine( 3039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
I/wpa_supplicant( 3410): set current WIFI status to BT!
I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,E/native  ( 3039): do suspend false
,E/WifiStateMachine( 3039): Unexpected BatchedScanResults :OK,
,E/WifiStateMachine( 3039): noteBatchedScanstop()
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57,
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/DHCPCD  ( 7638): version 5.5.6 starting
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/DHCPCD  ( 7638): hw_parse_xidfile 
I/DHCPCD  ( 7638): wlan0: dhcp start reboot
I/DHCPCD  ( 7638): wlan0: rebinding lease of 192.168.1.120
,I/DHCPCD  ( 7638): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,W/ArpVerifier( 3039): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,I/DHCPCD  ( 7638): wlan0: checking for 192.168.1.120
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 7638): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 3039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager( 3039): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3820): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3820): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3820): bBrokenPipe = false
,W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/ActivityManager( 3039): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3820): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3820): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3820): bBrokenPipe = false
,E/TEST-APN( 3798): query for APN: check-permission succ 
,E/TEST-APN( 3798): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3039): No APN found to select.
,W/GNSS_ADAPTER( 3039): This function not used.
W/GNSS_ADAPTER( 3039): This function not used.
,E/TEST-APN( 3798): query for APN: check-permission succ 
E/TEST-APN( 3798): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3039): No APN found to select.
,W/GNSS_ADAPTER( 3039): This function not used.
W/GNSS_ADAPTER( 3039): This function not used.
,I/HwEmailTag( 7664): MailAppProvider->onCreate->begin, consuming 1449756680891ms->-prefixstartupperformance-
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 3039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 3039): do suspend true
,I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 3039): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 3039): link address 192.168.1.120/24
,E/WifiStateMachine( 3039): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3039): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 3039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/HwEmailTag( 7664): MailAppProvider->onCreate->end, consuming 1449756680927ms->-prefixstartupperformance-
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3039): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,I/HwCust  ( 7664): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 7664): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 7664): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwSystemManager( 3638): aor:Network Stats Updated
I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwCust  ( 7664): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/HwEmailTag( 7664): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7664): HwUtils->initStaticVarsAsync
,I/HwEmailTag( 7664): HwUtils->initStaticVarsAsync
I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwCust  ( 7664): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/HwEmailTag( 7664): EmailContent->init->consuming:20ms->;-prefixstartupperformance-
,I/HwEmailTag( 7664): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 7664): EmailProvider->INTEGRITY_CHECK_URI != null
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/HwEmailTag( 7664): EmailProvider->onCreate->end, consuming 33ms->-prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->onCreate->end, consuming 33ms->-prefixstartupperformance-
,I/HwEmailTag( 7664): EmailProvider->resetVisibleLimits->start:1449756681023 ->-prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->resetVisibleLimits->start:1449756681022 ->-prefixstartupperformance-
,I/HwCust  ( 7664): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 7664): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7664): HwUtils->initStaticVarsAsync->run:consuming:50ms; bidiFormatter:android.support.v4.text.BidiFormatter@262779b1;accountsProjSize:42
,I/HwEmailTag( 7664): HwUtils->initStaticVarsAsync->run:consuming:53ms; bidiFormatter:android.support.v4.text.BidiFormatter@262779b1;accountsProjSize:42
,I/HwEmailTag( 7664): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 25ms.
,I/System  ( 3039): core_booster, getBoosterConfig = false
,I/HwEmailTag( 7664): DBHelper->onOpen-> EmailProvider.db
,E/WifiStateMachine( 3039):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:17088] from screen [on:0 period:-1942264959] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,I/HwEmailTag( 7664): EmailProvider->initBuildCache->start->1449756681092->-prefixstartupperformance-
,I/HwEmailTag( 7664): EmailProvider->buildCache->end, consuming:1ms;
,I/HwEmailTag( 7664): EmailProvider->initBuildCache->start->1449756681092; consuming:2->-prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->uiAccounts->start:1449756681094
,I/HwEmailTag( 7664): EmailProvider->resetVisibleLimits->getDatabase, consuming:71ms;-prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7664): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7664): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 14ms.
,I/HwEmailTag( 7664): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7664): EmailProvider->resetVisibleLimits->getDatabase, consuming:119ms;-prefixstartupperformance-
I/HwEmailTag( 7664): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/art     ( 3039): Explicit concurrent mark sweep GC freed 91038(4MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 2.129ms total 211.849ms
,I/HwEmailTag( 7664): EmailApplication->onCreate->begin, consuming 264ms->-prefixstartupperformance-
,I/HwEmailTag( 7664): EmailProvider->uiAccounts->start:1449756681094;end,consuming:159
I/HwEmailTag( 7664): EmailProvider->query->1449756681021;end;;consuming:232ms;
,I/HwEmailTag( 7664): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
I/HwCust  ( 7664): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
I/HwCust  ( 7664): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 7664): EmailApplication->onCreate->end, consuming 271ms->-prefixstartupperformance-
,I/HwEmailTag( 7664): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7664): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7664): EmailProvider->notifyNetworkChanged->
,I/ActivityManager( 3039): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 3039): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/DownloadManager( 3380): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
I/HwSystemManager( 3638): HoldService:uid:10050 pid:7246 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10050,7246
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10050
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10050, pid: 7246
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10050, pid: 7246
I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,I/HwCust  ( 6968): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 6968): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/MagazineUtils( 3313): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 6968): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6968): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/WifiTracker( 3401): STATE =1
,W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/WifiTracker( 3401): STATE =1
,E/HwOUC   ( 7704): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7704): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7704): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 7704): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7704): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7704): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7704): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7704): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6508): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwSystemManager( 3638): HoldService:uid:10001 pid:6575 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10001,6575
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10001, pid: 6575
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10001, pid: 6575
,W/asset   ( 7727): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 7727): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 7727): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7727): ThemeHelperretry to get Settings
,W/asset   ( 7751): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/jxcore-log( 7556): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7556): 
,I/HwCust  ( 7751): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/System  ( 7099): core_booster, getBoosterConfig = false
,E/WifiStateMachine( 3039):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3039):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 191us total 25.461ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 196us total 24.435ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 258us total 23.315ms
,I/Babel   ( 7099): connection state changed from UNKNOWN to CONNECTED
,I/HwSystemManager( 3638): HoldService:uid:10004 pid:6309 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10004,6309
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10004
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10004, pid: 6309
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10004, pid: 6309
,W/ContextImpl( 7775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7775): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7775):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7775):   adb logcat -s GAv4
,W/ContextImpl( 7775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7775): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7775): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7775): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7775): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 7775): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 7775): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 7775): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 7775): Loading: webviewchromium
,I/LibraryLoader( 7775): Time to load native libraries: 4 ms (timestamps 1469-1473)
,I/LibraryLoader( 7775): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 7775): Expected native library version number "",actual native library version number ""
,I/chromium( 7775): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7775): Initializing chromium process, renderers=0
,W/art     ( 7775): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7775): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 7775): Requires BLUETOOTH permission
I/chromium( 7775): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
I/chromium( 7775): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 7775): Starting up...
,I/HwSystemManager( 3638): HoldService:uid:10010 pid:7225 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10010,7225
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10010
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10010, pid: 7225
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10010, pid: 7225
,I/HwEmailTag( 7664): EmailProvider->query->1449756683028;end;;consuming:2ms;
,I/HwSystemManager( 3638): HoldService:uid:1000 pid:7334 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:1000,7334
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
W/MediaProcessHandler( 3039): processOp uid 1000 is not concerned!
,I/HwEmailTag( 7664): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7664): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7664): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3380): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 6968): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6968): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/HwEmailTag( 7664): AccountReconciler->reconcileAccountsInternal->consuming:122ms
,I/MagazineUtils( 3313): is magazine unlock on, now is lock screen diabled mode
,I/HwEmailTag( 7664): EmailProvider->query->1449756683157;end;;consuming:2ms;
,I/HwOUC   ( 7704): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7704): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6508): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/art     ( 7727): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7727): ThemeHelperretry to get Settings
I/HwEmailTag( 7664): AccountReconciler->reconcileAccountsInternal->consuming:9ms
,I/HwCust  ( 7869): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7869): EmailContent->init->consuming:23ms->;-prefixstartupperformance-
,I/HwEmailTag( 7869): Exchange->onCreate
,I/HwEmailTag( 7664): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/PG Utils( 7869): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7664): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 7664): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 7664): CleanRecipient->onCreate
I/HwEmailTag( 7664): Device->getDeviceId->
,I/HwEmailTag( 7664): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 7664): Device->getDeviceIdInternal->get id from deviceName, return successfully.
,I/HwEmailTag( 7664): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 7664): CleanRecipient->onHandleIntent->action is null
,I/HwEmailTag( 7664): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 7664): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 7664): CleanRecipient->onDestroy
I/PG Utils( 7869): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7664): EmailProvider->query->1449756683277;end;;consuming:1ms;
,I/HwEmailTag( 7869): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/HwSystemManager( 3638): HoldService:uid:10044 pid:7371 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10044,7371
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10044, pid: 7371
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10044, pid: 7371
,I/HwEmailTag( 7664): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 7664): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/ArpVerifier( 3039): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/ActivityManager( 3039): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3820): Network connection true
I/AccountTypeManager( 6968): Adding account type = com.android.contacts.model.account.ExchangeAccountType@26b7f152 in the cache
I/SUPL20_SPIMESLP-SENDING( 3820): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3820): bBrokenPipe = false
,I/NetworkMonitor( 7010): type=WIFI subType= reason=null isConnected=true
I/HwEmailTag( 7664): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7664): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7664): EmailProvider->notifyNetworkChanged->
,I/SimFactoryManager( 6968): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6968): Get SIM state from SIM factory manager: 1,For slotId:1
,E/TEST-APN( 3798): query for APN: check-permission succ ,
,E/TEST-APN( 3798): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/AccountTypeManager( 6968): Adding account type = com.android.contacts.model.account.ExternalAccountType@3f44ec23 in the cache
,I/DownloadManager( 3380): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,E/GpsLocationProvider( 3039): No APN found to select.
,W/GNSS_ADAPTER( 3039): This function not used.
W/GNSS_ADAPTER( 3039): This function not used.
,W/ResourceType( 6968): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6968): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6968): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6968): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
,I/Mms_TXM_SVC( 6968): onStartCommand send EVENT_NEW_INTENT. service-id 1
I/AccountTypeManager( 6968): Adding account type = com.android.contacts.model.account.ExternalAccountType@2683b34c in the cache
W/Mms_TXM_SVC( 6968): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/AccountTypeManager( 6968): Adding account type = com.android.contacts.model.account.GoogleAccountType@3f7caf95 in the cache
,I/MagazineUtils( 3313): is magazine unlock on, now is lock screen diabled mode
,E/ExternalAccountType( 6968): Unsupported attribute readOnly
,I/HwOUC   ( 7704): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7704): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/AccountTypeManager( 6968): AccountManager, account size is: 2
I/HwOUC   ( 7704): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/AccountTypeManager( 6968): Loaded meta-data for 5 account types, 3 accounts in 76ms(wall) 24ms(cpu)
,I/HwOUC   ( 7704): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 7704): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,E/HwSystemManager( 6508): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!,
,I/art     ( 7727): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7727): ThemeHelperretry to get Settings
,I/HwOUC   ( 7704): [Thread-124-124]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995),
,I/HwOUC   ( 7704): [Thread-124-124]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/Process ( 7704): Sending signal. PID: 7704 SIG: 9
,E/WifiStateMachine( 3039):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 3039):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 3039):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/HwSystemManager( 3638): HoldService:uid:10052 pid:7704 died,
I/HwSystemManager( 3638): HoldService:oldVersionKey:10052,7704
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10052
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10052, pid: 7704
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10052, pid: 7704
,I/HwEmailTag( 7664): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 7664): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 7664): EmailProvider->triggerPeroidSync->accountId:-1
,I/System  ( 4052): core_booster, getBoosterConfig = false
I/System  ( 4052): core_booster, getBoosterConfig = false
,I/HwEmailTag( 7664): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 7664): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7664): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 7664): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 7664): EmailProvider->query->1449756687019;end;;consuming:2ms;
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gcm.CONNECTED
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 5
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectedState what:131272 1 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:131272 1 0
E/WifiStateMachine( 3039):  ConnectModeState what:131272 1 0
E/WifiStateMachine( 3039):  DriverStartedState what:131272 1 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:131272 1 0
E/WifiStateMachine( 3039):  DefaultState what:131272 1 0
E/WifiStateMachine( 3039): Error! unhandled message{ when=-9ms what=131272 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/ArpVerifier( 3039): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,E/Thermal-daemon( 2331): [charger_ic] temp_new :31  temp_old :32
,E/Thermal-daemon( 2331): [ap] temp_new :31  temp_old :32
,I/art     ( 7727): System.exit called, status: 0
,I/AndroidRuntime( 7727): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3638): HoldService:uid:10060 pid:7727 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10060,7727
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10060
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10060, pid: 7727
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10060, pid: 7727
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/VacuumService( 4052): Vacuum at: now=1449756699489 tag=VacuumService
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/SyncManager( 3039): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,I/PG Utils( 5984): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 4052): Scheduling Phenotype for one-off execution 3324 seconds from now (1449756699803)
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 4052): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4052): Using platform SSLCertificateSocketFactory
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3039): Explicit concurrent mark sweep GC freed 38927(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.911ms total 180.938ms
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 4052): core_booster, getBoosterConfig = false
,I/System  ( 4052): core_booster, getBoosterConfig = false
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 6
E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :30  temp_old :31
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/HwSystemManager( 3638): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3638): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 3638): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3638): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3638): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3638): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3638): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3638): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3638): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1144369152 [332800000,437657600,542515200]
I/HwSystemManager( 3638): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3638): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,I/ClearcutLoggerApiImpl( 4052): disconnect managed GoogleApiClient
,E/Thermal-daemon( 2331): [charger_ic] temp_new :30  temp_old :31
,I/ActivityManager( 3039): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
I/TimeLayout( 3401): time = 15:12
I/TimeLayout( 3401): updateDate date = 12/10/2015
,I/TimeLayout( 3401): weekDay = Thursday
,I/bluedroid( 4936): bt interface: [set_adapter_property]
W/bt-btif ( 4936): HAL bt_hal_cbacks->adapter_properties_cb
I/bluedroid( 4936): bt interface: [set_adapter_property]
W/bt-btm  ( 4936): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 4936): adapterPropertyChangedCallback with type:9 len:4
,W/bt-btm  ( 4936): BTM_SetConnectability
W/bt-btif ( 4936): BTM_SetConnectability
I/BluetoothAdapterProperties( 4936): adapterPropertyChangedCallback with type:7 len:4
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 8
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 0 firstTime = 182985 firstmBatteryCapacity =2205
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 3600 firstTime = 182985 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 11
E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 12
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2722): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2722): [rename_old_file:107]rename_old_file
I/OAM     ( 2722): 
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 63604 firstTime = 182985 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 90222 firstTime = 182985 firstmBatteryCapacity =2205
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :30
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 16
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 16
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5
E/WifiMonitor( 3039): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor( 3039): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 17
E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 7556): Connected to the server!
I/jxcore-log( 7556): 
,I/chromium( 7556): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 123607 firstTime = 182985 firstmBatteryCapacity =2205
,I/art     ( 3039): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,I/System  ( 3039): core_booster, getBoosterConfig = false
,I/System  ( 3039): core_booster, getBoosterConfig = false
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 18
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 19
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=62 dispatchEvent: HEART-BEAT-ACK: 19
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 150404 firstTime = 182985 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 20
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=63 dispatchEvent: HEART-BEAT-ACK: 20
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/art     ( 3039): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 21
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=64 dispatchEvent: HEART-BEAT-ACK: 21
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 180472 firstTime = 182985 firstmBatteryCapacity =2205
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 183607 firstTime = 182985 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 22
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=65 dispatchEvent: HEART-BEAT-ACK: 22
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 23
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=66 dispatchEvent: HEART-BEAT-ACK: 23
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
,I/TimeLayout( 3401): time = 15:16
,I/TimeLayout( 3401): updateDate date = 12/10/2015
,I/TimeLayout( 3401): weekDay = Thursday
,I/art     ( 3039): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 210563 firstTime = 182985 firstmBatteryCapacity =2205
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :30
,E/Thermal-daemon( 2331): [charger_ic] temp_new :30  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 24
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=67 dispatchEvent: HEART-BEAT-ACK: 24
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :30
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 25
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 25
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 26
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=69 dispatchEvent: HEART-BEAT-ACK: 26
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 27
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=70 dispatchEvent: HEART-BEAT-ACK: 27
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 28
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=71 dispatchEvent: HEART-BEAT-ACK: 28
,E/WifiStateMachine( 3039):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4936): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/wpa_supplicant( 3410): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
E/WifiMonitor( 3039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
,W/System.err( 3039): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3039): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3039): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3039): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3039): This is not beta user build
,W/wpa_supplicant( 3410): check_associate_result func start
,E/WifiMonitor( 3039): WifiMonitor notify network disconnect: null reason=0
,E/WifiStateMachine( 3039):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-57 rt=475363
,W/wpa_supplicant( 3410): STA MODE: Set shutdown wlan cmd SUCCESS
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=73 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3039):  ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 73 0 rt=476182  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/wpa_supplicant( 3410): process exception in STA mode
,W/wpa_supplicant( 3410): check_associate_result func start
E/WifiStateMachine( 3039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 73 0 rt=476184  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 73 0 rt=476186  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3039): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3039): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 3039): do suspend true
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3410): set current WIFI status to BT!
,I/bluetooth-coex( 4936): btcoex_socket_server: accept socket success
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/ArpVerifier( 3039): current SSID is empty.
I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 3039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3039): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3039): setScanAlarm false period 0 initial delay 0
E/WifiStateMachine( 3039):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3039): setScanAlarm true period 0 initial delay 200
,I/ActivityManager( 3039): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3039): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/HwSystemManager( 3638): aor:Network Stats Updated
I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,I/HwSystemManager( 3638): aor:Network Stats Updated
I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/NetworkSpeedManagerEx( 3401): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3401): wifiManager = android.net.wifi.WifiManager@b040d57
,I/NetworkSpeedManagerEx( 3401): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3401): stop
,I/WifiTracker( 3401): STATE =1
,W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3401): STATE =1
,I/WifiTracker( 3401): STATE =1
,E/ArpVerifier( 3039): current WIFI rssi:-127 is weak
,E/Thermal-daemon( 2331): [charger_ic] temp_new :30  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 29
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=74 dispatchEvent: HEART-BEAT-ACK: 29
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/System  ( 4052): core_booster, getBoosterConfig = false
,I/System  ( 4052): core_booster, getBoosterConfig = false
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
I/TimeLayout( 3401): time = 15:17
,I/TimeLayout( 3401): updateDate date = 12/10/2015
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/System  ( 4052): core_booster, getBoosterConfig = false
I/System  ( 4052): core_booster, getBoosterConfig = false
I/TimeLayout( 3401): weekDay = Thursday
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gcm.DISCONNECTED
,W/View    ( 3401): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{21ea24cc V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,W/ArpVerifier( 3039): ignore msg MSG_CHECK_WIFI_STATE, msg token = 11, expected token = 14
,I/ActivityManager( 3039): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3820): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3820): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3820): bBrokenPipe = false
,I/HwEmailTag( 7664): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7664): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7664): EmailProvider->notifyNetworkChanged->
,I/ActivityManager( 3039): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3820): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3820): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3820): bBrokenPipe = false
,E/TEST-APN( 3798): query for APN: check-permission succ 
E/TEST-APN( 3798): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/DownloadManager( 3380): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 6968): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 6968): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3313): is magazine unlock on, now is lock screen diabled mode
,I/art     ( 3798): Explicit concurrent mark sweep GC freed 37618(2007KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.170ms total 62.431ms
,E/GpsLocationProvider( 3039): No APN found to select.
,W/GNSS_ADAPTER( 3039): This function not used.
,W/GNSS_ADAPTER( 3039): This function not used.
,E/TEST-APN( 3798): query for APN: check-permission succ 
E/TEST-APN( 3798): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3039): No APN found to select.
,W/GNSS_ADAPTER( 3039): This function not used.
W/GNSS_ADAPTER( 3039): This function not used.
,E/HwOUC   ( 8272): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8272): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8272): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 8272): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8272): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8272): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8272): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8272): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6508): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,W/asset   ( 8295): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8295): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/Babel   ( 7099): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 5984): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5984): num queued entries: 0
,I/iu.UploadsManager( 5984): num updated entries: 0
,I/iu.SyncManager( 5984): NEXT; no task
,I/HwSystemManager( 3638): HoldService:uid:10026 pid:7191 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10026,7191
I/HwEmailTag( 7664): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10026
I/HwEmailTag( 7664): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7664): EmailProvider->notifyNetworkChanged->
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10026, pid: 7191
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10026, pid: 7191
,I/DownloadManager( 3380): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 6968): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6968): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3313): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8272): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8272): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6508): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwEmailTag( 7664): EmailProvider->handleNetworkChanged->network is bad, WON'T start new EmailConnectivityTask
I/HwEmailTag( 7664): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7664): EmailProvider->triggerPeroidSync->accountId:-1
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=75 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 3039): handleEvent 13  CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 30
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=76 dispatchEvent: HEART-BEAT-ACK: 30
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :30
,I/art     ( 8295): System.exit called, status: 0
I/AndroidRuntime( 8295): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3638): HoldService:uid:10060 pid:8295 died
I/HwSystemManager( 3638): HoldService:oldVersionKey:10060,8295
I/HwSystemManager( 3638): BgPowerManagerService:onProcessDied uid = 10060
E/HsmCoreServiceImpl( 3039): onTransact in code is: 102
I/MediaProcessHandler( 3039): processOp opType: 1, uid: 10060, pid: 8295
W/MediaProcessHandler( 3039): remove target not exist, maybe the UI process: uid: 10060, pid: 8295
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 31
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=77 dispatchEvent: HEART-BEAT-ACK: 31
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 32
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=78 dispatchEvent: HEART-BEAT-ACK: 32
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 33
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=79 dispatchEvent: HEART-BEAT-ACK: 33
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 34
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=80 dispatchEvent: HEART-BEAT-ACK: 34
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 35
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=81 dispatchEvent: HEART-BEAT-ACK: 35
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 36
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=82 dispatchEvent: HEART-BEAT-ACK: 36
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 37
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=83 dispatchEvent: HEART-BEAT-ACK: 37
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 38
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=84 dispatchEvent: HEART-BEAT-ACK: 38
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 39
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=85 dispatchEvent: HEART-BEAT-ACK: 39
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 40
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=86 dispatchEvent: HEART-BEAT-ACK: 40
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 41
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=87 dispatchEvent: HEART-BEAT-ACK: 41
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 481279 firstTime = 182985 firstmBatteryCapacity =2205
,E/HwSystemManager( 3638): BgPowerManagerService: conusmPower = 1 result = 7 flag1 =false flag2 = false
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 0 firstTime = 666590 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 42
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=88 dispatchEvent: HEART-BEAT-ACK: 42
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 43
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=89 dispatchEvent: HEART-BEAT-ACK: 43
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 44
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=90 dispatchEvent: HEART-BEAT-ACK: 44
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 45
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=91 dispatchEvent: HEART-BEAT-ACK: 45
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 46
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=92 dispatchEvent: HEART-BEAT-ACK: 46
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 47
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=93 dispatchEvent: HEART-BEAT-ACK: 47
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 48
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=94 dispatchEvent: HEART-BEAT-ACK: 48
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 49
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=95 dispatchEvent: HEART-BEAT-ACK: 49
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 50
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=96 dispatchEvent: HEART-BEAT-ACK: 50
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
I/TimeLayout( 3401): time = 15:22
,I/TimeLayout( 3401): updateDate date = 12/10/2015
,I/TimeLayout( 3401): weekDay = Thursday
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 51
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=97 dispatchEvent: HEART-BEAT-ACK: 51
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 148078 firstTime = 666590 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 52
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=98 dispatchEvent: HEART-BEAT-ACK: 52
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 53
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=99 dispatchEvent: HEART-BEAT-ACK: 53
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 54
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=100 dispatchEvent: HEART-BEAT-ACK: 54
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 55
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=101 dispatchEvent: HEART-BEAT-ACK: 55
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 208230 firstTime = 666590 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 56
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=102 dispatchEvent: HEART-BEAT-ACK: 56
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 57
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=103 dispatchEvent: HEART-BEAT-ACK: 57
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 238316 firstTime = 666590 firstmBatteryCapacity =2204
,I/AGNSSCONTROL( 2725): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2725): void kill_timer(timer_t) -- 102: Timer: kill a timer 2874879872
,I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2874909160
I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2725): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2725): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
,E/Lss-gw  ( 2725): AllowSendingCellIdsToServer could not remove file. Error 2
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449757478417, wifi_time:1449756661474
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:9e:93:4e:3e:ba:c5
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:38:f8:89:11:e9:11
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:3
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:1
,I/AGNSSCONTROL( 2725): int MyLssGwCommunicator::sendRequestWithWlanInfo(EPH_TYPE, unsigned char*, int, bool) -- 73: sendRequestWithWlanInfo called, wlanLen:18
,E/Lss     ( 8690): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8690): No reference location.
W/Lss     ( 8690): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3202 bytes of data
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:4968675, nTOWassist:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:81, iode3:81, m0:-967115769.000000, delta_n:14526.000000, ecc:129437748.000000, ek:0.000000, sqrt_a:2702009717.000000, omega_0:549977455.000000, i0:643880151.000000, omega:-1507047801.000000, omega_dot:-22756.000000, i_dot:1868.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:922.000000, cus:4007.000000, crc:7105.000000, crs:945.000000, cic:205.000000, cis:53.000000, group_delay:-44.000000, af0:1283382.000000, af1:6.000000, af2:0.000000, aodc:81, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:68, iode3:68, m0:23149028.000000, delta_n:13388.000000, ecc:1959661.000000, ek:0.000000, sqrt_a:2701964653.000000, omega_0:572815240.000000, i0:658319580.000000, omega:-2109760734.000000, omega_dot:-22396.000000, i_dot:1716.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:726.000000, cus:4167.000000, crc:7423.000000, crs:794.000000, cic:-1.000000, cis:14.000000, group_delay:9.000000, af0:235861.000000, af1:57.000000, af2:0.000000, aodc:68, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:163, iode3:163, m0:1062402435.000000, delta_n:11542.000000, ecc:13890033.000000, ek:0.000000, sqrt_a:2701983603.000000, omega_0:-144880477.000000, i0:657474829.000000, omega:-1096011801.000000, omega_dot:-21833.000000, i_dot:307.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2761.000000, cus:5744.000000, crc:5550.000000, crs:-3142.000000, cic:-3.000000, cis:-38.000000, group_delay:10.000000, af0:-33654.000000, af1:-13.000000, af2:0.000000, aodc:163, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:1, iode2:95, iode3:95, m0:1546651437.000000, delta_n:14168.000000, ecc:7572759.000000, ek:0.000000, sqrt_a:2702011485.000000, omega_0:1287578492.000000, i0:655550033.000000, omega:-2018845324.000000, omega_dot:-23061.000000, i_dot:-931.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-624.000000, cus:2879.000000, crc:8835.000000, crs:-748.000000, cic:-26.000000, cis:19.000000, group_delay:7.000000, af0:86482.000000, af1:57.000000, af2:0.000000, aodc:95, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:32, iode3:32, m0:-2083673369.000000, delta_n:11154.000000, ecc:48074158.000000, ek:0.000000, sqrt_a:2701950829.000000, omega_0:-823131348.000000, i0:676743799.000000, omega:437741923.000000, omega_dot:-22464.000000, i_dot:-590.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2507.000000, cus:1139.000000, crc:11313.000000, crs:-2913.000000, cic:-2.000000, cis:-6.000000, group_delay:-27.000000, af0:756390.000000, af1:26.000000, af2:0.000000, aodc:32, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:89, iode3:89, m0:98789710.000000, delta_n:11711.000000, ecc:71573713.000000, ek:0.000000, sqrt_a:2702023927.000000, omega_0:2058199507.000000, i0:659996492.000000, omega:-1330371095.000000, omega_dot:-22015.000000, i_dot:-1065.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1603.000000, cus:6331.000000, crc:5051.000000, crs:1801.000000, cic:-69.000000, cis:56.000000, group_delay:-20.000000, af0:35070.000000, af1:-21.000000, af2:0.000000, aodc:89, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:64, iode3:64, m0:809539594.000000, delta_n:11045.000000, ecc:70881179.000000, ek:0.000000, sqrt_a:2702008246.000000, omega_0:-810316189.000000, i0:677108877.000000, omega:215022871.000000, omega_dot:-22644.000000, i_dot:-858.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2280.000000, cus:1259.000000, crc:11200.000000, crs:-2674.000000, cic:-18.000000, cis:37.000000, group_delay:-22.000000, af0:-125927.000000, af1:31.000000, af2:0.000000, aodc:64, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:37, iode3:37, m0:1194751982.000000, delta_n:16287.000000, ecc:140907190.000000, ek:0.000000, sqrt_a:2701991227.000000, omega_0:1271912071.000000, i0:631944933.000000, omega:-1316109537.000000, omega_dot:-24128.000000, i_dot:-904.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-955.000000, cus:2814.000000, crc:8398.000000, crs:-905.000000, cic:-100.000000, cis:-225.000000, group_delay:-24.000000, af0:990761.000000, af1:34.000000, af2:0.000000, aodc:37, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:19, iode3:19, m0:-354258077.000000, delta_n:16372.000000, ecc:43263710.000000, ek:0.000000, sqrt_a:2702002524.000000, omega_0:1236313334.000000, i0:632772239.000000, omega:881911892.000000, omega_dot:-24365.000000, i_dot:-880.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-538.000000, cus:2719.000000, crc:8415.000000, crs:-681.000000, cic:-18.000000, cis:23.000000, group_delay:-18.000000, af0:810327.000000, af1:25.000000, af2:0.000000, aodc:19, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:10
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:93, iode3:93, m0:865203476.000000, delta_n:16810.000000, ecc:68793355.000000, ek:0.000000, sqrt_a:2702001220.000000, omega_0:1272465676.000000, i0:630465837.000000, omega:-1400471870.000000, omega_dot:-24724.000000, i_dot:-997.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-725.000000, cus:2745.000000, crc:8458.000000, crs:-832.000000, cic:-93.000000, cis:20.000000, group_delay:-38.000000, af0:898389.000000, af1:32.000000, af2:0.000000, aodc:93, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:107, iode3:107, m0:-1130453385.000000, delta_n:13074.000000, ecc:33417038.000000, ek:0.000000, sqrt_a:2701995153.000000, omega_0:-1586950957.000000, i0:650417836.000000, omega:209382648.000000, omega_dot:-23190.000000, i_dot:891.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3567.000000, cus:2433.000000, crc:9238.000000, crs:4098.000000, cic:-26.000000, cis:-57.000000, group_delay:6.000000, af0:-19567.000000, af1:-5.000000, af2:0.000000, aodc:107, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:4, iode3:4, m0:1571046830.000000, delta_n:13146.000000, ecc:4313477.000000, ek:0.000000, sqrt_a:2702011383.000000, omega_0:-860705629.000000, i0:656505213.000000, omega:-217186696.000000, omega_dot:-23613.000000, i_dot:-481.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2042.000000, cus:574.000000, crc:11473.000000, crs:-2336.000000, cic:20.000000, cis:-12.000000, group_delay:16.000000, af0:-341695.000000, af1:-151.000000, af2:0.000000, aodc:4, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:16
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:27, iode3:27, m0:660114537.000000, delta_n:11606.000000, ecc:171995141.000000, ek:0.000000, sqrt_a:2702022440.000000, omega_0:-806799342.000000, i0:676196567.000000, omega:-1122500618.000000, omega_dot:-23515.000000, i_dot:-877.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2573.000000, cus:1772.000000, crc:10741.000000, crs:-2792.000000, cic:-186.000000, cis:-83.000000, group_delay:-24.000000, af0:1046514.000000, af1:23.000000, af2:0.000000, aodc:27, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:23
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:48, iode3:48, m0:-1835724982.000000, delta_n:13245.000000, ecc:14103085.000000, ek:0.000000, sqrt_a:2702004945.000000, omega_0:-1524874547.000000, i0:652181400.000000, omega:2141094938.000000, omega_dot:-23403.000000, i_dot:795.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3181.000000, cus:1686.000000, crc:10121.000000, crs:3680.000000, cic:26.000000, cis:-6.000000, group_delay:7.000000, af0:148299.000000, af1:46.000000, af2:0.000000, aodc:48, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:60, iode3:60, m0:-1527969227.000000, delta_n:14638.000000, ecc:97715132.000000, ek:0.000000, sqrt_a:2701992423.000000, omega_0:1344682068.000000, i0:646908511.000000, omega:131616316.000000, omega_dot:-23317.000000, i_dot:-1080.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-956.000000, cus:3319.000000, crc:8010.000000, crs:-1070.000000, cic:-22.000000, cis:-181.000000, group_delay:-7.000000, af0:93677.000000, af1:106.000000, af2:0.000000, aodc:60, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:1, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:1, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:2, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:5, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:2, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:1, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:6, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:1, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:6, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:6, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:0, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:6, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:6, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:4, usIod:69, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
,I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
,I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 58
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=104 dispatchEvent: HEART-BEAT-ACK: 58
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 59
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=105 dispatchEvent: HEART-BEAT-ACK: 59
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 60
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=106 dispatchEvent: HEART-BEAT-ACK: 60
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 61
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=107 dispatchEvent: HEART-BEAT-ACK: 61
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :28
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 298478 firstTime = 666590 firstmBatteryCapacity =2204
,E/Thermal-daemon( 2331): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 62
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=108 dispatchEvent: HEART-BEAT-ACK: 62
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 63
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=109 dispatchEvent: HEART-BEAT-ACK: 63
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
I/TimeLayout( 3401): time = 15:26
,I/TimeLayout( 3401): updateDate date = 12/10/2015
,I/TimeLayout( 3401): weekDay = Thursday
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :28
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 64
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=110 dispatchEvent: HEART-BEAT-ACK: 64
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 65
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=111 dispatchEvent: HEART-BEAT-ACK: 65
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 358637 firstTime = 666590 firstmBatteryCapacity =2204
E/HwSystemManager( 3638): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 66
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=112 dispatchEvent: HEART-BEAT-ACK: 66
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 67
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=113 dispatchEvent: HEART-BEAT-ACK: 67
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 68
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=114 dispatchEvent: HEART-BEAT-ACK: 68
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 69
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=115 dispatchEvent: HEART-BEAT-ACK: 69
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 70
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=116 dispatchEvent: HEART-BEAT-ACK: 70
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 71
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=117 dispatchEvent: HEART-BEAT-ACK: 71
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 0 firstTime = 1115468 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 72
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=118 dispatchEvent: HEART-BEAT-ACK: 72
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 73
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=119 dispatchEvent: HEART-BEAT-ACK: 73
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 31121 firstTime = 1115468 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 74
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=120 dispatchEvent: HEART-BEAT-ACK: 74
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 75
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=121 dispatchEvent: HEART-BEAT-ACK: 75
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 76
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=122 dispatchEvent: HEART-BEAT-ACK: 76
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 77
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=123 dispatchEvent: HEART-BEAT-ACK: 77
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 91124 firstTime = 1115468 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 78
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=124 dispatchEvent: HEART-BEAT-ACK: 78
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 79
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=125 dispatchEvent: HEART-BEAT-ACK: 79
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 120323 firstTime = 1115468 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 80
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=126 dispatchEvent: HEART-BEAT-ACK: 80
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 81
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=127 dispatchEvent: HEART-BEAT-ACK: 81
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 82
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=128 dispatchEvent: HEART-BEAT-ACK: 82
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 83
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=129 dispatchEvent: HEART-BEAT-ACK: 83
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 84
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=130 dispatchEvent: HEART-BEAT-ACK: 84
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 85
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=131 dispatchEvent: HEART-BEAT-ACK: 85
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 86
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=132 dispatchEvent: HEART-BEAT-ACK: 86
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 87
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=133 dispatchEvent: HEART-BEAT-ACK: 87
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 88
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=134 dispatchEvent: HEART-BEAT-ACK: 88
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 89
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=135 dispatchEvent: HEART-BEAT-ACK: 89
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 90
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=136 dispatchEvent: HEART-BEAT-ACK: 90
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 91
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=137 dispatchEvent: HEART-BEAT-ACK: 91
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 300795 firstTime = 1115468 firstmBatteryCapacity =2204
E/HwSystemManager( 3638): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 92
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=138 dispatchEvent: HEART-BEAT-ACK: 92
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 93
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=139 dispatchEvent: HEART-BEAT-ACK: 93
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 0 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 94
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=140 dispatchEvent: HEART-BEAT-ACK: 94
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 95
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=141 dispatchEvent: HEART-BEAT-ACK: 95
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 30072 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 96
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=142 dispatchEvent: HEART-BEAT-ACK: 96
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 97
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=143 dispatchEvent: HEART-BEAT-ACK: 97
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 98
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=144 dispatchEvent: HEART-BEAT-ACK: 98
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 99
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=145 dispatchEvent: HEART-BEAT-ACK: 99
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 100
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=146 dispatchEvent: HEART-BEAT-ACK: 100
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 101
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=147 dispatchEvent: HEART-BEAT-ACK: 101
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 120242 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 102
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=148 dispatchEvent: HEART-BEAT-ACK: 102
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 103
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=149 dispatchEvent: HEART-BEAT-ACK: 103
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 150385 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 104
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=150 dispatchEvent: HEART-BEAT-ACK: 104
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 105
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=151 dispatchEvent: HEART-BEAT-ACK: 105
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 180475 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 106
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=152 dispatchEvent: HEART-BEAT-ACK: 106
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 107
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=153 dispatchEvent: HEART-BEAT-ACK: 107
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 210562 firstTime = 1446347 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 108
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=154 dispatchEvent: HEART-BEAT-ACK: 108
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 109
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=155 dispatchEvent: HEART-BEAT-ACK: 109
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 240243 firstTime = 1446347 firstmBatteryCapacity =2204
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 240633 firstTime = 1446347 firstmBatteryCapacity =2204
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 110
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=156 dispatchEvent: HEART-BEAT-ACK: 110
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,E/HI110X_CHR_LOGD( 2723): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 111
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=157 dispatchEvent: HEART-BEAT-ACK: 111
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 112
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=158 dispatchEvent: HEART-BEAT-ACK: 112
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 113
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=159 dispatchEvent: HEART-BEAT-ACK: 113
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 114
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=160 dispatchEvent: HEART-BEAT-ACK: 114
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 115
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=161 dispatchEvent: HEART-BEAT-ACK: 115
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 116
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=162 dispatchEvent: HEART-BEAT-ACK: 116
E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 117
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=163 dispatchEvent: HEART-BEAT-ACK: 117
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/AGNSSCONTROL( 2725): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2725): void kill_timer(timer_t) -- 102: Timer: kill a timer 2874909160
I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2874924160
I/AGNSSCONTROL( 2725): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2725): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2725): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2725): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449758378415, wifi_time:1449756661474
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:9e:93:4e:3e:ba:c5
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:38:f8:89:11:e9:11
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:3
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:1
I/AGNSSCONTROL( 2725): int MyLssGwCommunicator::sendRequestWithWlanInfo(EPH_TYPE, unsigned char*, int, bool) -- 73: sendRequestWithWlanInfo called, wlanLen:18
,E/Lss     ( 9474): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 9474): No reference location.
W/Lss     ( 9474): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3202 bytes of data
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:4979925, nTOWassist:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:81, iode3:81, m0:-967115769.000000, delta_n:14526.000000, ecc:129437748.000000, ek:0.000000, sqrt_a:2702009717.000000, omega_0:549977455.000000, i0:643880151.000000, omega:-1507047801.000000, omega_dot:-22756.000000, i_dot:1868.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:922.000000, cus:4007.000000, crc:7105.000000, crs:945.000000, cic:205.000000, cis:53.000000, group_delay:-44.000000, af0:1283382.000000, af1:6.000000, af2:0.000000, aodc:81, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:68, iode3:68, m0:23149028.000000, delta_n:13388.000000, ecc:1959661.000000, ek:0.000000, sqrt_a:2701964653.000000, omega_0:572815240.000000, i0:658319580.000000, omega:-2109760734.000000, omega_dot:-22396.000000, i_dot:1716.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:726.000000, cus:4167.000000, crc:7423.000000, crs:794.000000, cic:-1.000000, cis:14.000000, group_delay:9.000000, af0:235861.000000, af1:57.000000, af2:0.000000, aodc:68, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:163, iode3:163, m0:1062402435.000000, delta_n:11542.000000, ecc:13890033.000000, ek:0.000000, sqrt_a:2701983603.000000, omega_0:-144880477.000000, i0:657474829.000000, omega:-1096011801.000000, omega_dot:-21833.000000, i_dot:307.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2761.000000, cus:5744.000000, crc:5550.000000, crs:-3142.000000, cic:-3.000000, cis:-38.000000, group_delay:10.000000, af0:-33654.000000, af1:-13.000000, af2:0.000000, aodc:163, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:1, iode2:95, iode3:95, m0:1546651437.000000, delta_n:14168.000000, ecc:7572759.000000, ek:0.000000, sqrt_a:2702011485.000000, omega_0:1287578492.000000, i0:655550033.000000, omega:-2018845324.000000, omega_dot:-23061.000000, i_dot:-931.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-624.000000, cus:2879.000000, crc:8835.000000, crs:-748.000000, cic:-26.000000, cis:19.000000, group_delay:7.000000, af0:86482.000000, af1:57.000000, af2:0.000000, aodc:95, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:32, iode3:32, m0:-2083673369.000000, delta_n:11154.000000, ecc:48074158.000000, ek:0.000000, sqrt_a:2701950829.000000, omega_0:-823131348.000000, i0:676743799.000000, omega:437741923.000000, omega_dot:-22464.000000, i_dot:-590.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2507.000000, cus:1139.000000, crc:11313.000000, crs:-2913.000000, cic:-2.000000, cis:-6.000000, group_delay:-27.000000, af0:756390.000000, af1:26.000000, af2:0.000000, aodc:32, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:89, iode3:89, m0:98789710.000000, delta_n:11711.000000, ecc:71573713.000000, ek:0.000000, sqrt_a:2702023927.000000, omega_0:2058199507.000000, i0:659996492.000000, omega:-1330371095.000000, omega_dot:-22015.000000, i_dot:-1065.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1603.000000, cus:6331.000000, crc:5051.000000, crs:1801.000000, cic:-69.000000, cis:56.000000, group_delay:-20.000000, af0:35070.000000, af1:-21.000000, af2:0.000000, aodc:89, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:64, iode3:64, m0:809539594.000000, delta_n:11045.000000, ecc:70881179.000000, ek:0.000000, sqrt_a:2702008246.000000, omega_0:-810316189.000000, i0:677108877.000000, omega:215022871.000000, omega_dot:-22644.000000, i_dot:-858.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2280.000000, cus:1259.000000, crc:11200.000000, crs:-2674.000000, cic:-18.000000, cis:37.000000, group_delay:-22.000000, af0:-125927.000000, af1:31.000000, af2:0.000000, aodc:64, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:37, iode3:37, m0:1194751982.000000, delta_n:16287.000000, ecc:140907190.000000, ek:0.000000, sqrt_a:2701991227.000000, omega_0:1271912071.000000, i0:631944933.000000, omega:-1316109537.000000, omega_dot:-24128.000000, i_dot:-904.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-955.000000, cus:2814.000000, crc:8398.000000, crs:-905.000000, cic:-100.000000, cis:-225.000000, group_delay:-24.000000, af0:990761.000000, af1:34.000000, af2:0.000000, aodc:37, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:19, iode3:19, m0:-354258077.000000, delta_n:16372.000000, ecc:43263710.000000, ek:0.000000, sqrt_a:2702002524.000000, omega_0:1236313334.000000, i0:632772239.000000, omega:881911892.000000, omega_dot:-24365.000000, i_dot:-880.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-538.000000, cus:2719.000000, crc:8415.000000, crs:-681.000000, cic:-18.000000, cis:23.000000, group_delay:-18.000000, af0:810327.000000, af1:25.000000, af2:0.000000, aodc:19, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:10
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:93, iode3:93, m0:865203476.000000, delta_n:16810.000000, ecc:68793355.000000, ek:0.000000, sqrt_a:2702001220.000000, omega_0:1272465676.000000, i0:630465837.000000, omega:-1400471870.000000, omega_dot:-24724.000000, i_dot:-997.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-725.000000, cus:2745.000000, crc:8458.000000, crs:-832.000000, cic:-93.000000, cis:20.000000, group_delay:-38.000000, af0:898389.000000, af1:32.000000, af2:0.000000, aodc:93, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:107, iode3:107, m0:-1130453385.000000, delta_n:13074.000000, ecc:33417038.000000, ek:0.000000, sqrt_a:2701995153.000000, omega_0:-1586950957.000000, i0:650417836.000000, omega:209382648.000000, omega_dot:-23190.000000, i_dot:891.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3567.000000, cus:2433.000000, crc:9238.000000, crs:4098.000000, cic:-26.000000, cis:-57.000000, group_delay:6.000000, af0:-19567.000000, af1:-5.000000, af2:0.000000, aodc:107, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:4, iode3:4, m0:1571046830.000000, delta_n:13146.000000, ecc:4313477.000000, ek:0.000000, sqrt_a:2702011383.000000, omega_0:-860705629.000000, i0:656505213.000000, omega:-217186696.000000, omega_dot:-23613.000000, i_dot:-481.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2042.000000, cus:574.000000, crc:11473.000000, crs:-2336.000000, cic:20.000000, cis:-12.000000, group_delay:16.000000, af0:-341695.000000, af1:-151.000000, af2:0.000000, aodc:4, health:0, toc:25199, toe:25199, status:0, code_on_L2:1, fit_interval_flag:0, aodo:16
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:27, iode3:27, m0:660114537.000000, delta_n:11606.000000, ecc:171995141.000000, ek:0.000000, sqrt_a:2702022440.000000, omega_0:-806799342.000000, i0:676196567.000000, omega:-1122500618.000000, omega_dot:-23515.000000, i_dot:-877.000000
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2573.000000, cus:1772.000000, crc:10741.000000, crs:-2792.000000, cic:-186.000000, cis:-83.000000, group_delay:-24.000000, af0:1046514.000000, af1:23.000000, af2:0.000000, aodc:27, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:23
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:48, iode3:48, m0:-1835724982.000000, delta_n:13245.000000, ecc:14103085.000000, ek:0.000000, sqrt_a:2702004945.000000, omega_0:-1524874547.000000, i0:652181400.000000, omega:2141094938.000000, omega_dot:-23403.000000, i_dot:795.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:3181.000000, cus:1686.000000, crc:10121.000000, crs:3680.000000, cic:26.000000, cis:-6.000000, group_delay:7.000000, af0:148299.000000, af1:46.000000, af2:0.000000, aodc:48, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:60, iode3:60, m0:-1527969227.000000, delta_n:14638.000000, ecc:97715132.000000, ek:0.000000, sqrt_a:2701992423.000000, omega_0:1344682068.000000, i0:646908511.000000, omega:131616316.000000, omega_dot:-23317.000000, i_dot:-1080.000000
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-956.000000, cus:3319.000000, crc:8010.000000, crs:-1070.000000, cic:-22.000000, cis:-181.000000, group_delay:-7.000000, af0:93677.000000, af1:106.000000, af2:0.000000, aodc:60, health:0, toc:25200, toe:25200, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2725): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:71, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2725): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
,I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2725): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2725): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 118
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=164 dispatchEvent: HEART-BEAT-ACK: 118
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/art     ( 3039): Can not find class: Lcom/android/server/AppOpsService$1$1;
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 119
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=165 dispatchEvent: HEART-BEAT-ACK: 119
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 391035 firstTime = 1446347 firstmBatteryCapacity =2204
E/HwSystemManager( 3638): BgPowerManagerService: conusmPower = -1 result = -9 flag1 =false flag2 = false
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 120
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=166 dispatchEvent: HEART-BEAT-ACK: 120
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/ActivityManager( 3039): filter receiver for action = com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS
,I/art     ( 3039): Can not find class: Lcom/android/server/am/ActivityManagerService$24;
,I/art     ( 3039): Can not find class: Lcom/android/server/am/ProcessStatsService$2;
,I/HwLauncher( 3846): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3401): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3401): hand message 1
I/TimeManager( 3401): notify time change. size = 2
I/TimeLayout( 3401): time = 15:40
I/TimeLayout( 3401): updateDate date = 12/10/2015
I/TimeLayout( 3401): weekDay = Thursday
I/HwSystemManager( 3638): aor:Network Stats Updated
I/HwSystemManager( 3638): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 3039): Can not find class: Lcom/android/server/pm/PackageManagerService$PackageUsage$1;
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3638): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3638): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3638): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3638): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3638): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3638): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/EventLogService( 5984): Aggregate from 1449756627492 (log), 1449756627492 (data)
,I/PG Utils( 5984): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4052): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Auth    ( 4052): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,I/PG Utils( 5984): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 121
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=167 dispatchEvent: HEART-BEAT-ACK: 121
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/HwSystemManager( 3638): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3638): BgPowerManagerService: mTimes = 0 firstTime = 1866589 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 122
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=168 dispatchEvent: HEART-BEAT-ACK: 122
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 123
E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=169 dispatchEvent: HEART-BEAT-ACK: 123
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3410): wlan0: HEART-BEAT-ACK: 124
,E/WifiMonitor( 3039): WifiMonitor:wlan0 cnt=170 dispatchEvent: HEART-BEAT-ACK: 124
,E/WifiStateMachine( 3039):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3039):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3039):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3039):  SupplicantStartedState what:147506 0 0
,TIME-OUT KILL (timeout was 1800000ms)
```
