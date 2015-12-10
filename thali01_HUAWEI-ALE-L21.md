#### Test 50650278d6c551a_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 8123): CLASSPATH=/system/framework/am.jar
I/appproc ( 8123): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 8123): app_process:number,5,0
I/AndroidRuntime( 8123): readDownloadBoosterConfig: 'false'
I/        ( 8123): power log dlsym ok
E/android_hardware_fm.cpp( 8123): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 8123): ========64bit long size = 8
E/FM_HAL  ( 8123): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 8123): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 8123): 
I/fm_hisi ( 8123): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 8123): 
I/fm_hisi ( 8123): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 8123): 
E/android_hardware_fm.cpp( 8123): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2925): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2925): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2925): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2925): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3465): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3465): AppLockService:applock password not initial or function is closed
I/HwLauncher( 4742): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 4742): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 4742): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3465): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 4742): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 4742): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 8142): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 8142): Loading: webviewchromium
I/LibraryLoader( 8142): Time to load native libraries: 59 ms (timestamps 4187-4246)
I/LibraryLoader( 8142): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 8142): Expected native library version number "",actual native library version number ""
I/chromium( 8142): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8142): Initializing chromium process, renderers=0
W/art     ( 8142): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8142): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8142): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 8142): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 8142): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 8142): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 8142): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 8142): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 8142): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 8142): Can not find class: Landroid/widget/ViewStub;
I/art     ( 8142): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 8142): Can not find class: Landroid/app/ViewStub;
W/art     ( 8142): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 8142): Attempt to remove local handle scope entry from IRT, ignoring
I/PhoneStatusBar( 3138): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3138): shouldTranslucent:true
I/PhoneStatusBar( 3138): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 8142): Initialized EGL, version 1.4
,I/ActivityManager( 2925): Displayed com.test.thalitest/.MainActivity: +1s124ms (total +1s194ms)
,W/IInputConnectionWrapper( 8142): showStatusIcon on inactive InputConnection
,I/chromium( 8142): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 8142): 
,W/jxcore-log( 8142): Initializing JXcore engine
W/jxcore-log( 8142): JXcore engine is ready
,W/jxcore-log( 8142): Starting JXcore engine
,I/art     ( 5842): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,W/jxcore-log( 8142): Platform android
W/jxcore-log( 8142): 
W/jxcore-log( 8142): Process ARCH arm
W/jxcore-log( 8142): 
,I/art     ( 2925): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 8142): JXcore Cordova bridge is ready!
I/jxcore-log( 8142): 
W/jxcore-log( 8142): JXcore engine is started
,I/jxcore-log( 8142): Toggling radios to true
I/jxcore-log( 8142): 
,I/HwSystemManager( 3465): HoldService:checkBeforeShowDialog: uid:10295 pid:8142, permissionType:2097152
I/HwSystemManager( 3465): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2925): allowOpenWifi blocked:false
,E/WifiStateMachine( 2925):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 2925):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 2925): [108,889,826 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,I/jxcore-log( 8142): Radios toggled
I/jxcore-log( 8142): 
I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3258): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2925): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 3258): check_associate_result func start
,I/jxcore-log( 8142): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 8142): 
,W/System.err( 2925): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2925): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 2925): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 2925): This is not beta user build
,I/jxcore-log( 8142): Perf Test app loaded loaded
I/jxcore-log( 8142): 
,I/Choreographer( 8142): Skipped 93 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 8142): check test folder
I/jxcore-log( 8142): 
,I/jxcore-log( 8142): found test : ./testFindPeers.js
I/jxcore-log( 8142): 
,E/WifiMonitor( 2925): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,W/wpa_supplicant( 3258): STA MODE: Set shutdown wlan cmd SUCCESS
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,W/wpa_supplicant( 3258): check_associate_result func start
,I/wpa_supplicant( 3258): set current WIFI status to BT!
I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
E/WifiStateMachine( 2925): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 2925): setScanAlarm false period 20000 initial delay 0
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,E/WifiStateMachine( 2925): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2925): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 2925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 8142): found test : ./testSendData.js
I/jxcore-log( 8142): 
,E/native  ( 2925): do suspend true
,I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
,E/Netd    ( 2305): ifc_reset_connections failed on iface wlan0 for address 192.168.1.120/24 (Unknown error -1)
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/ArpVerifier( 2925): current SSID is empty.
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiConfigStore( 2925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 2925):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 2925): Start Disconnecting Watchdog 1
E/WifiStateMachine( 2925):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 2925):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 2925): [109,006,271 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
W/wpa_supplicant( 3258): check_associate_result func start
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 3258): wlan is down..., now start up...
,E/WifiStateMachine( 2925):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109016
,E/WifiStateMachine( 2925):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109017
,E/native  ( 2925): do suspend true
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/WifiTracker( 3138): STATE =1
,W/View    ( 3138): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{77ac166 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,W/wpa_supplicant( 3258): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4657): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4657): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3258): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2925): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2925): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
,E/WifiStateMachine( 2925): setScanAlarm true period 0 initial delay 200
,E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=109767  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=109768  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 2925):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 2925): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2925):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 2925): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2925):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 2925): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,I/HwSystemManager( 3465): aor:Network Stats Updated
,I/HwSystemManager( 3465): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES,
E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=109789  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE,
I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=109793  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/chromium( 8142): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/HwSystemManager( 3465): aor:Network Stats Updated,
I/HwSystemManager( 3465): aoi:onNetworkStatsUpdated
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null,
E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/chromium( 8142): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/HwSystemManager( 3465): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
,I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null,
E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3465): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3465): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3465): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
,I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.,
E/HwSystemManager( 3465): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3465): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/OAM     ( 2644): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
,I/OAM     ( 2644): [rename_old_file:107]rename_old_file
I/OAM     ( 2644): 
,I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48,
E/WifiMonitor( 2925): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2925): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 2925): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 2925):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:327 bcn=0
E/WifiStateMachine( 2925):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:327 bcn=0
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 2925):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:327 bcn=0
I/wpa_supplicant( 3258): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 2925):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:327 bcn=0
E/WifiStateMachine( 2925): [1,449,754,815,568 ms] noteScanEnd no scan source
W/wpa_supplicant( 3258): check_associate_result func start
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4657): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4657): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,E/WifiStateMachine( 2925): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1f32be1 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController ( 2925): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController ( 2925): Gonzos 38:f8:89:11:e9:11 rssi=-87 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController ( 2925): ageScanResultsOut delay 40000 size 3 now 1449754815574
E/WifiAutoJoinController ( 2925): newSupplicantResults size=3 known=1 true
,E/WifiAutoJoinController ( 2925): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController ( 2925): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2925): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2925): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
,E/WifiAutoJoinController ( 2925): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiStateMachine( 2925):  DisconnectedState CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=110469
,E/WifiStateMachine( 2925):  ConnectModeState CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=110469
E/WifiStateMachine( 2925):  DriverStartedState CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=110469
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=110470
,E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=110470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=110476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,E/HI110X_CHR_LOGD( 2645): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/wpa_supplicant( 3258): check_associate_result func start
,I/wpa_supplicant( 3258): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48,
E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111009  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111012  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 2925): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72 SSID=0x
,W/wpa_supplicant( 3258): check_associate_result func start
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 2925):  DisconnectedState CMD_ASSOCIATED_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=111023
E/WifiStateMachine( 2925):  ConnectModeState CMD_ASSOCIATED_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=111023
E/WifiStateMachine( 2925):  DriverStartedState CMD_ASSOCIATED_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=111024
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_ASSOCIATED_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=111024
,E/WifiStateMachine( 2925):  DefaultState CMD_ASSOCIATED_BSSID 41 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=111024
I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=111025  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE,
,W/wpa_supplicant( 3258): check_associate_result func start
,W/wpa_supplicant( 3258): check_associate_result func start
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 3258): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP],
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 2925): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3258): set current WIFI status to BT!
I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
,I/bluetooth-coex( 4657): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
I/wpa_supplicant( 3258): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiMonitor( 2925): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
W/wpa_supplicant( 3258): check_associate_result func start
E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=111045  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 2925):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=111046  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 2925): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=111047  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 2925):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111048
,E/WifiStateMachine( 2925):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111049
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,W/System.err( 2925): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2925): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2925): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2925): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 2925): ,	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
,W/System.err( 2925): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 2925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2925): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 2925): This is not beta user build
I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925): setScanAlarm false period 0 initial delay 0
,I/WiFi_PRO( 2925): obtaining wifi is conencted
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2925): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 2925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 2925): obtaining wifi is conencted
,E/WifiStateMachine( 2925): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 2925): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 2925): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,E/WifiStateMachine( 2925): Start Dhcp Watchdog 2
,E/WifiStateMachine( 2925):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=111095  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 2925):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=111095  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 2925):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=111096  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 2925):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,I/wpa_supplicant( 3258): set current WIFI status to BT!
I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
,E/native  ( 2925): do suspend false
,E/WifiStateMachine( 2925): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 2925): noteBatchedScanstop()
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/DHCPCD  ( 8219): version 5.5.6 starting
,W/DHCPCD  ( 8219): hw_parse_xidfile 
I/DHCPCD  ( 8219): wlan0: dhcp start reboot
I/DHCPCD  ( 8219): wlan0: rebinding lease of 192.168.1.120
,I/DHCPCD  ( 8219): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,I/DHCPCD  ( 8219): wlan0: checking for 192.168.1.120
,W/ArpVerifier( 2925): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,I/DHCPCD  ( 8219): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2925): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 2925): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 2925): do suspend true
,I/wpa_supplicant( 3258): set current WIFI status to BT!
,I/bluetooth-coex( 4657): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4657): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 2925): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 2925): link address 192.168.1.120/24
,E/WifiStateMachine( 2925): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 2925): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 2925):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2925): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2925): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine( 2925): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 2925): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
I/HwSystemManager( 3465): aor:Network Stats Updated
I/HwSystemManager( 3465): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3465): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3465): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3465): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3465): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3465): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3465): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3465): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/NetworkSpeedManagerEx( 3138): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3138): wifiManager = android.net.wifi.WifiManager@23560f59
,I/NetworkSpeedManagerEx( 3138): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3138): stop
,I/WifiTracker( 3138): STATE =1
,W/View    ( 3138): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{77ac166 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3138): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{77ac166 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/System  ( 2925): core_booster, getBoosterConfig = false
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,I/WifiTracker( 3138): STATE =1
,W/View    ( 3138): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{77ac166 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,E/WifiStateMachine( 2925):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:18590] from screen [on:0 period:-1944128190] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,I/ActivityManager( 2925): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3579): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3579): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3579): bBrokenPipe = false
,I/NetworkMonitor( 7259): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 2925): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 7259): type=WIFI subType= reason=null isConnected=true
I/SUPL20_SCM( 3579): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3579): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3579): bBrokenPipe = false
,I/HwEmailTag( 8257): MailAppProvider->onCreate->begin, consuming 1449754817994ms->-prefixstartupperformance-
,I/art     ( 3557): Explicit concurrent mark sweep GC freed 26912(1426KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.340ms total 64.406ms
,I/HwEmailTag( 8257): MailAppProvider->onCreate->end, consuming 1449754818024ms->-prefixstartupperformance-
,I/HwCust  ( 8257): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 8257): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 8257): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 8257): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 8257): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 8257): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 8257): HwUtils->initStaticVarsAsync
,I/HwEmailTag( 8257): HwUtils->initStaticVarsAsync
,I/HwCust  ( 8257): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 8257): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 8257): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 8257): EmailProvider->onCreate->end, consuming 34ms->-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailProvider->onCreate->end, consuming 34ms->-prefixstartupperformance-
,I/HwCust  ( 8257): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 8257): EmailProvider->resetVisibleLimits->start:1449754818090 ->-prefixstartupperformance-
I/HwEmailTag( 8257): EmailProvider->resetVisibleLimits->start:1449754818091 ->-prefixstartupperformance-
,I/HwEmailTag( 8257): HwUtils->initStaticVarsAsync->run:consuming:49ms; bidiFormatter:android.support.v4.text.BidiFormatter@263039f4;accountsProjSize:42
I/HwEmailTag( 8257): HwUtils->initStaticVarsAsync->run:consuming:49ms; bidiFormatter:android.support.v4.text.BidiFormatter@263039f4;accountsProjSize:42
,I/HwEmailTag( 8257): EmailApplication->onCreate->begin, consuming 59ms->-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwCust  ( 8257): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwEmailTag( 8257): DBHelper->onOpen-> EmailProvider.db
I/HwCust  ( 8257): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 8257): EmailApplication->onCreate->end, consuming 64ms->-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
,I/HwEmailTag( 8257): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 8257): EmailProvider->notifyNetworkChanged->
,I/HwEmailTag( 8257): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 36ms.
,I/HwEmailTag( 8257): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8257): EmailProvider->initBuildCache->start->1449754818174->-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 8257): EmailProvider->initBuildCache->start->1449754818174; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 8257): EmailProvider->uiAccounts->start:1449754818176
,I/HwEmailTag( 8257): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8257): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 13ms.
,I/HwEmailTag( 8257): DBHelper->onOpen-> EmailProvider.db
,I/art     ( 2925): Explicit concurrent mark sweep GC freed 94099(4MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/42MB, paused 2.045ms total 207.661ms
,E/TEST-APN( 3557): query for APN: check-permission succ 
,E/TEST-APN( 3557): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/HwEmailTag( 8257): EmailProvider->resetVisibleLimits->getDatabase, consuming:137ms;-prefixstartupperformance-
I/HwEmailTag( 8257): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 8257): EmailProvider->resetVisibleLimits->getDatabase, consuming:138ms;-prefixstartupperformance-
I/HwEmailTag( 8257): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 8257): EmailProvider->uiAccounts->start:1449754818176;end,consuming:56
I/HwEmailTag( 8257): EmailProvider->query->1449754818087;end;;consuming:146ms;
,I/DownloadManager( 3164): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,E/GpsLocationProvider( 2925): No APN found to select.
,I/HwSystemManager( 3465): HoldService:uid:10050 pid:7611 died
I/HwSystemManager( 3465): HoldService:oldVersionKey:10050,7611
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10050
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10050, pid: 7611
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10050, pid: 7611
,W/GNSS_ADAPTER( 2925): This function not used.
W/GNSS_ADAPTER( 2925): This function not used.
,E/TEST-APN( 3557): query for APN: check-permission succ 
,E/TEST-APN( 3557): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 2925): No APN found to select.
,W/GNSS_ADAPTER( 2925): This function not used.
,W/GNSS_ADAPTER( 2925): This function not used.
,I/HwCust  ( 7212): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 7212): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/MagazineUtils( 3066): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 7212): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 7212): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 2925): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2925): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,E/HwOUC   ( 8292): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8292): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8292): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 8292): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8292): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8292): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8292): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8292): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 3465): HoldService:uid:10001 pid:6881 died
I/HwSystemManager( 3465): HoldService:oldVersionKey:10001,6881
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10001, pid: 6881
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10001, pid: 6881
,W/asset   ( 8315): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8315): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 8315): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8315): ThemeHelperretry to get Settings
,W/asset   ( 8339): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8339): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/HwSystemManager( 6748): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwSystemManager( 3465): HoldService:uid:10004 pid:6258 died
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 3465): HoldService:oldVersionKey:10004,6258
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10004, pid: 6258
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10004, pid: 6258
,I/jxcore-log( 8142): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 8142): 
,E/WifiStateMachine( 2925):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2925):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2925):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 2925):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2925):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3465): HoldService:uid:10010 pid:7586 died
I/HwSystemManager( 3465): HoldService:oldVersionKey:10010,7586
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10010, pid: 7586
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10010, pid: 7586
,W/ContextImpl( 8385): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8385): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8385): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8385):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8385):   adb logcat -s GAv4
,W/ContextImpl( 8385): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8385): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8385): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8385): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8385): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 5
E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/PG Utils( 8385): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 8385): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 8385): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 8385): Loading: webviewchromium
,I/LibraryLoader( 8385): Time to load native libraries: 3 ms (timestamps 4502-4505)
I/LibraryLoader( 8385): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 8385): Expected native library version number "",actual native library version number ""
,I/chromium( 8385): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8385): Initializing chromium process, renderers=0
,W/art     ( 8385): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 8385): Requires BLUETOOTH permission
,W/chromium( 8385): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8385): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
I/chromium( 8385): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 8385): Starting up...
,I/System  ( 6939): core_booster, getBoosterConfig = false
,I/HwEmailTag( 8257): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 8257): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 8257): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3164): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 7212): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7212): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3066): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8292): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8292): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/art     ( 8315): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8315): ThemeHelperretry to get Settings
,E/HwSystemManager( 6748): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwEmailTag( 8257): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 8257): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwSystemManager( 3465): HoldService:uid:1000 pid:7735 died
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3465): HoldService:oldVersionKey:1000,7735
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
W/MediaProcessHandler( 2925): processOp uid 1000 is not concerned!
,I/HwEmailTag( 8257): EmailProvider->query->1449754820100;end;;consuming:3ms;
,I/HwEmailTag( 8257): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 8257): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 8257): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 8257): Device->getDeviceId->
I/HwEmailTag( 8257): CleanRecipient->onCreate
,I/HwEmailTag( 8257): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 8257): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 8257): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 8257): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 8257): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 8257): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 8257): CleanRecipient->onDestroy
,I/HwEmailTag( 8257): AccountReconciler->reconcileAccountsInternal->consuming:80ms
,I/HwEmailTag( 8257): EmailProvider->query->1449754820188;end;;consuming:1ms;
,I/HwEmailTag( 8257): AccountReconciler->reconcileAccountsInternal->consuming:2ms
,I/HwCust  ( 8461): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 8461): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 8461): Exchange->onCreate
,I/PG Utils( 8461): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8461): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 8257): EmailProvider->query->1449754820271;end;;consuming:2ms;
,I/HwEmailTag( 8461): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/HwSystemManager( 3465): HoldService:uid:10044 pid:7779 died
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10044
I/HwSystemManager( 3465): HoldService:oldVersionKey:10044,7779
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10044, pid: 7779
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10044, pid: 7779
,W/ArpVerifier( 2925): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/ActivityManager( 2925): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3579): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3579): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3579): bBrokenPipe = false
,I/NetworkMonitor( 7259): type=WIFI subType= reason=null isConnected=true
,I/HwEmailTag( 8257): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 8257): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 8257): EmailProvider->notifyNetworkChanged->
,E/TEST-APN( 3557): query for APN: check-permission succ 
E/TEST-APN( 3557): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 2925): No APN found to select.
,W/GNSS_ADAPTER( 2925): This function not used.
W/GNSS_ADAPTER( 2925): This function not used.
,I/DownloadManager( 3164): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 7212): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7212): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3066): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8292): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
I/HwOUC   ( 8292): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 8292): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 8292): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
I/HwOUC   ( 8292): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,I/art     ( 8315): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8315): ThemeHelperretry to get Settings
,E/HwSystemManager( 6748): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwOUC   ( 8292): [Thread-134-134]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,I/HwOUC   ( 8292): [Thread-134-134]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/Process ( 8292): Sending signal. PID: 8292 SIG: 9
,E/WifiStateMachine( 2925):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 2925):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 2925):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/HwSystemManager( 3465): HoldService:uid:10052 pid:8292 died
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3465): HoldService:oldVersionKey:10052,8292
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10052, pid: 8292
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10052, pid: 8292
,I/HwEmailTag( 8257): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 8257): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 8257): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 8257): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 8257): EmailProvider->triggerAllPeriodSync
,I/HwEmailTag( 8257): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 8257): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 8257): EmailProvider->query->1449754823740;end;;consuming:4ms;
,E/WifiStateMachine( 2925):  ConnectedState what:131272 1 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:131272 1 0
,E/WifiStateMachine( 2925):  ConnectModeState what:131272 1 0
E/WifiStateMachine( 2925):  DriverStartedState what:131272 1 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:131272 1 0
,E/WifiStateMachine( 2925):  DefaultState what:131272 1 0
,E/WifiStateMachine( 2925): Error! unhandled message{ when=-18ms what=131272 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/ArpVerifier( 2925): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 0 firstTime = 122982 firstmBatteryCapacity =2203
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 3542 firstTime = 122982 firstmBatteryCapacity =2203
,E/Thermal-daemon( 2329): [charger_ic] temp_new :31  temp_old :32
,E/Thermal-daemon( 2329): [ap] temp_new :31  temp_old :32
,I/ActivityManager( 2925): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/VacuumService( 3849): Vacuum at: now=1449754832718 tag=VacuumService
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/SyncManager( 2925): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,I/ActivityManager( 2925): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 5842): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 3849): Scheduling Phenotype for one-off execution 8524 seconds from now (1449754833052)
,I/ActivityManager( 2925): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 3849): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 3849): Using platform SSLCertificateSocketFactory
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 2925): Explicit concurrent mark sweep GC freed 37060(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.905ms total 179.169ms
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 3849): core_booster, getBoosterConfig = false
,I/System  ( 3849): core_booster, getBoosterConfig = false
,I/PG Utils( 3849): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/art     ( 8315): System.exit called, status: 0
I/AndroidRuntime( 8315): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3465): HoldService:uid:10060 pid:8315 died
I/HwSystemManager( 3465): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3465): HoldService:oldVersionKey:10060,8315
E/HsmCoreServiceImpl( 2925): onTransact in code is: 102
I/MediaProcessHandler( 2925): processOp opType: 1, uid: 10060, pid: 8315
W/MediaProcessHandler( 2925): remove target not exist, maybe the UI process: uid: 10060, pid: 8315
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3465): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3465): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 3465): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3465): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3465): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3465): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3465): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3465): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3465): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1168785408 [332800000,437657600,542515200]
I/HwSystemManager( 3465): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3465): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,E/WifiStateMachine( 2925):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2925):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2925):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2925):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2925):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2925):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/ClearcutLoggerApiImpl( 3849): disconnect managed GoogleApiClient
,E/Thermal-daemon( 2329): [ap] temp_new :30  temp_old :31
,I/ActivityManager( 2925): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/TimeManager( 3138): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3138): hand message 1
I/TimeManager( 3138): notify time change. size = 2
,I/TimeLayout( 3138): time = 14:41
,I/bluedroid( 4657): bt interface: [set_adapter_property]
I/bluedroid( 4657): bt interface: [set_adapter_property]
W/bt-btif ( 4657): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 4657): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 4657): adapterPropertyChangedCallback with type:9 len:4
,I/TimeLayout( 3138): updateDate date = 12/10/2015
,W/bt-btif ( 4657): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 4657): BTM_SetConnectability
I/BluetoothAdapterProperties( 4657): adapterPropertyChangedCallback with type:7 len:4
I/TimeLayout( 3138): weekDay = Thursday
,I/HwLauncher( 4742): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 8
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2329): [charger_ic] temp_new :30  temp_old :31
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 63540 firstTime = 122982 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 90321 firstTime = 122982 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 12
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 120400 firstTime = 122982 firstmBatteryCapacity =2203
,I/HwSystemManager( 3465): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3465): BgPowerManagerService: mTimes = 123537 firstTime = 122982 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=58 dispatchEvent: HEART-BEAT-ACK: 16
E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2329): [ap] temp_new :29  temp_old :30
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor( 2925): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,I/wpa_supplicant( 3258): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 2925): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 17
E/WifiStateMachine( 2925):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2925):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2925):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2925):  SupplicantStartedState what:147506 0 0

```
