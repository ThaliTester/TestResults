#### Test 50650278cb112b9_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 7838): CLASSPATH=/system/framework/am.jar
I/appproc ( 7838): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 7838): app_process:number,5,0
I/AndroidRuntime( 7838): readDownloadBoosterConfig: 'false'
I/        ( 7838): power log dlsym ok
E/android_hardware_fm.cpp( 7838): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 7838): ========64bit long size = 8
E/FM_HAL  ( 7838): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 7838): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 7838): 
I/fm_hisi ( 7838): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 7838): 
I/fm_hisi ( 7838): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 7838): 
E/android_hardware_fm.cpp( 7838): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 3044): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3044): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3044): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3044): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3675): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3675): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3850): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3850): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3850): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3675): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3850): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3850): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 7858): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 7858): Loading: webviewchromium
I/LibraryLoader( 7858): Time to load native libraries: 57 ms (timestamps 5212-5269)
I/LibraryLoader( 7858): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 7858): Expected native library version number "",actual native library version number ""
I/chromium( 7858): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7858): Initializing chromium process, renderers=0
W/art     ( 7858): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7858): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7858): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 7858): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 7858): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7858): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 7858): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 7858): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7858): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 7858): Can not find class: Landroid/widget/ViewStub;
I/art     ( 7858): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 7858): Can not find class: Landroid/app/ViewStub;
W/art     ( 7858): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7858): Attempt to remove local handle scope entry from IRT, ignoring
I/PhoneStatusBar( 3402): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3402): shouldTranslucent:true
I/PhoneStatusBar( 3402): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 7858): Initialized EGL, version 1.4
,I/ActivityManager( 3044): Displayed com.test.thalitest/.MainActivity: +1s76ms (total +1s148ms)
,W/IInputConnectionWrapper( 7858): showStatusIcon on inactive InputConnection
,I/chromium( 7858): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7858): 
,W/jxcore-log( 7858): Initializing JXcore engine
W/jxcore-log( 7858): JXcore engine is ready
,W/jxcore-log( 7858): Starting JXcore engine
,W/jxcore-log( 7858): Platform android
W/jxcore-log( 7858): 
W/jxcore-log( 7858): Process ARCH arm
W/jxcore-log( 7858): 
,I/art     ( 3044): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 7858): JXcore Cordova bridge is ready!
I/jxcore-log( 7858): 
W/jxcore-log( 7858): JXcore engine is started
,I/art     ( 6038): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,I/jxcore-log( 7858): Toggling radios to true
I/jxcore-log( 7858): 
,I/HwSystemManager( 3675): HoldService:checkBeforeShowDialog: uid:10295 pid:7858, permissionType:2097152
I/HwSystemManager( 3675): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 3044): allowOpenWifi blocked:false
,E/WifiStateMachine( 3044):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 3044): [109,870,082 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
I/jxcore-log( 7858): Radios toggled
I/jxcore-log( 7858): 
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3468): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3044): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/System.err( 3044): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3044): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3044): This is not beta user build
W/wpa_supplicant( 3468): check_associate_result func start
,I/jxcore-log( 7858): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): Perf Test app loaded loaded
I/jxcore-log( 7858): 
,I/Choreographer( 7858): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 7858): check test folder
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): found test : ./testFindPeers.js
I/jxcore-log( 7858): 
,W/wpa_supplicant( 3468): STA MODE: Set shutdown wlan cmd SUCCESS
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
W/wpa_supplicant( 3468): check_associate_result func start
I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
E/WifiStateMachine( 3044): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3044): setScanAlarm false period 20000 initial delay 0
E/WifiStateMachine( 3044): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3044): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 3044): do suspend true
,E/WifiMonitor( 3044): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
,I/jxcore-log( 7858): found test : ./testSendData.js
I/jxcore-log( 7858): 
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
I/ActivityManager( 3044): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/ArpVerifier( 3044): current SSID is empty.
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,E/WifiStateMachine( 3044):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3044): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3044):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 3044): [110,030,448 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
W/wpa_supplicant( 3468): check_associate_result func start
I/wpa_supplicant( 3468): wlan is down..., now start up...
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,E/WifiStateMachine( 3044):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110044
E/WifiStateMachine( 3044):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110044
E/native  ( 3044): do suspend true
,I/WifiTracker( 3402): STATE =1
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3402): STATE =1
,W/wpa_supplicant( 3468): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4904): btcoex_set_a2dp_priority: bdaddr: 000000000000
,I/bluetooth-coex( 4904): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3468): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3044): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3044): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
,I/art     ( 3044): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3044):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3044): setScanAlarm true period 0 initial delay 200
,E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=110814  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=110816  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=110832  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
I/chromium( 7858): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE,
E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=110845  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
,I/chromium( 7858): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,I/WifiTracker( 3402): STATE =1
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,I/WifiTracker( 3402): STATE =1
,I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 3044): handleEvent 12  CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3044): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 3044): couldn't identify event type - WPS-AP-AVAILABLE 
,E/WifiStateMachine( 3044):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:281 bcn=0
,E/WifiStateMachine( 3044):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:281 bcn=0
,I/wpa_supplicant( 3468): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 3044):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:281 bcn=0
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=34 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,E/WifiStateMachine( 3044):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:281 bcn=0
E/WifiStateMachine( 3044): [1,450,149,728,517 ms] noteScanEnd no scan source
W/wpa_supplicant( 3468): check_associate_result func start
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4904): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4904): btcoex_set_a2dp_priority: A2DP - no link control block
,I/bluetooth-coex( 4904): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,E/WifiStateMachine( 3044): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2082b128 sup_state=SCANNING debouncing=false
,E/WifiAutoJoinController ( 3044): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 3044): 01ABC c2:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 3044): ageScanResultsOut delay 40000 size 2 now 1450149728523
E/WifiAutoJoinController ( 3044): newSupplicantResults size=2 known=1 true
,E/WifiAutoJoinController ( 3044): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController ( 3044): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3044): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3044): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
,E/WifiAutoJoinController ( 3044): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiStateMachine( 3044):  DisconnectedState CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111519
E/WifiStateMachine( 3044):  ConnectModeState CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111520
E/WifiStateMachine( 3044):  DriverStartedState CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111520
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_TARGET_BSSID 34 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111521
E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=111521  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=111527  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/wpa_supplicant( 3468): check_associate_result func start
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112126  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
I/wpa_supplicant( 3468): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=37 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112127  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 3044): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72 SSID=0x
W/wpa_supplicant( 3468): check_associate_result func start
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 3044):  DisconnectedState CMD_ASSOCIATED_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=112143
E/WifiStateMachine( 3044):  ConnectModeState CMD_ASSOCIATED_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=112143
E/WifiStateMachine( 3044):  DriverStartedState CMD_ASSOCIATED_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=112143
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_ASSOCIATED_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=112144
E/WifiStateMachine( 3044):  DefaultState CMD_ASSOCIATED_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=112144
I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=112146  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,W/wpa_supplicant( 3468): check_associate_result func start
,E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=112153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE,
W/wpa_supplicant( 3468): check_associate_result func start
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=112156  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 3044): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=112158  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=40 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 3044): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3468): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 3044): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3468): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
,W/wpa_supplicant( 3468): check_associate_result func start
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3044):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112174
,E/WifiStateMachine( 3044):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112175
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
W/System.err( 3044): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3044): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3044): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 3044): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 3044): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 3044): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3044): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3044): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 3044): This is not beta user build
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3044): setScanAlarm false period 0 initial delay 0
I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3044): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48,
E/WifiStateMachine( 3044): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3044): obtaining wifi is conencted
,E/WifiStateMachine( 3044): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any,
E/WifiStateMachine( 3044): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3044): obtaining wifi is conencted
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,E/WifiStateMachine( 3044): Start Dhcp Watchdog 2
,E/WifiStateMachine( 3044):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=112206  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=112206  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=112207  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3044):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 3044):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,I/wpa_supplicant( 3468): set current WIFI status to BT!
I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
E/native  ( 3044): do suspend false
,E/WifiStateMachine( 3044): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 3044): noteBatchedScanstop()
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,I/WifiTracker( 3402): STATE =1
,I/WifiTracker( 3402): STATE =1
,I/WifiTracker( 3402): STATE =1
,I/DHCPCD  ( 7942): version 5.5.6 starting
,W/DHCPCD  ( 7942): hw_parse_xidfile 
I/DHCPCD  ( 7942): wlan0: dhcp start reboot
I/DHCPCD  ( 7942): wlan0: rebinding lease of 192.168.1.120
,W/ArpVerifier( 3044): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,I/OAM     ( 2752): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2752): [rename_old_file:107]rename_old_file
I/OAM     ( 2752): 
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager( 3044): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3827): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3827): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3827): bBrokenPipe = false
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/ActivityManager( 3044): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,E/TEST-APN( 3805): query for APN: check-permission succ 
E/TEST-APN( 3805): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/SUPL20_SCM( 3827): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3827): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3827): bBrokenPipe = false
,E/GpsLocationProvider( 3044): No APN found to select.
,W/GNSS_ADAPTER( 3044): This function not used.
W/GNSS_ADAPTER( 3044): This function not used.
,E/TEST-APN( 3805): query for APN: check-permission succ 
E/TEST-APN( 3805): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3044): No APN found to select.
,W/GNSS_ADAPTER( 3044): This function not used.
W/GNSS_ADAPTER( 3044): This function not used.
,I/HwEmailTag( 7949): MailAppProvider->onCreate->begin, consuming 1450149730937ms->-prefixstartupperformance-
,I/HwEmailTag( 7949): MailAppProvider->onCreate->end, consuming 1450149730962ms->-prefixstartupperformance-
,I/HwCust  ( 7949): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 7949): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 7949): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 7949): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 7949): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7949): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7949): HwUtils->initStaticVarsAsync
I/HwEmailTag( 7949): HwUtils->initStaticVarsAsync
,I/HwCust  ( 7949): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7949): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 7949): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 7949): EmailProvider->onCreate->end, consuming 32ms->-prefixstartupperformance-
I/HwEmailTag( 7949): EmailProvider->onCreate->end, consuming 32ms->-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailProvider->resetVisibleLimits->start:1450149731021 ->-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailProvider->resetVisibleLimits->start:1450149731022 ->-prefixstartupperformance-
I/HwCust  ( 7949): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 7949): EmailApplication->onCreate->begin, consuming 50ms->-prefixstartupperformance-
,I/HwEmailTag( 7949): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 7949): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
I/HwEmailTag( 7949): HwUtils->initStaticVarsAsync->run:consuming:47ms; bidiFormatter:android.support.v4.text.BidiFormatter@a397437;accountsProjSize:42
,I/HwEmailTag( 7949): HwUtils->initStaticVarsAsync->run:consuming:50ms; bidiFormatter:android.support.v4.text.BidiFormatter@a397437;accountsProjSize:42
,I/HwCust  ( 7949): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 7949): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 7949): EmailApplication->onCreate->end, consuming 56ms->-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7949): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7949): EmailProvider->notifyNetworkChanged->
,I/HwEmailTag( 7949): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 26ms.
,I/HwEmailTag( 7949): DBHelper->onOpen-> EmailProvider.db
,I/DHCPCD  ( 7942): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,I/HwEmailTag( 7949): EmailProvider->initBuildCache->start->1450149731093->-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 7949): EmailProvider->initBuildCache->start->1450149731093; consuming:2->-prefixstartupperformance-
,I/HwEmailTag( 7949): EmailProvider->resetVisibleLimits->getDatabase, consuming:74ms;-prefixstartupperformance-
I/HwEmailTag( 7949): EmailProvider->uiAccounts->start:1450149731095
I/HwEmailTag( 7949): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7949): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7949): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 12ms.
,I/HwEmailTag( 7949): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7949): EmailProvider->resetVisibleLimits->getDatabase, consuming:119ms;-prefixstartupperformance-
I/HwEmailTag( 7949): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7949): EmailProvider->uiAccounts->start:1450149731095;end,consuming:49
I/HwEmailTag( 7949): EmailProvider->query->1450149731021;end;;consuming:124ms;
,I/DownloadManager( 3381): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 3675): HoldService:uid:10050 pid:7559 died
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): HoldService:oldVersionKey:10050,7559
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10050, pid: 7559
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10050, pid: 7559
,I/HwCust  ( 7199): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 7199): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/MagazineUtils( 3314): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 7199): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 7199): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/DHCPCD  ( 7942): wlan0: checking for 192.168.1.120
,I/ActivityManager( 3044): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/art     ( 3044): Explicit concurrent mark sweep GC freed 62215(3MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.984ms total 191.435ms
,E/HwOUC   ( 7981): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7981): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7981): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 7981): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7981): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7981): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7981): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7981): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 3675): HoldService:uid:10001 pid:7031 died
I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): HoldService:oldVersionKey:10001,7031
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10001, pid: 7031
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10001, pid: 7031
,W/asset   ( 8006): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8006): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/DHCPCD  ( 7942): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/HwSystemManager( 6762): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10004
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): HoldService:uid:10004 pid:6375 died
I/HwSystemManager( 3675): HoldService:oldVersionKey:10004,6375
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10004, pid: 6375
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10004, pid: 6375
,I/jxcore-log( 7858): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7858): 
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3044):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3044):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3044):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 3044):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 3044): do suspend true
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 3044): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 3044): link address 192.168.1.120/24
,E/WifiStateMachine( 3044): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3044): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 3044):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3044): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/System  ( 3044): core_booster, getBoosterConfig = false
I/System  ( 7372): core_booster, getBoosterConfig = false
I/WifiTracker( 3402): STATE =1
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,E/WifiStateMachine( 3044):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:40543] from screen [on:0 period:-1549213815] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/Babel   ( 7372): connection state changed from UNKNOWN to CONNECTED
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3675): HoldService:uid:10010 pid:7537 died
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): HoldService:oldVersionKey:10010,7537
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10010, pid: 7537
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10010, pid: 7537
,I/WifiTracker( 3402): STATE =1
,I/WifiTracker( 3402): STATE =1
,W/ContextImpl( 8078): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8078): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/ContextImpl( 8078): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 8078): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8078):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8078):   adb logcat -s GAv4
,W/ContextImpl( 8078): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8078): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8078): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8078): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 8078): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 8078): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 8078): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 8078): Loading: webviewchromium
,I/LibraryLoader( 8078): Time to load native libraries: 3 ms (timestamps 5660-5663)
I/LibraryLoader( 8078): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 8078): Expected native library version number "",actual native library version number ""
,I/chromium( 8078): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8078): Initializing chromium process, renderers=0
,W/art     ( 8078): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 8078): Requires BLUETOOTH permission
W/chromium( 8078): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8078): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
,I/chromium( 8078): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 8078): Starting up...
,I/HwSystemManager( 3675): HoldService:uid:1000 pid:7646 died
I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3675): HoldService:oldVersionKey:1000,7646
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
W/MediaProcessHandler( 3044): processOp uid 1000 is not concerned!
,I/HwEmailTag( 7949): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7949): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7949): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3381): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwEmailTag( 7949): EmailProvider->query->1450149733023;end;;consuming:4ms;
,I/Mms_TXM_SVC( 7199): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7199): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3314): is magazine unlock on, now is lock screen diabled mode
,I/HwEmailTag( 7949): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwOUC   ( 7981): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7981): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwEmailTag( 7949): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 7949): CleanRecipient->onCreate
,I/HwEmailTag( 7949): Device->updateDeviceIdIfNeeded->doInBackground
,I/HwEmailTag( 7949): CleanRecipient->onStartCommand->action is null
,I/HwEmailTag( 7949): Device->getDeviceId->
,I/HwEmailTag( 7949): CleanRecipient->onHandleIntent->action is null
,I/HwEmailTag( 7949): Device->getDeviceIdInternal->isUpdate:false
I/art     ( 8006): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8006): ThemeHelperretry to get Settings
,I/HwEmailTag( 7949): Device->getDeviceIdInternal->get id from deviceName, return successfully.
,I/HwEmailTag( 7949): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 7949): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 7949): CleanRecipient->onDestroy
,I/HwEmailTag( 7949): AccountReconciler->reconcileAccountsInternal->consuming:86ms
,E/HwSystemManager( 6762): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwEmailTag( 7949): EmailProvider->query->1450149733119;end;;consuming:1ms;
,I/HwEmailTag( 7949): AccountReconciler->reconcileAccountsInternal->consuming:5ms
,I/HwEmailTag( 7949): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwCust  ( 8154): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 8154): EmailContent->init->consuming:22ms->;-prefixstartupperformance-
,I/HwEmailTag( 8154): Exchange->onCreate
,I/PG Utils( 8154): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8154): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7949): EmailProvider->query->1450149733225;end;;consuming:2ms;
,I/HwEmailTag( 8154): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=43 dispatchEvent: HEART-BEAT-ACK: 5
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,W/ArpVerifier( 3044): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/HwLauncher( 3850): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/System  ( 4076): core_booster, getBoosterConfig = false
I/System  ( 4076): core_booster, getBoosterConfig = false
,I/TimeManager( 3402): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3402): hand message 1
I/TimeManager( 3402): notify time change. size = 2
,I/TimeLayout( 3402): time = 04:22
,I/TimeLayout( 3402): updateDate date = 12/15/2015
,I/TimeLayout( 3402): weekDay = Tuesday
,I/ActivityManager( 3044): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3827): Network connection true
,I/AccountTypeManager( 7199): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2b840f24 in the cache
I/SUPL20_SPIMESLP-SENDING( 3827): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3827): bBrokenPipe = false
,I/HwEmailTag( 7949): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7949): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7949): EmailProvider->notifyNetworkChanged->
,I/NetworkMonitor( 7236): type=WIFI subType= reason=null isConnected=true
,I/SimFactoryManager( 7199): Get SIM state from SIM factory manager: 1,For slotId:0
,E/TEST-APN( 3805): query for APN: check-permission succ 
E/TEST-APN( 3805): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/SimFactoryManager( 7199): Get SIM state from SIM factory manager: 1,For slotId:1
,E/GpsLocationProvider( 3044): No APN found to select.
,I/AccountTypeManager( 7199): Adding account type = com.android.contacts.model.account.ExternalAccountType@1daf9a8d in the cache
,W/GNSS_ADAPTER( 3044): This function not used.
W/GNSS_ADAPTER( 3044): This function not used.
,I/DownloadManager( 3381): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,W/ResourceType( 7199): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7199): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 7199): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7199): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7199): Adding account type = com.android.contacts.model.account.ExternalAccountType@3ae9f442 in the cache
,I/AccountTypeManager( 7199): Adding account type = com.android.contacts.model.account.GoogleAccountType@b154c53 in the cache
,E/ExternalAccountType( 7199): Unsupported attribute readOnly
,I/AccountTypeManager( 7199): AccountManager, account size is: 2
,I/AccountTypeManager( 7199): Loaded meta-data for 5 account types, 3 accounts in 58ms(wall) 20ms(cpu)
,I/Mms_TXM_SVC( 7199): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7199): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3314): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 7981): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7981): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 7981): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 7981): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 7981): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,I/art     ( 8006): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8006): ThemeHelperretry to get Settings
,I/HwOUC   ( 7981): [Thread-129-129]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
E/HwSystemManager( 6762): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwOUC   ( 7981): [Thread-129-129]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,E/WifiStateMachine( 3044):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 3044):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/Process ( 7981): Sending signal. PID: 7981 SIG: 9
,I/HwSystemManager( 3675): HoldService:uid:10052 pid:7981 died
I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3675): HoldService:oldVersionKey:10052,7981
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10052, pid: 7981
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10052, pid: 7981
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gcm.CONNECTED
,I/HwEmailTag( 7949): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 7949): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 7949): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 7949): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 7949): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7949): EmailProvider->triggerPeroidSync->accountId:-1
I/HwEmailTag( 7949): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 7949): EmailProvider->query->1450149738171;end;;consuming:2ms;
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 30104 firstTime = 92809 firstmBatteryCapacity =2203
,W/ArpVerifier( 3044): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/VacuumService( 4076): Vacuum at: now=1450149744697 tag=VacuumService
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 4076): Scheduling Phenotype for one-off execution 7576 seconds from now (1450149745013)
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 4076): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GoogleURLConnFactory( 4076): Using platform SSLCertificateSocketFactory
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 4076): core_booster, getBoosterConfig = false
,I/System  ( 4076): core_booster, getBoosterConfig = false
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2332): [ap] temp_new :30  temp_old :31
,I/art     ( 8006): System.exit called, status: 0
I/AndroidRuntime( 8006): VM exiting with result code 0, cleanup skipped.
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 6
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=44 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10060
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10060, pid: 8006
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10060, pid: 8006
I/HwSystemManager( 3675): HoldService:uid:10060 pid:8006 died
I/HwSystemManager( 3675): HoldService:oldVersionKey:10060,8006
,E/Thermal-daemon( 2332): [charger_ic] temp_new :30  temp_old :31
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=45 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/HwSystemManager( 3675): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3675): LauncherPredicate:get default launcher is null, set hwlauncher
,I/art     ( 3044): Explicit concurrent mark sweep GC freed 57175(3MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/42MB, paused 1.900ms total 181.109ms
,I/HwSystemManager( 3675): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3675): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3675): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3675): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3675): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3675): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3675): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1111846912 [332800000,437657600,542515200]
I/HwSystemManager( 3675): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3675): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,E/WifiStateMachine( 3044):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3044):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3044):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/ActivityManager( 3044): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/bluedroid( 4904): bt interface: [set_adapter_property]
I/bluedroid( 4904): bt interface: [set_adapter_property]
W/bt-btm  ( 4904): BTM_SetDiscoverability
,W/bt-btif ( 4904): BTM_SetConnectability
W/bt-btm  ( 4904): BTM_SetConnectability
I/BluetoothAdapterProperties( 4904): adapterPropertyChangedCallback with type:9 len:4
W/bt-btif ( 4904): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4904): adapterPropertyChangedCallback with type:7 len:4
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 8
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3850): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3402): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3402): hand message 1
I/TimeManager( 3402): notify time change. size = 2
,I/TimeLayout( 3402): time = 04:23
,I/TimeLayout( 3402): updateDate date = 12/15/2015
,I/TimeLayout( 3402): weekDay = Tuesday
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 90264 firstTime = 92809 firstmBatteryCapacity =2203
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 93744 firstTime = 92809 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/Thermal-daemon( 2332): [ap] temp_new :29  temp_old :30
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :29  temp_old :30
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 120359 firstTime = 92809 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 12
E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 150433 firstTime = 92809 firstmBatteryCapacity =2203
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 153740 firstTime = 92809 firstmBatteryCapacity =2203
,I/ClearcutLoggerApiImpl( 4076): disconnect managed GoogleApiClient
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 15
E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 180500 firstTime = 92809 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 16
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3044): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 17
E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/art     ( 3044): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 18
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,I/System  ( 3044): core_booster, getBoosterConfig = false
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/System  ( 3044): core_booster, getBoosterConfig = false
,I/jxcore-log( 7858): Connected to the server!
I/jxcore-log( 7858): 
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 19
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=58 dispatchEvent: HEART-BEAT-ACK: 19
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 7858): --- start :testFindPeers.js---
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testFindPeers created [object Object]
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): serverPort is 8876
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT6525
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7858): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7858): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/art     ( 3044): Can not find class: Lcom/android/server/wifi/p2p/WifiP2pServiceImpl$ClientInfo;
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7858): start: OK
,I/jxcore-log( 7858): StartBroadcasting started ok
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 20
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=59 dispatchEvent: HEART-BEAT-ACK: 20
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/art     ( 3044): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 21
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 21
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/art     ( 3044): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 22
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 22
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 7858): --- start :testFindPeers.js---
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testFindPeers created [object Object]
I/jxcore-log( 7858): 
I/jxcore-log( 7858): serverPort is 8876
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): weAreDoneNow
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): done, now sending data to server
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): done, now sending data to server
I/jxcore-log( 7858): 
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7858): teardown
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testFindPeers stopped
I/jxcore-log( 7858): 
,I/io.jxcore.node.ConnectionHelper( 7858): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:492)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: NOT_INITIALIZED
I/jxcore-log( 7858): StopBroadcasting went ok
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onConnectionFailed: Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7858): --- start :testSendData.js---
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":22}bt-address length : 0
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): daya100000
I/jxcore-log( 7858): 
I/jxcore-log( 7858): check server
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): serverPort is 51857
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT6525
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7858): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7858): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7858): start: OK
I/jxcore-log( 7858): StartBroadcasting started ok
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): null
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): 2015-12-15T03:26:41.811Z SendDataTCPServer.js: TCP/IP server is bound to port: 51857
,I/jxcore-log( 7858): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 23
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=62 dispatchEvent: HEART-BEAT-ACK: 23
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2752): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2752): [rename_old_file:107]rename_old_file
I/OAM     ( 2752): 
,I/jxcore-log( 7858): teardown
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testSendData stopped
I/jxcore-log( 7858): 
,I/io.jxcore.node.ConnectionHelper( 7858): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:492)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: NOT_INITIALIZED
,I/jxcore-log( 7858): StopBroadcasting went ok
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): 2015-12-15T03:26:58.049Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): 2015-12-15T03:26:58.051Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7858): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: NOT_INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7858): --- start :testSendData.js---
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): daya100000
I/jxcore-log( 7858): 
I/jxcore-log( 7858): check server
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): serverPort is 56973
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT6525
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7858): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7858): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7858): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7858): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7858): start: OK
,I/jxcore-log( 7858): StartBroadcasting started ok
I/jxcore-log( 7858): 
I/jxcore-log( 7858): null
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): 2015-12-15T03:26:58.369Z SendDataTCPServer.js: TCP/IP server is bound to port: 56973
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 7858): onConnectionManagerStateChanged: RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 7858): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63),
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 24
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=63 dispatchEvent: HEART-BEAT-ACK: 24
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0,
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 25
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=64 dispatchEvent: HEART-BEAT-ACK: 25
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 26
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=65 dispatchEvent: HEART-BEAT-ACK: 26
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 27
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=66 dispatchEvent: HEART-BEAT-ACK: 27
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 28
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=67 dispatchEvent: HEART-BEAT-ACK: 28
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 29
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 29
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 30
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=69 dispatchEvent: HEART-BEAT-ACK: 30
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 31
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=70 dispatchEvent: HEART-BEAT-ACK: 31
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 32
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=71 dispatchEvent: HEART-BEAT-ACK: 32
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 33
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=72 dispatchEvent: HEART-BEAT-ACK: 33
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 34
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=73 dispatchEvent: HEART-BEAT-ACK: 34
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 35
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=74 dispatchEvent: HEART-BEAT-ACK: 35
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 36
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=75 dispatchEvent: HEART-BEAT-ACK: 36
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 37
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=76 dispatchEvent: HEART-BEAT-ACK: 37
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2752): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2752): [rename_old_file:107]rename_old_file
I/OAM     ( 2752): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 38
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=77 dispatchEvent: HEART-BEAT-ACK: 38
,E/WifiStateMachine( 3044):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3044):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4904): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/wpa_supplicant( 3468): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
E/WifiMonitor( 3044): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
,W/System.err( 3044): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3044): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3044): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3044): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3044): This is not beta user build
,W/wpa_supplicant( 3468): check_associate_result func start
,W/wpa_supplicant( 3468): STA MODE: Set shutdown wlan cmd SUCCESS
,E/WifiMonitor( 3044): WifiMonitor notify network disconnect: null reason=0
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=79 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3044):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-58 rt=619255
,E/WifiStateMachine( 3044):  ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=619256  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 3044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=619257  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 3044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=619257  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3044): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3044): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 3044): do suspend true
,I/wpa_supplicant( 3468): set current WIFI status to BT!
,I/bluetooth-coex( 4904): btcoex_socket_server: accept socket success
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE,
,E/ArpVerifier( 3044): current SSID is empty.
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiConfigStore( 3044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/WifiStateMachine( 3044): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3044): setScanAlarm false period 0 initial delay 0
E/WifiStateMachine( 3044):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3044): setScanAlarm true period 0 initial delay 200
,I/ActivityManager( 3044): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3044): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,I/WifiTracker( 3402): STATE =1
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/NetworkSpeedManagerEx( 3402): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3402): wifiManager = android.net.wifi.WifiManager@1416b650
,I/NetworkSpeedManagerEx( 3402): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3402): stop
,I/WifiTracker( 3402): STATE =1
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3402): STATE =1
,W/ArpVerifier( 3044): ignore msg MSG_CHECK_WIFI_STATE, msg token = 11, expected token = 13
,I/ActivityManager( 3044): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3827): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3827): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3827): bBrokenPipe = false
,I/HwEmailTag( 7949): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7949): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7949): EmailProvider->notifyNetworkChanged->
,I/ActivityManager( 3044): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3827): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3827): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3827): bBrokenPipe = false
,E/TEST-APN( 3805): query for APN: check-permission succ 
,E/TEST-APN( 3805): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,W/View    ( 3402): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{511f0b1 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
I/DownloadManager( 3381): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 7199): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7199): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3314): is magazine unlock on, now is lock screen diabled mode
,I/art     ( 3805): Explicit concurrent mark sweep GC freed 36103(1939KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.125ms total 59.230ms
,E/GpsLocationProvider( 3044): No APN found to select.
,W/GNSS_ADAPTER( 3044): This function not used.
W/GNSS_ADAPTER( 3044): This function not used.
,E/TEST-APN( 3805): query for APN: check-permission succ 
E/TEST-APN( 3805): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3044): No APN found to select.
,W/GNSS_ADAPTER( 3044): This function not used.
,W/GNSS_ADAPTER( 3044): This function not used.
,E/HwOUC   ( 8672): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8672): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8672): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 8672): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8672): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8672): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8672): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8672): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 217us total 23.423ms
,W/asset   ( 8695): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 204us total 25.660ms
,I/HwCust  ( 8695): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 193us total 22.865ms
,I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10044
I/HwSystemManager( 3675): HoldService:uid:10044 pid:7686 died
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/HwSystemManager( 3675): HoldService:oldVersionKey:10044,7686
E/HwSystemManager( 6762): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10044, pid: 7686
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10044, pid: 7686
,I/Babel   ( 7372): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 6038): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6038): num queued entries: 0
,I/iu.UploadsManager( 6038): num updated entries: 0
,I/iu.SyncManager( 6038): NEXT; no task
,I/HwEmailTag( 7949): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7949): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7949): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3381): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 7199): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7199): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3314): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8672): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8672): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6762): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwLauncher( 3850): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/System  ( 4076): core_booster, getBoosterConfig = false
I/System  ( 4076): core_booster, getBoosterConfig = false
,I/TimeManager( 3402): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3402): hand message 1
I/TimeManager( 3402): notify time change. size = 2
I/TimeLayout( 3402): time = 04:30
,I/TimeLayout( 3402): updateDate date = 12/15/2015
,I/TimeLayout( 3402): weekDay = Tuesday
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=80 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 3044): handleEvent 13  CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
,I/HwEmailTag( 7949): EmailProvider->handleNetworkChanged->network is bad, WON'T start new EmailConnectivityTask
I/HwEmailTag( 7949): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7949): EmailProvider->triggerPeroidSync->accountId:-1
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 39
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=81 dispatchEvent: HEART-BEAT-ACK: 39
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,W/ArpVerifier( 3044): ignore msg MSG_CHECK_WIFI_STATE, msg token = 10, expected token = 13
,I/art     ( 8695): System.exit called, status: 0
I/AndroidRuntime( 8695): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3675): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3675): HoldService:uid:10060 pid:8695 died
I/HwSystemManager( 3675): HoldService:oldVersionKey:10060,8695
E/HsmCoreServiceImpl( 3044): onTransact in code is: 102
I/MediaProcessHandler( 3044): processOp opType: 1, uid: 10060, pid: 8695
W/MediaProcessHandler( 3044): remove target not exist, maybe the UI process: uid: 10060, pid: 8695
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 40
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=82 dispatchEvent: HEART-BEAT-ACK: 40
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 41
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=83 dispatchEvent: HEART-BEAT-ACK: 41
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 42
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=84 dispatchEvent: HEART-BEAT-ACK: 42
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 43
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=85 dispatchEvent: HEART-BEAT-ACK: 43
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 44
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=86 dispatchEvent: HEART-BEAT-ACK: 44
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 45
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=87 dispatchEvent: HEART-BEAT-ACK: 45
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 46
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=88 dispatchEvent: HEART-BEAT-ACK: 46
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 47
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=89 dispatchEvent: HEART-BEAT-ACK: 47
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 48
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=90 dispatchEvent: HEART-BEAT-ACK: 48
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 49
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=91 dispatchEvent: HEART-BEAT-ACK: 49
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 50
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=92 dispatchEvent: HEART-BEAT-ACK: 50
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/HwLauncher( 3850): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3402): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3402): hand message 1
I/TimeManager( 3402): notify time change. size = 2
I/TimeLayout( 3402): time = 04:33
,I/TimeLayout( 3402): updateDate date = 12/15/2015
I/TimeLayout( 3402): weekDay = Tuesday
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 51
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=93 dispatchEvent: HEART-BEAT-ACK: 51
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 52
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=94 dispatchEvent: HEART-BEAT-ACK: 52
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 53
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=95 dispatchEvent: HEART-BEAT-ACK: 53
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 54
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=96 dispatchEvent: HEART-BEAT-ACK: 54
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 55
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=97 dispatchEvent: HEART-BEAT-ACK: 55
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 56
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=98 dispatchEvent: HEART-BEAT-ACK: 56
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 57
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=99 dispatchEvent: HEART-BEAT-ACK: 57
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/AGNSSCONTROL( 2756): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2756): void kill_timer(timer_t) -- 102: Timer: kill a timer 2874539904
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2874569192
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2756): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2756): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
,E/Lss-gw  ( 2756): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1450150524214, wifi_time:1450149689103
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:1
W/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2756): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,E/Lss     ( 8968): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8968): No reference location.
,W/Lss     ( 8968): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3202 bytes of data
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:851, gpsTime.gpsTOW23b:2321750, nTOWassist:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:92, iode3:92, m0:-858380415.000000, delta_n:13210.000000, ecc:129694829.000000, ek:0.000000, sqrt_a:2702016669.000000, omega_0:465527384.000000, i0:644017446.000000, omega:-1505810128.000000, omega_dot:-22436.000000, i_dot:382.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1792.000000, cus:6003.000000, crc:4894.000000, crs:-2107.000000, cic:224.000000, cis:108.000000, group_delay:-44.000000, af0:1283943.000000, af1:6.000000, af2:0.000000, aodc:92, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:32, iode3:32, m0:82960744.000000, delta_n:11913.000000, ecc:1979120.000000, ek:0.000000, sqrt_a:2701971946.000000, omega_0:488426546.000000, i0:658459553.000000, omega:-2057779647.000000, omega_dot:-21922.000000, i_dot:560.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1872.000000, cus:6482.000000, crc:4759.000000, crs:-2158.000000, cic:17.000000, cis:14.000000, group_delay:9.000000, af0:241262.000000, af1:57.000000, af2:0.000000, aodc:32, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:37, iode3:37, m0:1165681406.000000, delta_n:12817.000000, ecc:13987882.000000, ek:0.000000, sqrt_a:2701981408.000000, omega_0:-229320841.000000, i0:657432125.000000, omega:-1088070362.000000, omega_dot:-23080.000000, i_dot:-912.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3161.000000, cus:2504.000000, crc:9223.000000, crs:-3524.000000, cic:2.000000, cis:-20.000000, group_delay:10.000000, af0:-34885.000000, af1:-13.000000, af2:0.000000, aodc:37, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:0, iode2:85, iode3:85, m0:1659141472.000000, delta_n:13415.000000, ecc:7819668.000000, ek:0.000000, sqrt_a:2702013510.000000, omega_0:1203086152.000000, i0:655552042.000000, omega:-2021144880.000000, omega_dot:-22794.000000, i_dot:1112.000000
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:818.000000, cus:3602.000000, crc:7925.000000, crs:893.000000, cic:-43.000000, cis:-2.000000, group_delay:7.000000, af0:91450.000000, af1:48.000000, af2:0.000000, aodc:85, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:108, iode3:108, m0:-1970235368.000000, delta_n:11458.000000, ecc:48218081.000000, ek:0.000000, sqrt_a:2701950219.000000, omega_0:-907619012.000000, i0:676736837.000000, omega:436866910.000000, omega_dot:-22535.000000, i_dot:631.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1826.000000, cus:1805.000000, crc:10465.000000, crs:2140.000000, cic:-34.000000, cis:-106.000000, group_delay:-27.000000, af0:758880.000000, af1:26.000000, af2:0.000000, aodc:108, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:42, iode3:42, m0:208775040.000000, delta_n:12985.000000, ecc:71487750.000000, ek:0.000000, sqrt_a:2702020039.000000, omega_0:1973820485.000000, i0:659860805.000000, omega:-1330865037.000000, omega_dot:-22895.000000, i_dot:-1281.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-518.000000, cus:4216.000000, crc:7424.000000, crs:-509.000000, cic:-65.000000, cis:16.000000, group_delay:-20.000000, af0:33095.000000, af1:-21.000000, af2:0.000000, aodc:42, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:30, iode3:30, m0:920204799.000000, delta_n:11584.000000, ecc:71064007.000000, ek:0.000000, sqrt_a:2702009643.000000, omega_0:-894802844.000000, i0:677097847.000000, omega:214455907.000000, omega_dot:-22925.000000, i_dot:153.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1706.000000, cus:1582.000000, crc:10805.000000, crs:1797.000000, cic:18.000000, cis:78.000000, group_delay:-22.000000, af0:-123029.000000, af1:30.000000, af2:0.000000, aodc:30, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:64, iode3:64, m0:1307476604.000000, delta_n:15404.000000, ecc:141019747.000000, ek:0.000000, sqrt_a:2701993508.000000, omega_0:1187303138.000000, i0:631952931.000000, omega:-1315981548.000000, omega_dot:-23535.000000, i_dot:1248.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:669.000000, cus:3675.000000, crc:7254.000000, crs:879.000000, cic:-46.000000, cis:-252.000000, group_delay:-24.000000, af0:993870.000000, af1:33.000000, af2:0.000000, aodc:64, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:63, iode3:63, m0:-245966629.000000, delta_n:15355.000000, ecc:43147604.000000, ek:0.000000, sqrt_a:2702005588.000000, omega_0:1151709186.000000, i0:632793334.000000, omega:885905768.000000, omega_dot:-23866.000000, i_dot:1304.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:799.000000, cus:3907.000000, crc:7076.000000, crs:829.000000, cic:-19.000000, cis:27.000000, group_delay:-18.000000, af0:812662.000000, af1:24.000000, af2:0.000000, aodc:63, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:1, iode2:182, iode3:182, m0:931001387.000000, delta_n:15909.000000, ecc:64264997.000000, ek:0.000000, sqrt_a:2702762040.000000, omega_0:1187857718.000000, i0:630476152.000000, omega:-1387138083.000000, omega_dot:-24268.000000, i_dot:995.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:805.000000, cus:3600.000000, crc:7380.000000, crs:923.000000, cic:-116.000000, cis:-9.000000, group_delay:-38.000000, af0:901463.000000, af1:33.000000, af2:0.000000, aodc:182, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:58, iode3:58, m0:-1020317371.000000, delta_n:12620.000000, ecc:33638914.000000, ek:0.000000, sqrt_a:2701996182.000000, omega_0:-1671418392.000000, i0:650454277.000000, omega:209905205.000000, omega_dot:-22273.000000, i_dot:-264.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1775.000000, cus:5919.000000, crc:5182.000000, crs:2104.000000, cic:-15.000000, cis:-57.000000, group_delay:6.000000, af0:-20045.000000, af1:-5.000000, af2:0.000000, aodc:58, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:17, iode3:17, m0:1671827435.000000, delta_n:13371.000000, ecc:4580936.000000, ek:0.000000, sqrt_a:2702014002.000000, omega_0:-945283782.000000, i0:656506089.000000, omega:-207849636.000000, omega_dot:-23633.000000, i_dot:610.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1835.000000, cus:1587.000000, crc:10308.000000, crs:2019.000000, cic:-5.000000, cis:58.000000, group_delay:16.000000, af0:-356145.000000, af1:-154.000000, af2:0.000000, aodc:17, health:0, toc:11699, toe:11699, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:83, iode3:83, m0:767810866.000000, delta_n:12036.000000, ecc:172031175.000000, ek:0.000000, sqrt_a:2702022453.000000, omega_0:-891289139.000000, i0:676185583.000000, omega:-1120765736.000000, omega_dot:-23603.000000, i_dot:539.000000
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1494.000000, cus:1870.000000, crc:10648.000000, crs:1914.000000, cic:-170.000000, cis:-159.000000, group_delay:-24.000000, af0:1048727.000000, af1:23.000000, af2:0.000000, aodc:83, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:25, iode3:25, m0:-1724644868.000000, delta_n:12444.000000, ecc:14106991.000000, ek:0.000000, sqrt_a:2702007395.000000, omega_0:-1609347626.000000, i0:652229844.000000, omega:2140261343.000000, omega_dot:-22272.000000, i_dot:-134.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2684.000000, cus:5726.000000, crc:5566.000000, crs:3108.000000, cic:-6.000000, cis:-16.000000, group_delay:7.000000, af0:152674.000000, af1:46.000000, af2:0.000000, aodc:25, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:47, iode3:47, m0:-1418453021.000000, delta_n:14343.000000, ecc:97569405.000000, ek:0.000000, sqrt_a:2701989966.000000, omega_0:1260145582.000000, i0:646889076.000000, omega:133303333.000000, omega_dot:-23154.000000, i_dot:1218.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:755.000000, cus:3307.000000, crc:8124.000000, crs:896.000000, cic:-13.000000, cis:-78.000000, group_delay:-7.000000, af0:103678.000000, af1:106.000000, af2:0.000000, aodc:47, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 83
,W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
,I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 58
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=100 dispatchEvent: HEART-BEAT-ACK: 58
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 59
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=101 dispatchEvent: HEART-BEAT-ACK: 59
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 60
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=102 dispatchEvent: HEART-BEAT-ACK: 60
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 61
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=103 dispatchEvent: HEART-BEAT-ACK: 61
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 62
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=104 dispatchEvent: HEART-BEAT-ACK: 62
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 63
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=105 dispatchEvent: HEART-BEAT-ACK: 63
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 64
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=106 dispatchEvent: HEART-BEAT-ACK: 64
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 65
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=107 dispatchEvent: HEART-BEAT-ACK: 65
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 66
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=108 dispatchEvent: HEART-BEAT-ACK: 66
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 67
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=109 dispatchEvent: HEART-BEAT-ACK: 67
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 68
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=110 dispatchEvent: HEART-BEAT-ACK: 68
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 69
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=111 dispatchEvent: HEART-BEAT-ACK: 69
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 992658 firstTime = 92809 firstmBatteryCapacity =2203
,E/HwSystemManager( 3675): BgPowerManagerService: conusmPower = -2 result = -7 flag1 =false flag2 = false
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 0 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 70
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=112 dispatchEvent: HEART-BEAT-ACK: 70
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 71
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=113 dispatchEvent: HEART-BEAT-ACK: 71
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 28981 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 72
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=114 dispatchEvent: HEART-BEAT-ACK: 72
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 73
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=115 dispatchEvent: HEART-BEAT-ACK: 73
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 74
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=116 dispatchEvent: HEART-BEAT-ACK: 74
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,E/HI110X_CHR_LOGD( 2753): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 75
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=117 dispatchEvent: HEART-BEAT-ACK: 75
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 89164 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 76
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=118 dispatchEvent: HEART-BEAT-ACK: 76
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 77
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=119 dispatchEvent: HEART-BEAT-ACK: 77
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 119239 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 78
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=120 dispatchEvent: HEART-BEAT-ACK: 78
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 79
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=121 dispatchEvent: HEART-BEAT-ACK: 79
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 149324 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 80
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=122 dispatchEvent: HEART-BEAT-ACK: 80
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 81
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=123 dispatchEvent: HEART-BEAT-ACK: 81
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 179399 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 82
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=124 dispatchEvent: HEART-BEAT-ACK: 82
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 83
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=125 dispatchEvent: HEART-BEAT-ACK: 83
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 84
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=126 dispatchEvent: HEART-BEAT-ACK: 84
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 85
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=127 dispatchEvent: HEART-BEAT-ACK: 85
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 240000 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 86
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=128 dispatchEvent: HEART-BEAT-ACK: 86
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 7858): timeout now
I/jxcore-log( 7858): 
I/jxcore-log( 7858): weAreDoneNow
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): done, now sending data to server
I/jxcore-log( 7858): 
I/jxcore-log( 7858): done, now sending data to server
I/jxcore-log( 7858): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 87
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=129 dispatchEvent: HEART-BEAT-ACK: 87
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 269644 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 88
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=130 dispatchEvent: HEART-BEAT-ACK: 88
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 89
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=131 dispatchEvent: HEART-BEAT-ACK: 89
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 299716 firstTime = 1086549 firstmBatteryCapacity =2205
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 90
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=132 dispatchEvent: HEART-BEAT-ACK: 90
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/jxcore-log( 7858): timeout now
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): weAreDoneNow, resultArray.length: 0
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): sendReportNow
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): done, now sending data to server
I/jxcore-log( 7858): 
,I/jxcore-log( 7858): 2015-12-15T03:43:38.375Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7858): 
,E/Thermal-daemon( 2332): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2332): [charger_ic] temp_new :28  temp_old :29
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 91
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=133 dispatchEvent: HEART-BEAT-ACK: 91
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 92
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=134 dispatchEvent: HEART-BEAT-ACK: 92
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 93
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=135 dispatchEvent: HEART-BEAT-ACK: 93
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 359888 firstTime = 1086549 firstmBatteryCapacity =2205
E/HwSystemManager( 3675): BgPowerManagerService: conusmPower = -1 result = -10 flag1 =false flag2 = false
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 0 firstTime = 1446550 firstmBatteryCapacity =2206
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 94
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=136 dispatchEvent: HEART-BEAT-ACK: 94
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 95
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=137 dispatchEvent: HEART-BEAT-ACK: 95
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 96
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=138 dispatchEvent: HEART-BEAT-ACK: 96
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 97
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=139 dispatchEvent: HEART-BEAT-ACK: 97
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3675): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3675): BgPowerManagerService: mTimes = 60002 firstTime = 1446550 firstmBatteryCapacity =2206
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 98
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=140 dispatchEvent: HEART-BEAT-ACK: 98
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 99
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=141 dispatchEvent: HEART-BEAT-ACK: 99
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 100
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=142 dispatchEvent: HEART-BEAT-ACK: 100
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 101
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=143 dispatchEvent: HEART-BEAT-ACK: 101
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 102
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=144 dispatchEvent: HEART-BEAT-ACK: 102
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 103
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=145 dispatchEvent: HEART-BEAT-ACK: 103
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 104
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=146 dispatchEvent: HEART-BEAT-ACK: 104
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 105
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=147 dispatchEvent: HEART-BEAT-ACK: 105
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 106
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=148 dispatchEvent: HEART-BEAT-ACK: 106
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 107
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=149 dispatchEvent: HEART-BEAT-ACK: 107
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 108
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=150 dispatchEvent: HEART-BEAT-ACK: 108
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 109
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=151 dispatchEvent: HEART-BEAT-ACK: 109
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 110
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=152 dispatchEvent: HEART-BEAT-ACK: 110
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 111
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=153 dispatchEvent: HEART-BEAT-ACK: 111
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 112
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=154 dispatchEvent: HEART-BEAT-ACK: 112
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 113
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=155 dispatchEvent: HEART-BEAT-ACK: 113
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 114
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=156 dispatchEvent: HEART-BEAT-ACK: 114
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 115
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=157 dispatchEvent: HEART-BEAT-ACK: 115
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 116
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=158 dispatchEvent: HEART-BEAT-ACK: 116
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :29  temp_old :28
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 117
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=159 dispatchEvent: HEART-BEAT-ACK: 117
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/AGNSSCONTROL( 2756): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2756): void kill_timer(timer_t) -- 102: Timer: kill a timer 2874569192
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2874580088
I/AGNSSCONTROL( 2756): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2756): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2756): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2756): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1450151424215, wifi_time:1450149689103
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:1
W/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2756): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,E/Lss     ( 9744): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 9744): No reference location.
W/Lss     ( 9744): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3202 bytes of data
I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:851, gpsTime.gpsTOW23b:2333000, nTOWassist:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:92, iode3:92, m0:-858380415.000000, delta_n:13210.000000, ecc:129694829.000000, ek:0.000000, sqrt_a:2702016669.000000, omega_0:465527384.000000, i0:644017446.000000, omega:-1505810128.000000, omega_dot:-22436.000000, i_dot:382.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1792.000000, cus:6003.000000, crc:4894.000000, crs:-2107.000000, cic:224.000000, cis:108.000000, group_delay:-44.000000, af0:1283943.000000, af1:6.000000, af2:0.000000, aodc:92, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:32, iode3:32, m0:82960744.000000, delta_n:11913.000000, ecc:1979120.000000, ek:0.000000, sqrt_a:2701971946.000000, omega_0:488426546.000000, i0:658459553.000000, omega:-2057779647.000000, omega_dot:-21922.000000, i_dot:560.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1872.000000, cus:6482.000000, crc:4759.000000, crs:-2158.000000, cic:17.000000, cis:14.000000, group_delay:9.000000, af0:241262.000000, af1:57.000000, af2:0.000000, aodc:32, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:37, iode3:37, m0:1165681406.000000, delta_n:12817.000000, ecc:13987882.000000, ek:0.000000, sqrt_a:2701981408.000000, omega_0:-229320841.000000, i0:657432125.000000, omega:-1088070362.000000, omega_dot:-23080.000000, i_dot:-912.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3161.000000, cus:2504.000000, crc:9223.000000, crs:-3524.000000, cic:2.000000, cis:-20.000000, group_delay:10.000000, af0:-34885.000000, af1:-13.000000, af2:0.000000, aodc:37, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:0, iode2:85, iode3:85, m0:1659141472.000000, delta_n:13415.000000, ecc:7819668.000000, ek:0.000000, sqrt_a:2702013510.000000, omega_0:1203086152.000000, i0:655552042.000000, omega:-2021144880.000000, omega_dot:-22794.000000, i_dot:1112.000000
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:818.000000, cus:3602.000000, crc:7925.000000, crs:893.000000, cic:-43.000000, cis:-2.000000, group_delay:7.000000, af0:91450.000000, af1:48.000000, af2:0.000000, aodc:85, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:108, iode3:108, m0:-1970235368.000000, delta_n:11458.000000, ecc:48218081.000000, ek:0.000000, sqrt_a:2701950219.000000, omega_0:-907619012.000000, i0:676736837.000000, omega:436866910.000000, omega_dot:-22535.000000, i_dot:631.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1826.000000, cus:1805.000000, crc:10465.000000, crs:2140.000000, cic:-34.000000, cis:-106.000000, group_delay:-27.000000, af0:758880.000000, af1:26.000000, af2:0.000000, aodc:108, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:42, iode3:42, m0:208775040.000000, delta_n:12985.000000, ecc:71487750.000000, ek:0.000000, sqrt_a:2702020039.000000, omega_0:1973820485.000000, i0:659860805.000000, omega:-1330865037.000000, omega_dot:-22895.000000, i_dot:-1281.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-518.000000, cus:4216.000000, crc:7424.000000, crs:-509.000000, cic:-65.000000, cis:16.000000, group_delay:-20.000000, af0:33095.000000, af1:-21.000000, af2:0.000000, aodc:42, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:30, iode3:30, m0:920204799.000000, delta_n:11584.000000, ecc:71064007.000000, ek:0.000000, sqrt_a:2702009643.000000, omega_0:-894802844.000000, i0:677097847.000000, omega:214455907.000000, omega_dot:-22925.000000, i_dot:153.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1706.000000, cus:1582.000000, crc:10805.000000, crs:1797.000000, cic:18.000000, cis:78.000000, group_delay:-22.000000, af0:-123029.000000, af1:30.000000, af2:0.000000, aodc:30, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:64, iode3:64, m0:1307476604.000000, delta_n:15404.000000, ecc:141019747.000000, ek:0.000000, sqrt_a:2701993508.000000, omega_0:1187303138.000000, i0:631952931.000000, omega:-1315981548.000000, omega_dot:-23535.000000, i_dot:1248.000000
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:669.000000, cus:3675.000000, crc:7254.000000, crs:879.000000, cic:-46.000000, cis:-252.000000, group_delay:-24.000000, af0:993870.000000, af1:33.000000, af2:0.000000, aodc:64, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:63, iode3:63, m0:-245966629.000000, delta_n:15355.000000, ecc:43147604.000000, ek:0.000000, sqrt_a:2702005588.000000, omega_0:1151709186.000000, i0:632793334.000000, omega:885905768.000000, omega_dot:-23866.000000, i_dot:1304.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:799.000000, cus:3907.000000, crc:7076.000000, crs:829.000000, cic:-19.000000, cis:27.000000, group_delay:-18.000000, af0:812662.000000, af1:24.000000, af2:0.000000, aodc:63, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:1, iode2:182, iode3:182, m0:931001387.000000, delta_n:15909.000000, ecc:64264997.000000, ek:0.000000, sqrt_a:2702762040.000000, omega_0:1187857718.000000, i0:630476152.000000, omega:-1387138083.000000, omega_dot:-24268.000000, i_dot:995.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:805.000000, cus:3600.000000, crc:7380.000000, crs:923.000000, cic:-116.000000, cis:-9.000000, group_delay:-38.000000, af0:901463.000000, af1:33.000000, af2:0.000000, aodc:182, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:58, iode3:58, m0:-1020317371.000000, delta_n:12620.000000, ecc:33638914.000000, ek:0.000000, sqrt_a:2701996182.000000, omega_0:-1671418392.000000, i0:650454277.000000, omega:209905205.000000, omega_dot:-22273.000000, i_dot:-264.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1775.000000, cus:5919.000000, crc:5182.000000, crs:2104.000000, cic:-15.000000, cis:-57.000000, group_delay:6.000000, af0:-20045.000000, af1:-5.000000, af2:0.000000, aodc:58, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:17, iode3:17, m0:1671827435.000000, delta_n:13371.000000, ecc:4580936.000000, ek:0.000000, sqrt_a:2702014002.000000, omega_0:-945283782.000000, i0:656506089.000000, omega:-207849636.000000, omega_dot:-23633.000000, i_dot:610.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1835.000000, cus:1587.000000, crc:10308.000000, crs:2019.000000, cic:-5.000000, cis:58.000000, group_delay:16.000000, af0:-356145.000000, af1:-154.000000, af2:0.000000, aodc:17, health:0, toc:11699, toe:11699, status:0, code_on_L2:1, fit_interval_flag:0, aodo:12
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:83, iode3:83, m0:767810866.000000, delta_n:12036.000000, ecc:172031175.000000, ek:0.000000, sqrt_a:2702022453.000000, omega_0:-891289139.000000, i0:676185583.000000, omega:-1120765736.000000, omega_dot:-23603.000000, i_dot:539.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1494.000000, cus:1870.000000, crc:10648.000000, crs:1914.000000, cic:-170.000000, cis:-159.000000, group_delay:-24.000000, af0:1048727.000000, af1:23.000000, af2:0.000000, aodc:83, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:25, iode3:25, m0:-1724644868.000000, delta_n:12444.000000, ecc:14106991.000000, ek:0.000000, sqrt_a:2702007395.000000, omega_0:-1609347626.000000, i0:652229844.000000, omega:2140261343.000000, omega_dot:-22272.000000, i_dot:-134.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2684.000000, cus:5726.000000, crc:5566.000000, crs:3108.000000, cic:-6.000000, cis:-16.000000, group_delay:7.000000, af0:152674.000000, af1:46.000000, af2:0.000000, aodc:25, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:47, iode3:47, m0:-1418453021.000000, delta_n:14343.000000, ecc:97569405.000000, ek:0.000000, sqrt_a:2701989966.000000, omega_0:1260145582.000000, i0:646889076.000000, omega:133303333.000000, omega_dot:-23154.000000, i_dot:1218.000000
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:755.000000, cus:3307.000000, crc:8124.000000, crs:896.000000, cic:-13.000000, cis:-78.000000, group_delay:-7.000000, af0:103678.000000, af1:106.000000, af2:0.000000, aodc:47, health:0, toc:11700, toe:11700, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 83
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2756): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:27, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
,W/AGNSSCONTROL( 2756): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2756): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2756): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 118
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=160 dispatchEvent: HEART-BEAT-ACK: 118
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :28  temp_old :29
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/art     ( 3044): Can not find class: Lcom/android/server/AppOpsService$1$1;
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 119
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=161 dispatchEvent: HEART-BEAT-ACK: 119
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 120
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=162 dispatchEvent: HEART-BEAT-ACK: 120
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/ActivityManager( 3044): filter receiver for action = com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS
,I/art     ( 3044): Can not find class: Lcom/android/server/am/ActivityManagerService$24;
,I/art     ( 3044): Can not find class: Lcom/android/server/am/ProcessStatsService$2;
,I/HwLauncher( 3850): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3402): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3402): hand message 1
I/TimeManager( 3402): notify time change. size = 2
I/TimeLayout( 3402): time = 04:51
,I/HwSystemManager( 3675): aor:Network Stats Updated
I/HwSystemManager( 3675): aoi:onNetworkStatsUpdated
I/TimeLayout( 3402): updateDate date = 12/15/2015
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/TimeLayout( 3402): weekDay = Tuesday
,I/art     ( 3044): Can not find class: Lcom/android/server/pm/PackageManagerService$PackageUsage$1;
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3675): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 3675): getSimCardType:/getSimCardInfo: imsi is null,
E/HwSystemManager( 3675): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3675): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3675): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/EventLogService( 6038): Aggregate from 1450149359757 (log), 1450149359757 (data)
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4076): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Auth    ( 4076): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,I/PG Utils( 6038): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 4076): Explicit concurrent mark sweep GC freed 71333(4MB) AllocSpace objects, 19(400KB) LOS objects, 39% free, 21MB/36MB, paused 1.126ms total 118.400ms
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 121
E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=163 dispatchEvent: HEART-BEAT-ACK: 121
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :29  temp_old :28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 122
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=164 dispatchEvent: HEART-BEAT-ACK: 122
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2332): [charger_ic] temp_new :28  temp_old :29
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 123
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=165 dispatchEvent: HEART-BEAT-ACK: 123
,E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7858): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT6525","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7858): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 7858): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7858): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7858): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3468): wlan0: HEART-BEAT-ACK: 124
,E/WifiMonitor( 3044): WifiMonitor:wlan0 cnt=166 dispatchEvent: HEART-BEAT-ACK: 124
E/WifiStateMachine( 3044):  DisconnectedState what:147506 0 0
,E/WifiStateMachine( 3044):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3044):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3044):  SupplicantStartedState what:147506 0 0
,TIME-OUT KILL (timeout was 1800000ms)
```
