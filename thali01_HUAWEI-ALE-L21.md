#### Test 5065027870036d7_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 8268): CLASSPATH=/system/framework/am.jar
I/appproc ( 8268): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 8268): app_process:number,5,0
I/AndroidRuntime( 8268): readDownloadBoosterConfig: 'false'
I/        ( 8268): power log dlsym ok
E/android_hardware_fm.cpp( 8268): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 8268): ========64bit long size = 8
E/FM_HAL  ( 8268): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 8268): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 8268): 
I/fm_hisi ( 8268): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 8268): 
I/fm_hisi ( 8268): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 8268): 
E/android_hardware_fm.cpp( 8268): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 3052): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3052): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3052): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3052): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3954): AppLockService:applock password not initial or function is closed
I/HwLauncher( 4110): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 4110): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 4110): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3954): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3954): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 4110): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 4110): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 8287): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 8287): Loading: webviewchromium
I/LibraryLoader( 8287): Time to load native libraries: 55 ms (timestamps 513-568)
I/LibraryLoader( 8287): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 8287): Expected native library version number "",actual native library version number ""
I/chromium( 8287): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8287): Initializing chromium process, renderers=0
W/art     ( 8287): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8287): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8287): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 8287): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 8287): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 8287): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 8287): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 8287): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 8287): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 8287): Can not find class: Landroid/widget/ViewStub;
I/art     ( 8287): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 8287): Can not find class: Landroid/app/ViewStub;
I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 4
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=29 dispatchEvent: HEART-BEAT-ACK: 4
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
W/art     ( 8287): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 8287): Attempt to remove local handle scope entry from IRT, ignoring
I/PhoneStatusBar( 3575): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3575): shouldTranslucent:true
I/PhoneStatusBar( 3575): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 8287): Initialized EGL, version 1.4
I/ActivityManager( 3052): Displayed com.test.thalitest/.MainActivity: +1s10ms (total +1s80ms)
W/IInputConnectionWrapper( 8287): showStatusIcon on inactive InputConnection
I/chromium( 8287): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 8287): 
,E/WifiStateMachine( 3052):  ConnectedState what:131272 1 0
E/WifiStateMachine( 3052):  L2ConnectedState what:131272 1 0
,E/WifiStateMachine( 3052):  ConnectModeState what:131272 1 0
E/WifiStateMachine( 3052):  DriverStartedState what:131272 1 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:131272 1 0
E/WifiStateMachine( 3052):  DefaultState what:131272 1 0
,E/WifiStateMachine( 3052): Error! unhandled message{ when=-4ms what=131272 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/jxcore-log( 8287): Initializing JXcore engine
W/jxcore-log( 8287): JXcore engine is ready
,W/jxcore-log( 8287): Starting JXcore engine
,W/jxcore-log( 8287): Platform android
W/jxcore-log( 8287): 
W/jxcore-log( 8287): Process ARCH arm
W/jxcore-log( 8287): 
,I/art     ( 3052): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 8287): JXcore Cordova bridge is ready!
I/jxcore-log( 8287): 
W/jxcore-log( 8287): JXcore engine is started
,I/art     ( 6422): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,I/jxcore-log( 8287): Toggling radios to true
I/jxcore-log( 8287): 
,I/HwSystemManager( 3954): HoldService:checkBeforeShowDialog: uid:10295 pid:8287, permissionType:2097152
I/HwSystemManager( 3954): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 3052): allowOpenWifi blocked:false
,E/WifiStateMachine( 3052):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 3052):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 3052): [105,118,117 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,I/wpa_supplicant( 3588): set current WIFI status to BT!
I/jxcore-log( 8287): Radios toggled
I/jxcore-log( 8287): 
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/wpa_supplicant( 3588): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3052): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 3588): check_associate_result func start
,W/System.err( 3052): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3052): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3052): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3052): This is not beta user build
,I/jxcore-log( 8287): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): Perf Test app loaded loaded
I/jxcore-log( 8287): 
,E/WifiMonitor( 3052): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,I/jxcore-log( 8287): check test folder
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): found test : ./testFindPeers.js
I/jxcore-log( 8287): 
,W/wpa_supplicant( 3588): STA MODE: Set shutdown wlan cmd SUCCESS
,W/wpa_supplicant( 3588): check_associate_result func start
I/wpa_supplicant( 3588): set current WIFI status to BT!
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
E/WifiStateMachine( 3052): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3052): setScanAlarm false period 20000 initial delay 0
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 3052): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3052): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3052): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 3052): do suspend true
,I/wpa_supplicant( 3588): set current WIFI status to BT!
,I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
,E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/jxcore-log( 8287): found test : ./testSendData.js
I/jxcore-log( 8287): 
I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/ArpVerifier( 3052): current SSID is empty.
,E/WifiConfigStore( 3052): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3052):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3052): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3052):  DisconnectingState CMD_RECONNECT 0 0
,E/WifiStateMachine( 3052):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 3052): [105,244,991 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
,W/wpa_supplicant( 3588): check_associate_result func start
I/wpa_supplicant( 3588): wlan is down..., now start up...
I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,E/WifiStateMachine( 3052):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105264
,E/WifiStateMachine( 3052):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105268
,E/native  ( 3052): do suspend true
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/WifiTracker( 3575): STATE =1
,W/View    ( 3575): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{d011ef2 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,W/wpa_supplicant( 3588): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3588): set current WIFI status to BT!
,I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 5408): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 5408): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3588): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3052): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3052): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3588): set current WIFI status to BT!
,I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3052):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 3052): setScanAlarm true period 0 initial delay 200
,E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=106032  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=106034  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3052):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3052):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 3052): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,E/WifiStateMachine( 3052): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3052):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=106052  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
I/HwSystemManager( 3954): aor:Network Stats Updated
I/HwSystemManager( 3954): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=106056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/chromium( 8287): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwSystemManager( 3954): aor:Network Stats Updated
I/HwSystemManager( 3954): aoi:onNetworkStatsUpdated
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3954): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/chromium( 8287): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/wpa_supplicant( 3588): set current WIFI status to BT!
,I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 3052): handleEvent 12  CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3052): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=36 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 3052): couldn't identify event type - WPS-AP-AVAILABLE 
,E/WifiStateMachine( 3052):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:317 bcn=0
,E/WifiStateMachine( 3052):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:317 bcn=0
,I/wpa_supplicant( 3588): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 3052):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:317 bcn=0
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=37 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 3052):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=1 got=1 dur:317 bcn=0
E/WifiStateMachine( 3052): [1,450,127,803,957 ms] noteScanEnd no scan source
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
W/wpa_supplicant( 3588): check_associate_result func start
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
I/wpa_supplicant( 3588): set current WIFI status to BT!
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 5408): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 5408): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/WifiStateMachine( 3052): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f83048d sup_state=SCANNING debouncing=false
E/WifiAutoJoinController ( 3052): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 3052): 01ABC c2:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 3052): ageScanResultsOut delay 40000 size 2 now 1450127803962
E/WifiAutoJoinController ( 3052): newSupplicantResults size=2 known=1 true
E/WifiAutoJoinController ( 3052): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController ( 3052): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3052): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3052): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
E/WifiAutoJoinController ( 3052): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiStateMachine( 3052):  DisconnectedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106729
E/WifiStateMachine( 3052):  ConnectModeState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106729
E/WifiStateMachine( 3052):  DriverStartedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106730
E/WifiStateMachine( 3052):  SupplicantStartedState CMD_TARGET_BSSID 37 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=106730
,E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=106731  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE,
,E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=106736  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE,
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,W/wpa_supplicant( 3588): check_associate_result func start
,I/wpa_supplicant( 3588): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=107523  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=107523  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 3052): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72 SSID=0x
,E/WifiStateMachine( 3052):  DisconnectedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107532
E/WifiStateMachine( 3052):  ConnectModeState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107532
E/WifiStateMachine( 3052):  DriverStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107533
,E/WifiStateMachine( 3052):  SupplicantStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107533
E/WifiStateMachine( 3052):  DefaultState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=107533
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,W/wpa_supplicant( 3588): check_associate_result func start
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=107547  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=107552  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/wpa_supplicant( 3588): check_associate_result func start
,W/wpa_supplicant( 3588): check_associate_result func start
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 3052): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3588): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3588): set current WIFI status to BT!
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3588): set current WIFI status to BT!
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 3052): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3588): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
W/wpa_supplicant( 3588): check_associate_result func start
E/WifiStateMachine( 3052):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=107566  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 3052): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=107567  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 3052):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107568
,E/WifiStateMachine( 3052):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107569
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,W/System.err( 3052): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3052): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3052): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3052): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 3052): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 3052): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 3052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3052): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3052): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 3052): This is not beta user build
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3052): setScanAlarm false period 0 initial delay 0
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE,
,I/WiFi_PRO( 3052): obtaining wifi is conencted
,E/WifiStateMachine( 3052): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 3052): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3052): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3052): obtaining wifi is conencted
,E/WifiStateMachine( 3052): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine( 3052): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3052): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,E/WifiStateMachine( 3052): Start Dhcp Watchdog 2,
I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
E/WifiStateMachine( 3052):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=107615  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 3052):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=107616  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 3052):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=107616  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3052):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3052):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
I/wpa_supplicant( 3588): set current WIFI status to BT!
I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
E/native  ( 3052): do suspend false
,E/WifiStateMachine( 3052): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 3052): noteBatchedScanstop()
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/DHCPCD  ( 8370): version 5.5.6 starting
,W/DHCPCD  ( 8370): hw_parse_xidfile 
I/DHCPCD  ( 8370): wlan0: dhcp start reboot
I/DHCPCD  ( 8370): wlan0: rebinding lease of 192.168.1.120
,I/DHCPCD  ( 8370): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,W/ArpVerifier( 3052): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,I/DHCPCD  ( 8370): wlan0: checking for 192.168.1.120
,I/DHCPCD  ( 8370): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 3052):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3052): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3052):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 3052):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 3052):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 3052):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 3052):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 3052): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager( 3052): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 3052):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 3052): do suspend true
,I/wpa_supplicant( 3588): set current WIFI status to BT!
,I/bluetooth-coex( 5408): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5408): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 3052): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
I/SUPL20_SCM( 4082): Network connection true
I/SUPL20_SPIMESLP-SENDING( 4082): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4082): bBrokenPipe = false
,E/WifiStateMachine( 3052): link address 192.168.1.120/24
,E/WifiStateMachine( 3052): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
I/SUPL20_SCM( 4082): Network connection true
I/SUPL20_SPIMESLP-SENDING( 4082): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4082): bBrokenPipe = false
E/WifiStateMachine( 3052): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 3052):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 3052):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,W/View    ( 3575): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{d011ef2 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/TEST-APN( 4056): query for APN: check-permission succ 
E/TEST-APN( 4056): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3052): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3052): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine( 3052): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/GpsLocationProvider( 3052): No APN found to select.
,W/GNSS_ADAPTER( 3052): This function not used.
,W/GNSS_ADAPTER( 3052): This function not used.
,E/TEST-APN( 4056): query for APN: check-permission succ 
E/TEST-APN( 4056): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3052): No APN found to select.
,W/GNSS_ADAPTER( 3052): This function not used.
,W/GNSS_ADAPTER( 3052): This function not used.
,E/WifiStateMachine( 3052): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/HwSystemManager( 3954): aor:Network Stats Updated
I/HwSystemManager( 3954): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3954): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/HwEmailTag( 8397): MailAppProvider->onCreate->begin, consuming 1450127806467ms->-prefixstartupperformance-
,I/System  ( 3052): core_booster, getBoosterConfig = false
,I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
,I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/HwEmailTag( 8397): MailAppProvider->onCreate->end, consuming 1450127806499ms->-prefixstartupperformance-
,I/HwCust  ( 8397): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 8397): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 8397): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
I/HwCust  ( 8397): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
W/View    ( 3575): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{d011ef2 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
I/NetworkSpeedManagerEx( 3575): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3575): wifiManager = android.net.wifi.WifiManager@7c49d15
E/WifiStateMachine( 3052):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:33825] from screen [on:0 period:-1571139517] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
I/NetworkSpeedManagerEx( 3575): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3575): stop
,I/HwEmailTag( 8397): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 8397): HwUtils->initStaticVarsAsync
,I/HwEmailTag( 8397): EmailProvider->onCreate->start. -prefixstartupperformance-
,I/HwEmailTag( 8397): HwUtils->initStaticVarsAsync
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/WifiTracker( 3575): STATE =1
,I/HwCust  ( 8397): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 8397): EmailContent->init->consuming:21ms->;-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 8397): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 8397): EmailProvider->onCreate->end, consuming 39ms->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->onCreate->end, consuming 40ms->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->resetVisibleLimits->start:1450127806574 ->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->resetVisibleLimits->start:1450127806577 ->-prefixstartupperformance-
I/HwCust  ( 8397): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 8397): HwUtils->initStaticVarsAsync->run:consuming:51ms; bidiFormatter:android.support.v4.text.BidiFormatter@2005ea1d;accountsProjSize:42
,I/HwEmailTag( 8397): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8397): HwUtils->initStaticVarsAsync->run:consuming:50ms; bidiFormatter:android.support.v4.text.BidiFormatter@2005ea1d;accountsProjSize:42
,I/HwEmailTag( 8397): EmailApplication->onCreate->begin, consuming 66ms->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwCust  ( 8397): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 8397): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 8397): EmailApplication->onCreate->end, consuming 71ms->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 32ms.
I/HwEmailTag( 8397): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 8397): HwUtils->notifyNetworkChanged->
W/View    ( 3575): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{d011ef2 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/HwEmailTag( 8397): EmailProvider->notifyNetworkChanged->
,I/HwEmailTag( 8397): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8397): EmailProvider->initBuildCache->start->1450127806661->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 8397): EmailProvider->initBuildCache->start->1450127806661; consuming:2->-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->uiAccounts->start:1450127806663
,I/HwEmailTag( 8397): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8397): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 12ms.
,I/HwEmailTag( 8397): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 8397): EmailProvider->resetVisibleLimits->getDatabase, consuming:146ms;-prefixstartupperformance-
,I/HwEmailTag( 8397): EmailProvider->resetVisibleLimits->getDatabase, consuming:143ms;-prefixstartupperformance-
I/HwEmailTag( 8397): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 8397): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 8397): EmailProvider->uiAccounts->start:1450127806663;end,consuming:61
,I/HwEmailTag( 8397): EmailProvider->query->1450127806571;end;;consuming:153ms;
,I/DownloadManager( 3551): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwSystemManager( 3954): HoldService:uid:10050 pid:7880 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:10050,7880
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10050, pid: 7880
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10050, pid: 7880
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10050
,I/HwCust  ( 7589): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 7589): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/MagazineUtils( 3464): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 7589): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 7589): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3052): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 3052): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,E/HwOUC   ( 8436): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8436): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8436): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 8436): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8436): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8436): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8436): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8436): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 3954): HoldService:uid:10001 pid:6917 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:10001,6917
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10001, pid: 6917
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10001, pid: 6917
,W/asset   ( 8459): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8459): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 8459): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8459): ThemeHelperretry to get Settings
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 195us total 23.325ms
,W/asset   ( 8483): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 215us total 22.935ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 199us total 23.057ms
,I/HwCust  ( 8483): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/HwSystemManager( 7162): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/jxcore-log( 8287): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 8287): 
,I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10004
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10004, pid: 6763
I/HwSystemManager( 3954): HoldService:uid:10004 pid:6763 died
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10004, pid: 6763
I/HwSystemManager( 3954): HoldService:oldVersionKey:10004,6763
,E/WifiStateMachine( 3052):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3052):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3052):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3052):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3052):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/HwSystemManager( 3954): HoldService:uid:10010 pid:7856 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:10010,7856
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10010
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10010, pid: 7856
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10010, pid: 7856
,W/ContextImpl( 8533): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8533): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/ContextImpl( 8533): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 8533): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8533):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8533):   adb logcat -s GAv4
,W/ContextImpl( 8533): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8533): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8533): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8533): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 8533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 8533): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 8533): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 8533): Loading: webviewchromium
,I/LibraryLoader( 8533): Time to load native libraries: 3 ms (timestamps 813-816)
,I/LibraryLoader( 8533): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 8533): Expected native library version number "",actual native library version number ""
,I/chromium( 8533): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8533): Initializing chromium process, renderers=0
,W/art     ( 8533): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 8533): Requires BLUETOOTH permission
,W/chromium( 8533): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8533): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
,I/chromium( 8533): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 8533): Starting up...
,I/System  ( 6636): core_booster, getBoosterConfig = false
,I/HwSystemManager( 3954): HoldService:uid:1000 pid:8008 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:1000,8008
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
W/MediaProcessHandler( 3052): processOp uid 1000 is not concerned!
,I/HwEmailTag( 8397): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 8397): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 8397): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3551): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 7589): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 7589): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3464): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8436): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8436): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/art     ( 8459): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8459): ThemeHelperretry to get Settings
,E/HwSystemManager( 7162): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwEmailTag( 8397): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 8397): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 8397): EmailProvider->query->1450127808572;end;;consuming:2ms;
,I/HwEmailTag( 8397): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 8397): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 8397): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 8397): Device->getDeviceId->
,I/HwEmailTag( 8397): CleanRecipient->onCreate
I/HwEmailTag( 8397): AccountReconciler->reconcileAccountsInternal->consuming:71ms
I/HwEmailTag( 8397): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 8397): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 8397): CleanRecipient->onStartCommand->action is null
,I/HwEmailTag( 8397): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 8397): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 8397): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
I/HwEmailTag( 8397): CleanRecipient->onDestroy
,I/HwCust  ( 8608): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 8608): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 8608): Exchange->onCreate
,I/PG Utils( 8608): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8608): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 8397): EmailProvider->query->1450127808736;end;;consuming:1ms;
,I/HwEmailTag( 8608): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/HwSystemManager( 3954): HoldService:uid:10044 pid:8048 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:10044,8048
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10044, pid: 8048
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10044, pid: 8048
,W/ArpVerifier( 3052): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/ActivityManager( 3052): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 4082): Network connection true
I/SUPL20_SPIMESLP-SENDING( 4082): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4082): bBrokenPipe = false
,I/NetworkMonitor( 8128): type=WIFI subType= reason=null isConnected=true
,I/AccountTypeManager( 7589): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2f274c6b in the cache
,I/HwEmailTag( 8397): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 8397): HwUtils->notifyNetworkChanged->
I/SimFactoryManager( 7589): Get SIM state from SIM factory manager: 1,For slotId:0
I/HwEmailTag( 8397): EmailProvider->notifyNetworkChanged->
,I/SimFactoryManager( 7589): Get SIM state from SIM factory manager: 1,For slotId:1
,W/SyncManager( 3052): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,I/DownloadManager( 3551): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/AccountTypeManager( 7589): Adding account type = com.android.contacts.model.account.ExternalAccountType@12c653c8 in the cache
E/TEST-APN( 4056): query for APN: check-permission succ 
E/TEST-APN( 4056): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3052): No APN found to select.
,W/GNSS_ADAPTER( 3052): This function not used.
W/GNSS_ADAPTER( 3052): This function not used.
,W/ResourceType( 7589): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7589): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 7589): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7589): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7589): Adding account type = com.android.contacts.model.account.ExternalAccountType@1fd0e474 in the cache
,I/AccountTypeManager( 7589): Adding account type = com.android.contacts.model.account.GoogleAccountType@1744cd9d in the cache
,E/ExternalAccountType( 7589): Unsupported attribute readOnly
,I/AccountTypeManager( 7589): AccountManager, account size is: 2
,I/AccountTypeManager( 7589): Loaded meta-data for 5 account types, 3 accounts in 72ms(wall) 32ms(cpu)
,E/WifiStateMachine( 3052):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 3052):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/art     ( 3052): Explicit concurrent mark sweep GC freed 71479(3MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.966ms total 201.573ms
,I/Mms_TXM_SVC( 7589): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7589): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3464): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8436): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8436): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 8436): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 8436): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 8436): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,I/art     ( 8459): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 8459): ThemeHelperretry to get Settings
,I/HwOUC   ( 8436): [Thread-129-129]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,E/HwSystemManager( 7162): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwOUC   ( 8436): [Thread-129-129]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/Process ( 8436): Sending signal. PID: 8436 SIG: 9
,I/HwSystemManager( 3954): HoldService:uid:10052 pid:8436 died
I/HwSystemManager( 3954): HoldService:oldVersionKey:10052,8436
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10052
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10052, pid: 8436
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10052, pid: 8436
,I/HwEmailTag( 8397): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 8397): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 8397): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 8397): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 8397): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 8397): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 8397): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 8397): EmailProvider->query->1450127812442;end;;consuming:1ms;
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 5
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 30078 firstTime = 92752 firstmBatteryCapacity =2203
,W/ArpVerifier( 3052): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,E/Thermal-daemon( 2330): [ap] temp_new :30  temp_old :31
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 33940 firstTime = 92752 firstmBatteryCapacity =2203
,I/art     ( 8459): System.exit called, status: 0
I/AndroidRuntime( 8459): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3954): HoldService:uid:10060 pid:8459 died
I/HwSystemManager( 3954): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3954): HoldService:oldVersionKey:10060,8459
E/HsmCoreServiceImpl( 3052): onTransact in code is: 102
I/MediaProcessHandler( 3052): processOp opType: 1, uid: 10060, pid: 8459
W/MediaProcessHandler( 3052): remove target not exist, maybe the UI process: uid: 10060, pid: 8459
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/ActivityManager( 3052): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/HwLauncher( 4110): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3575): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3575): hand message 1
I/TimeManager( 3575): notify time change. size = 2
,I/TimeLayout( 3575): time = 22:17
,I/TimeLayout( 3575): updateDate date = 12/14/2015
,I/TimeLayout( 3575): weekDay = Monday
,I/VacuumService( 4555): Vacuum at: now=1450127825783 tag=VacuumService
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3052): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 6422): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 4555): Scheduling Phenotype for one-off execution 7646 seconds from now (1450127826101)
,I/ActivityManager( 3052): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 4555): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4555): Using platform SSLCertificateSocketFactory
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 4555): core_booster, getBoosterConfig = false
,I/System  ( 4555): core_booster, getBoosterConfig = false
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2330): [charger_ic] temp_new :30  temp_old :31
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3052):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3052):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3052):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3052):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3052):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/HwSystemManager( 3954): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3954): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 3954): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3954): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3954): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3954): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3954): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3954): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3954): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1125511168 [332800000,437657600,542515200]
I/HwSystemManager( 3954): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3954): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,I/ClearcutLoggerApiImpl( 4555): disconnect managed GoogleApiClient
,I/ActivityManager( 3052): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/bluedroid( 5408): bt interface: [set_adapter_property]
I/bluedroid( 5408): bt interface: [set_adapter_property]
W/bt-btm  ( 5408): BTM_SetDiscoverability
,W/bt-btm  ( 5408): BTM_SetConnectability
W/bt-btif ( 5408): BTM_SetConnectability
I/BluetoothAdapterProperties( 5408): adapterPropertyChangedCallback with type:9 len:4
W/bt-btif ( 5408): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 5408): adapterPropertyChangedCallback with type:7 len:4
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 8
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2330): [ap] temp_new :29  temp_old :30
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 93937 firstTime = 92752 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 4110): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3575): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3575): hand message 1
I/TimeManager( 3575): notify time change. size = 2
,I/TimeLayout( 3575): time = 22:18
,I/TimeLayout( 3575): updateDate date = 12/14/2015
,I/TimeLayout( 3575): weekDay = Monday
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 11
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2330): [charger_ic] temp_new :29  temp_old :30
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 120318 firstTime = 92752 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 12
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 16
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3052): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=59 dispatchEvent: HEART-BEAT-ACK: 17
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 18
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/art     ( 3052): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,I/System  ( 3052): core_booster, getBoosterConfig = false
,I/System  ( 3052): core_booster, getBoosterConfig = false
,I/jxcore-log( 8287): Connected to the server!
I/jxcore-log( 8287): 
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 19
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 19
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 8287): --- start :testFindPeers.js---
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testFindPeers created [object Object]
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): serverPort is 8876
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT2060
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 8287): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 8287): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,I/art     ( 3052): Can not find class: Lcom/android/server/wifi/p2p/WifiP2pServiceImpl$ClientInfo;
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 8287): start: OK
,I/jxcore-log( 8287): StartBroadcasting started ok
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: RUNNING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 240637 firstTime = 92752 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 20
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=62 dispatchEvent: HEART-BEAT-ACK: 20
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/art     ( 3052): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 21
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=63 dispatchEvent: HEART-BEAT-ACK: 21
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 273933 firstTime = 92752 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 22
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=64 dispatchEvent: HEART-BEAT-ACK: 22
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/art     ( 3052): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 23
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=65 dispatchEvent: HEART-BEAT-ACK: 23
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 24
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=66 dispatchEvent: HEART-BEAT-ACK: 24
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 25
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=67 dispatchEvent: HEART-BEAT-ACK: 25
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 330880 firstTime = 92752 firstmBatteryCapacity =2203
,E/HwSystemManager( 3954): BgPowerManagerService: conusmPower = -1 result = -10 flag1 =false flag2 = false
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 0 firstTime = 426689 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 26
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 26
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 8287): --- start :testFindPeers.js---
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testFindPeers created [object Object]
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): serverPort is 8876
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): weAreDoneNow
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 8287): teardown
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testFindPeers stopped
I/jxcore-log( 8287): 
,I/io.jxcore.node.ConnectionHelper( 8287): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:492)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: NOT_INITIALIZED
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onServerStopped
I/jxcore-log( 8287): StopBroadcasting went ok
,I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: NOT_INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Socket is null
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 8287): --- start :testSendData.js---
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): daya100000
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): check server
I/jxcore-log( 8287): 
I/jxcore-log( 8287): serverPort is 47919
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT2060
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 8287): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 8287): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 8287): start: OK
,I/jxcore-log( 8287): StartBroadcasting started ok
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): null
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:22:15.849Z SendDataTCPServer.js: TCP/IP server is bound to port: 47919
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: RUNNING
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 27
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=69 dispatchEvent: HEART-BEAT-ACK: 27
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 28
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=70 dispatchEvent: HEART-BEAT-ACK: 28
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 8287): teardown
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testSendData stopped
I/jxcore-log( 8287): 
,I/io.jxcore.node.ConnectionHelper( 8287): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:492)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: NOT_INITIALIZED
,I/jxcore-log( 8287): StopBroadcasting went ok
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:22:40.994Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:22:41.000Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 8287): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Socket is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: NOT_INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 8287): --- start :testSendData.js---
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): daya100000
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): check server
I/jxcore-log( 8287): 
I/jxcore-log( 8287): serverPort is 46320
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: 58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT2060
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 8287): initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): verifyIdentityString: Identity string created: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 8287): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 8287): start: OK
,I/jxcore-log( 8287): StartBroadcasting started ok
I/jxcore-log( 8287): 
I/jxcore-log( 8287): null
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:22:41.029Z SendDataTCPServer.js: TCP/IP server is bound to port: 46320
I/jxcore-log( 8287): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: RUNNING
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 29
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=71 dispatchEvent: HEART-BEAT-ACK: 29
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 60001 firstTime = 426689 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 30
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=72 dispatchEvent: HEART-BEAT-ACK: 30
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 31
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=73 dispatchEvent: HEART-BEAT-ACK: 31
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 87187 firstTime = 426689 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 32
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=74 dispatchEvent: HEART-BEAT-ACK: 32
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 33
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=75 dispatchEvent: HEART-BEAT-ACK: 33
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 117263 firstTime = 426689 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 34
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=76 dispatchEvent: HEART-BEAT-ACK: 34
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 35
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=77 dispatchEvent: HEART-BEAT-ACK: 35
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 36
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=78 dispatchEvent: HEART-BEAT-ACK: 36
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 37
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=79 dispatchEvent: HEART-BEAT-ACK: 37
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 38
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=80 dispatchEvent: HEART-BEAT-ACK: 38
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 39
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=81 dispatchEvent: HEART-BEAT-ACK: 39
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 40
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=82 dispatchEvent: HEART-BEAT-ACK: 40
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 41
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=83 dispatchEvent: HEART-BEAT-ACK: 41
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/System.out( 3052): [ping, -c, 1, -w, 2, 192.168.1.1]
I/System.out( 3052): null
I/System.out( 3052): null
I/System.out( 3052): Calling by::className:com.android.server.wifi.ArpVerifier  MethodName:ping
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 42
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=84 dispatchEvent: HEART-BEAT-ACK: 42
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 43
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=85 dispatchEvent: HEART-BEAT-ACK: 43
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 44
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=86 dispatchEvent: HEART-BEAT-ACK: 44
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 45
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=87 dispatchEvent: HEART-BEAT-ACK: 45
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 46
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=88 dispatchEvent: HEART-BEAT-ACK: 46
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 47
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=89 dispatchEvent: HEART-BEAT-ACK: 47
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 48
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=90 dispatchEvent: HEART-BEAT-ACK: 48
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 49
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=91 dispatchEvent: HEART-BEAT-ACK: 49
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/System.out( 3052): [ping, -c, 1, -w, 2, 192.168.1.1]
I/System.out( 3052): null
I/System.out( 3052): null
I/System.out( 3052): Calling by::className:com.android.server.wifi.ArpVerifier  MethodName:ping
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 357909 firstTime = 426689 firstmBatteryCapacity =2204
E/HwSystemManager( 3954): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 50
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=92 dispatchEvent: HEART-BEAT-ACK: 50
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 51
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=93 dispatchEvent: HEART-BEAT-ACK: 51
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/System.out( 3052): [ping, -c, 1, -w, 2, 192.168.1.1]
I/System.out( 3052): null
I/System.out( 3052): null
I/System.out( 3052): Calling by::className:com.android.server.wifi.ArpVerifier  MethodName:ping
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 0 firstTime = 814671 firstmBatteryCapacity =2205
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 52
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=94 dispatchEvent: HEART-BEAT-ACK: 52
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 53
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=95 dispatchEvent: HEART-BEAT-ACK: 53
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 54
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=96 dispatchEvent: HEART-BEAT-ACK: 54
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 55
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=97 dispatchEvent: HEART-BEAT-ACK: 55
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 56
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=98 dispatchEvent: HEART-BEAT-ACK: 56
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 57
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=99 dispatchEvent: HEART-BEAT-ACK: 57
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/AGNSSCONTROL( 2708): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2708): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876964736
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2876994024
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2708): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2708): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
,E/Lss-gw  ( 2708): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1450128604590, wifi_time:1450127770188
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:1
W/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2708): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,E/Lss     ( 9364): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 9364): No reference location.
,W/Lss     ( 9364): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3235 bytes of data
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:851, gpsTime.gpsTOW23b:2047763, nTOWassist:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:46, iode3:46, m0:1283046838.000000, delta_n:12843.000000, ecc:129679509.000000, ek:0.000000, sqrt_a:2702019039.000000, omega_0:465641062.000000, i0:644012487.000000, omega:-1505850170.000000, omega_dot:-22411.000000, i_dot:966.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1623.000000, cus:6122.000000, crc:4811.000000, crs:-1842.000000, cic:-167.000000, cis:-149.000000, group_delay:-44.000000, af0:1283914.000000, af1:6.000000, af2:0.000000, aodc:46, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:15, iode3:15, m0:-2070487765.000000, delta_n:11489.000000, ecc:1974661.000000, ek:0.000000, sqrt_a:2701973762.000000, omega_0:488540403.000000, i0:658455635.000000, omega:-2058014428.000000, omega_dot:-21730.000000, i_dot:1011.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1289.000000, cus:5917.000000, crc:5358.000000, crs:-1535.000000, cic:8.000000, cis:-13.000000, group_delay:9.000000, af0:240963.000000, af1:57.000000, af2:0.000000, aodc:15, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:17
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:13, iode3:13, m0:-987530835.000000, delta_n:12784.000000, ecc:13983016.000000, ek:0.000000, sqrt_a:2701981115.000000, omega_0:-229198466.000000, i0:657436117.000000, omega:-1088528208.000000, omega_dot:-23373.000000, i_dot:-609.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2869.000000, cus:2299.000000, crc:9566.000000, crs:-3357.000000, cic:9.000000, cis:46.000000, group_delay:10.000000, af0:-34817.000000, af1:-13.000000, af2:0.000000, aodc:13, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:22
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:0, iode2:12, iode3:12, m0:-493419118.000000, delta_n:13769.000000, ecc:7808777.000000, ek:0.000000, sqrt_a:2702011083.000000, omega_0:1203206901.000000, i0:655546504.000000, omega:-2022183934.000000, omega_dot:-22803.000000, i_dot:1090.000000
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:687.000000, cus:3570.000000, crc:7981.000000, crs:788.000000, cic:29.000000, cis:10.000000, group_delay:7.000000, af0:91197.000000, af1:48.000000, af2:0.000000, aodc:12, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:94, iode3:94, m0:170948925.000000, delta_n:11573.000000, ecc:48200511.000000, ek:0.000000, sqrt_a:2701949933.000000, omega_0:-907499047.000000, i0:676734639.000000, omega:436914716.000000, omega_dot:-22953.000000, i_dot:282.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1408.000000, cus:1190.000000, crc:11244.000000, crs:1613.000000, cic:33.000000, cis:72.000000, group_delay:-27.000000, af0:758743.000000, af1:26.000000, af2:0.000000, aodc:94, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:2, iode3:2, m0:-1946484282.000000, delta_n:12811.000000, ecc:71495742.000000, ek:0.000000, sqrt_a:2702020106.000000, omega_0:1973938814.000000, i0:659868583.000000, omega:-1330777056.000000, omega_dot:-21958.000000, i_dot:-1449.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-128.000000, cus:4505.000000, crc:6961.000000, crs:-194.000000, cic:102.000000, cis:-30.000000, group_delay:-20.000000, af0:33205.000000, af1:-21.000000, af2:0.000000, aodc:2, health:0, toc:10349, toe:10349, status:0, code_on_L2:1, fit_interval_flag:0, aodo:8
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:73, iode3:73, m0:-1233334081.000000, delta_n:11311.000000, ecc:71054110.000000, ek:0.000000, sqrt_a:2702007678.000000, omega_0:-894682771.000000, i0:677096273.000000, omega:214397260.000000, omega_dot:-22606.000000, i_dot:742.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1560.000000, cus:1435.000000, crc:11039.000000, crs:1820.000000, cic:1.000000, cis:-66.000000, group_delay:-22.000000, af0:-123187.000000, af1:30.000000, af2:0.000000, aodc:73, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:15, iode3:15, m0:-846157894.000000, delta_n:16185.000000, ecc:141004020.000000, ek:0.000000, sqrt_a:2701991772.000000, omega_0:1187434093.000000, i0:631946987.000000, omega:-1316006789.000000, omega_dot:-24261.000000, i_dot:1060.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1097.000000, cus:3293.000000, crc:7725.000000, crs:1026.000000, cic:83.000000, cis:238.000000, group_delay:-24.000000, af0:993697.000000, af1:33.000000, af2:0.000000, aodc:15, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:30, iode3:30, m0:1895536449.000000, delta_n:15911.000000, ecc:43164676.000000, ek:0.000000, sqrt_a:2702006247.000000, omega_0:1151834910.000000, i0:632786742.000000, omega:885746962.000000, omega_dot:-23758.000000, i_dot:1117.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:858.000000, cus:3386.000000, crc:7667.000000, crs:1058.000000, cic:18.000000, cis:-19.000000, group_delay:-18.000000, af0:812533.000000, af1:24.000000, af2:0.000000, aodc:30, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:82, iode3:82, m0:-1220765359.000000, delta_n:16013.000000, ecc:64249666.000000, ek:0.000000, sqrt_a:2702759725.000000, omega_0:1187985613.000000, i0:630471170.000000, omega:-1387195752.000000, omega_dot:-23722.000000, i_dot:1259.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:856.000000, cus:3279.000000, crc:7586.000000, crs:965.000000, cic:101.000000, cis:10.000000, group_delay:-38.000000, af0:901289.000000, af1:33.000000, af2:0.000000, aodc:82, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:39, iode3:39, m0:1121168255.000000, delta_n:12816.000000, ecc:33620464.000000, ek:0.000000, sqrt_a:2701997181.000000, omega_0:-1671300514.000000, i0:650455424.000000, omega:209755460.000000, omega_dot:-22535.000000, i_dot:-491.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2617.000000, cus:5418.000000, crc:5745.000000, crs:2941.000000, cic:20.000000, cis:58.000000, group_delay:6.000000, af0:-20019.000000, af1:-5.000000, af2:0.000000, aodc:39, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:24
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:54, iode3:54, m0:-478701526.000000, delta_n:13115.000000, ecc:4575978.000000, ek:0.000000, sqrt_a:2702011356.000000, omega_0:-945158806.000000, i0:656504041.000000, omega:-209322664.000000, omega_dot:-23610.000000, i_dot:431.000000
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2050.000000, cus:1464.000000, crc:10522.000000, crs:2353.000000, cic:3.000000, cis:-42.000000, group_delay:16.000000, af0:-355335.000000, af1:-153.000000, af2:0.000000, aodc:54, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:20, iode3:20, m0:-1385670745.000000, delta_n:10871.000000, ecc:172028462.000000, ek:0.000000, sqrt_a:2702024984.000000, omega_0:-891164878.000000, i0:676185357.000000, omega:-1120848880.000000, omega_dot:-21828.000000, i_dot:405.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1484.000000, cus:1082.000000, crc:11321.000000, crs:1559.000000, cic:167.000000, cis:87.000000, group_delay:-24.000000, af0:1048604.000000, af1:23.000000, af2:0.000000, aodc:20, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:22, iode3:22, m0:416854379.000000, delta_n:12502.000000, ecc:14109497.000000, ek:0.000000, sqrt_a:2702006062.000000, omega_0:-1609229214.000000, i0:652230853.000000, omega:2140121494.000000, omega_dot:-22457.000000, i_dot:-338.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2285.000000, cus:5357.000000, crc:5784.000000, crs:2649.000000, cic:-4.000000, cis:-1.000000, group_delay:7.000000, af0:152432.000000, af1:46.000000, af2:0.000000, aodc:22, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:44, iode3:44, m0:722891704.000000, delta_n:14757.000000, ecc:97574042.000000, ek:0.000000, sqrt_a:2701988698.000000, omega_0:1260268564.000000, i0:646884256.000000, omega:133267123.000000, omega_dot:-23432.000000, i_dot:567.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:665.000000, cus:3360.000000, crc:8107.000000, crs:791.000000, cic:10.000000, cis:96.000000, group_delay:-7.000000, af0:103122.000000, af1:105.000000, af2:0.000000, aodc:44, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 83
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:18, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
,W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
,I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
,I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 58
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=100 dispatchEvent: HEART-BEAT-ACK: 58
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 59
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=101 dispatchEvent: HEART-BEAT-ACK: 59
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 60
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=102 dispatchEvent: HEART-BEAT-ACK: 60
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 61
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=103 dispatchEvent: HEART-BEAT-ACK: 61
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 62
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=104 dispatchEvent: HEART-BEAT-ACK: 62
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 63
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=105 dispatchEvent: HEART-BEAT-ACK: 63
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 180478 firstTime = 814671 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 64
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=106 dispatchEvent: HEART-BEAT-ACK: 64
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 65
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=107 dispatchEvent: HEART-BEAT-ACK: 65
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 210568 firstTime = 814671 firstmBatteryCapacity =2205
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 66
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=108 dispatchEvent: HEART-BEAT-ACK: 66
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 67
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=109 dispatchEvent: HEART-BEAT-ACK: 67
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 68
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=110 dispatchEvent: HEART-BEAT-ACK: 68
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 69
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=111 dispatchEvent: HEART-BEAT-ACK: 69
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 70
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=112 dispatchEvent: HEART-BEAT-ACK: 70
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 71
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=113 dispatchEvent: HEART-BEAT-ACK: 71
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 72
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=114 dispatchEvent: HEART-BEAT-ACK: 72
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 73
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=115 dispatchEvent: HEART-BEAT-ACK: 73
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 74
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=116 dispatchEvent: HEART-BEAT-ACK: 74
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 75
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=117 dispatchEvent: HEART-BEAT-ACK: 75
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 76
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=118 dispatchEvent: HEART-BEAT-ACK: 76
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 77
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=119 dispatchEvent: HEART-BEAT-ACK: 77
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 392022 firstTime = 814671 firstmBatteryCapacity =2205
E/HwSystemManager( 3954): BgPowerManagerService: conusmPower = 1 result = 9 flag1 =false flag2 = false
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 78
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=120 dispatchEvent: HEART-BEAT-ACK: 78
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 79
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=121 dispatchEvent: HEART-BEAT-ACK: 79
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 0 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 80
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=122 dispatchEvent: HEART-BEAT-ACK: 80
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 81
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=123 dispatchEvent: HEART-BEAT-ACK: 81
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 82
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=124 dispatchEvent: HEART-BEAT-ACK: 82
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 83
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=125 dispatchEvent: HEART-BEAT-ACK: 83
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 60158 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 84
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=126 dispatchEvent: HEART-BEAT-ACK: 84
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 85
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=127 dispatchEvent: HEART-BEAT-ACK: 85
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 90235 firstTime = 1235785 firstmBatteryCapacity =2204
,I/jxcore-log( 8287): timeout now
I/jxcore-log( 8287): 
I/jxcore-log( 8287): weAreDoneNow
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 86
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=128 dispatchEvent: HEART-BEAT-ACK: 86
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 87
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=129 dispatchEvent: HEART-BEAT-ACK: 87
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 120320 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 88
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=130 dispatchEvent: HEART-BEAT-ACK: 88
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 89
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=131 dispatchEvent: HEART-BEAT-ACK: 89
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 150409 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 90
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=132 dispatchEvent: HEART-BEAT-ACK: 90
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 91
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=133 dispatchEvent: HEART-BEAT-ACK: 91
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 92
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=134 dispatchEvent: HEART-BEAT-ACK: 92
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 93
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=135 dispatchEvent: HEART-BEAT-ACK: 93
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 210573 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 94
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=136 dispatchEvent: HEART-BEAT-ACK: 94
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/jxcore-log( 8287): timeout now
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): weAreDoneNow, resultArray.length: 0
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): sendReportNow
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:39:21.055Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 8287): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 95
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=137 dispatchEvent: HEART-BEAT-ACK: 95
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 240633 firstTime = 1235785 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 96
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=138 dispatchEvent: HEART-BEAT-ACK: 96
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): start: {"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): start: Identity string: "{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2060","ra":"58:2A:F7:ED:96:BE"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 8287): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Failed to add local service, got error code: 0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 97
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=139 dispatchEvent: HEART-BEAT-ACK: 97
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 98
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=140 dispatchEvent: HEART-BEAT-ACK: 98
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): start: Starting peer discovery...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to startListeningForIncomingConnections peer discovery, got error code: 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 99
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=141 dispatchEvent: HEART-BEAT-ACK: 99
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 8287): server initiated timeout
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): testSendData stopped
I/jxcore-log( 8287): 
,I/io.jxcore.node.ConnectionHelper( 8287): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 8287): stop: Stopping services
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:492)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 8287): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 8287): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): setState: NOT_INITIALIZED
I/jxcore-log( 8287): StopBroadcasting went ok
I/jxcore-log( 8287): 
I/jxcore-log( 8287): sendReportNow
I/jxcore-log( 8287): 
I/jxcore-log( 8287): done, now sending data to server
I/jxcore-log( 8287): 
,I/jxcore-log( 8287): 2015-12-14T21:40:26.830Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 8287): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 8287): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 8287): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 8287): onConnectionManagerStateChanged: NOT_INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 8287): Failed to shutdown peer discovery, got error code: 0
,I/chromium( 8287): [INFO:CONSOLE(63)] "logCallback server initiated timeout", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 100
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=142 dispatchEvent: HEART-BEAT-ACK: 100
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 101
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=143 dispatchEvent: HEART-BEAT-ACK: 101
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 102
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=144 dispatchEvent: HEART-BEAT-ACK: 102
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 103
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=145 dispatchEvent: HEART-BEAT-ACK: 103
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/OAM     ( 2704): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2704): [rename_old_file:107]rename_old_file
I/OAM     ( 2704): 
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 104
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=146 dispatchEvent: HEART-BEAT-ACK: 104
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 105
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=147 dispatchEvent: HEART-BEAT-ACK: 105
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 106
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=148 dispatchEvent: HEART-BEAT-ACK: 106
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 107
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=149 dispatchEvent: HEART-BEAT-ACK: 107
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 108
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=150 dispatchEvent: HEART-BEAT-ACK: 108
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 109
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=151 dispatchEvent: HEART-BEAT-ACK: 109
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2330): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 110
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=152 dispatchEvent: HEART-BEAT-ACK: 110
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2330): [ap] temp_new :29  temp_old :28
,E/Thermal-daemon( 2330): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 111
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=153 dispatchEvent: HEART-BEAT-ACK: 111
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 112
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=154 dispatchEvent: HEART-BEAT-ACK: 112
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 113
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=155 dispatchEvent: HEART-BEAT-ACK: 113
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 510901 firstTime = 1235785 firstmBatteryCapacity =2204
E/HwSystemManager( 3954): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 114
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=156 dispatchEvent: HEART-BEAT-ACK: 114
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 115
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=157 dispatchEvent: HEART-BEAT-ACK: 115
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/HI110X_CHR_LOGD( 2705): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 0 firstTime = 1777242 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 116
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=158 dispatchEvent: HEART-BEAT-ACK: 116
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 117
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=159 dispatchEvent: HEART-BEAT-ACK: 117
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3954): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3954): BgPowerManagerService: mTimes = 29435 firstTime = 1777242 firstmBatteryCapacity =2204
,I/AGNSSCONTROL( 2708): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2708): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876994024
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2877004952
I/AGNSSCONTROL( 2708): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2708): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2708): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2708): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1450129504591, wifi_time:1450127770188
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:1
W/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 678: WIFI MAC ADDRESS COUNT LESS THAN 2
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:0
I/AGNSSCONTROL( 2708): int MyLssGwCommunicator::sendRequestWithGeranCellId(EPH_TYPE, int, int, int, int, bool) -- 53: sendRequestWithGeranCellId called, mcc:-1, mnc:-1, lac:0, ci:0
,E/Lss     (10143): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     (10143): No reference location.
W/Lss     (10143): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3235 bytes of data
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:851, gpsTime.gpsTOW23b:2059013, nTOWassist:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:46, iode3:46, m0:1283046838.000000, delta_n:12843.000000, ecc:129679509.000000, ek:0.000000, sqrt_a:2702019039.000000, omega_0:465641062.000000, i0:644012487.000000, omega:-1505850170.000000, omega_dot:-22411.000000, i_dot:966.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1623.000000, cus:6122.000000, crc:4811.000000, crs:-1842.000000, cic:-167.000000, cis:-149.000000, group_delay:-44.000000, af0:1283914.000000, af1:6.000000, af2:0.000000, aodc:46, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:15, iode3:15, m0:-2070487765.000000, delta_n:11489.000000, ecc:1974661.000000, ek:0.000000, sqrt_a:2701973762.000000, omega_0:488540403.000000, i0:658455635.000000, omega:-2058014428.000000, omega_dot:-21730.000000, i_dot:1011.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1289.000000, cus:5917.000000, crc:5358.000000, crs:-1535.000000, cic:8.000000, cis:-13.000000, group_delay:9.000000, af0:240963.000000, af1:57.000000, af2:0.000000, aodc:15, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:17
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:13, iode3:13, m0:-987530835.000000, delta_n:12784.000000, ecc:13983016.000000, ek:0.000000, sqrt_a:2701981115.000000, omega_0:-229198466.000000, i0:657436117.000000, omega:-1088528208.000000, omega_dot:-23373.000000, i_dot:-609.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2869.000000, cus:2299.000000, crc:9566.000000, crs:-3357.000000, cic:9.000000, cis:46.000000, group_delay:10.000000, af0:-34817.000000, af1:-13.000000, af2:0.000000, aodc:13, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:22
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:0, iode2:12, iode3:12, m0:-493419118.000000, delta_n:13769.000000, ecc:7808777.000000, ek:0.000000, sqrt_a:2702011083.000000, omega_0:1203206901.000000, i0:655546504.000000, omega:-2022183934.000000, omega_dot:-22803.000000, i_dot:1090.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:687.000000, cus:3570.000000, crc:7981.000000, crs:788.000000, cic:29.000000, cis:10.000000, group_delay:7.000000, af0:91197.000000, af1:48.000000, af2:0.000000, aodc:12, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:94, iode3:94, m0:170948925.000000, delta_n:11573.000000, ecc:48200511.000000, ek:0.000000, sqrt_a:2701949933.000000, omega_0:-907499047.000000, i0:676734639.000000, omega:436914716.000000, omega_dot:-22953.000000, i_dot:282.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1408.000000, cus:1190.000000, crc:11244.000000, crs:1613.000000, cic:33.000000, cis:72.000000, group_delay:-27.000000, af0:758743.000000, af1:26.000000, af2:0.000000, aodc:94, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:2, iode3:2, m0:-1946484282.000000, delta_n:12811.000000, ecc:71495742.000000, ek:0.000000, sqrt_a:2702020106.000000, omega_0:1973938814.000000, i0:659868583.000000, omega:-1330777056.000000, omega_dot:-21958.000000, i_dot:-1449.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-128.000000, cus:4505.000000, crc:6961.000000, crs:-194.000000, cic:102.000000, cis:-30.000000, group_delay:-20.000000, af0:33205.000000, af1:-21.000000, af2:0.000000, aodc:2, health:0, toc:10349, toe:10349, status:0, code_on_L2:1, fit_interval_flag:0, aodo:8
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:73, iode3:73, m0:-1233334081.000000, delta_n:11311.000000, ecc:71054110.000000, ek:0.000000, sqrt_a:2702007678.000000, omega_0:-894682771.000000, i0:677096273.000000, omega:214397260.000000, omega_dot:-22606.000000, i_dot:742.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1560.000000, cus:1435.000000, crc:11039.000000, crs:1820.000000, cic:1.000000, cis:-66.000000, group_delay:-22.000000, af0:-123187.000000, af1:30.000000, af2:0.000000, aodc:73, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:15, iode3:15, m0:-846157894.000000, delta_n:16185.000000, ecc:141004020.000000, ek:0.000000, sqrt_a:2701991772.000000, omega_0:1187434093.000000, i0:631946987.000000, omega:-1316006789.000000, omega_dot:-24261.000000, i_dot:1060.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1097.000000, cus:3293.000000, crc:7725.000000, crs:1026.000000, cic:83.000000, cis:238.000000, group_delay:-24.000000, af0:993697.000000, af1:33.000000, af2:0.000000, aodc:15, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:30, iode3:30, m0:1895536449.000000, delta_n:15911.000000, ecc:43164676.000000, ek:0.000000, sqrt_a:2702006247.000000, omega_0:1151834910.000000, i0:632786742.000000, omega:885746962.000000, omega_dot:-23758.000000, i_dot:1117.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:858.000000, cus:3386.000000, crc:7667.000000, crs:1058.000000, cic:18.000000, cis:-19.000000, group_delay:-18.000000, af0:812533.000000, af1:24.000000, af2:0.000000, aodc:30, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:82, iode3:82, m0:-1220765359.000000, delta_n:16013.000000, ecc:64249666.000000, ek:0.000000, sqrt_a:2702759725.000000, omega_0:1187985613.000000, i0:630471170.000000, omega:-1387195752.000000, omega_dot:-23722.000000, i_dot:1259.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:856.000000, cus:3279.000000, crc:7586.000000, crs:965.000000, cic:101.000000, cis:10.000000, group_delay:-38.000000, af0:901289.000000, af1:33.000000, af2:0.000000, aodc:82, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:39, iode3:39, m0:1121168255.000000, delta_n:12816.000000, ecc:33620464.000000, ek:0.000000, sqrt_a:2701997181.000000, omega_0:-1671300514.000000, i0:650455424.000000, omega:209755460.000000, omega_dot:-22535.000000, i_dot:-491.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2617.000000, cus:5418.000000, crc:5745.000000, crs:2941.000000, cic:20.000000, cis:58.000000, group_delay:6.000000, af0:-20019.000000, af1:-5.000000, af2:0.000000, aodc:39, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:24
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:54, iode3:54, m0:-478701526.000000, delta_n:13115.000000, ecc:4575978.000000, ek:0.000000, sqrt_a:2702011356.000000, omega_0:-945158806.000000, i0:656504041.000000, omega:-209322664.000000, omega_dot:-23610.000000, i_dot:431.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2050.000000, cus:1464.000000, crc:10522.000000, crs:2353.000000, cic:3.000000, cis:-42.000000, group_delay:16.000000, af0:-355335.000000, af1:-153.000000, af2:0.000000, aodc:54, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:20, iode3:20, m0:-1385670745.000000, delta_n:10871.000000, ecc:172028462.000000, ek:0.000000, sqrt_a:2702024984.000000, omega_0:-891164878.000000, i0:676185357.000000, omega:-1120848880.000000, omega_dot:-21828.000000, i_dot:405.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:1484.000000, cus:1082.000000, crc:11321.000000, crs:1559.000000, cic:167.000000, cis:87.000000, group_delay:-24.000000, af0:1048604.000000, af1:23.000000, af2:0.000000, aodc:20, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:22, iode3:22, m0:416854379.000000, delta_n:12502.000000, ecc:14109497.000000, ek:0.000000, sqrt_a:2702006062.000000, omega_0:-1609229214.000000, i0:652230853.000000, omega:2140121494.000000, omega_dot:-22457.000000, i_dot:-338.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2285.000000, cus:5357.000000, crc:5784.000000, crs:2649.000000, cic:-4.000000, cis:-1.000000, group_delay:7.000000, af0:152432.000000, af1:46.000000, af2:0.000000, aodc:22, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:44, iode3:44, m0:722891704.000000, delta_n:14757.000000, ecc:97574042.000000, ek:0.000000, sqrt_a:2701988698.000000, omega_0:1260268564.000000, i0:646884256.000000, omega:133267123.000000, omega_dot:-23432.000000, i_dot:567.000000
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:665.000000, cus:3360.000000, crc:8107.000000, crs:791.000000, cic:10.000000, cis:96.000000, group_delay:-7.000000, af0:103122.000000, af1:105.000000, af2:0.000000, aodc:44, health:0, toc:10350, toe:10350, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 83
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2708): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 107680
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:18, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:3, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1776: ganss inject rti
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2708): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2708): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2708): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 118
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=160 dispatchEvent: HEART-BEAT-ACK: 118
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/art     ( 3052): Can not find class: Lcom/android/server/AppOpsService$1$1;
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 119
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=161 dispatchEvent: HEART-BEAT-ACK: 119
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 120
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=162 dispatchEvent: HEART-BEAT-ACK: 120
E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/ActivityManager( 3052): filter receiver for action = com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS
,I/art     ( 3052): Can not find class: Lcom/android/server/am/ActivityManagerService$24;
,I/art     ( 3052): Can not find class: Lcom/android/server/am/ProcessStatsService$2;
,I/HwLauncher( 4110): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3575): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3575): hand message 1
I/TimeManager( 3575): notify time change. size = 2
I/TimeLayout( 3575): time = 22:45
,I/TimeLayout( 3575): updateDate date = 12/14/2015
,I/TimeLayout( 3575): weekDay = Monday
,I/HwSystemManager( 3954): aor:Network Stats Updated
I/HwSystemManager( 3954): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 3052): Can not find class: Lcom/android/server/pm/PackageManagerService$PackageUsage$1;
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3954): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3954): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3954): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3954): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3954): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/EventLogService( 6422): Aggregate from 1450127755143 (log), 1450127755143 (data)
,I/PG Utils( 6422): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 4555): core_booster, getBoosterConfig = false
,I/System  ( 4555): core_booster, getBoosterConfig = false
I/System  ( 4555): core_booster, getBoosterConfig = false
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 121
E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=163 dispatchEvent: HEART-BEAT-ACK: 121
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/PG Utils( 4555): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6422): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2330): [ap] temp_new :29  temp_old :28
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 122
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=164 dispatchEvent: HEART-BEAT-ACK: 122
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2330): [ap] temp_new :28  temp_old :29
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 123
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=165 dispatchEvent: HEART-BEAT-ACK: 123
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3588): wlan0: HEART-BEAT-ACK: 124
,E/WifiMonitor( 3052): WifiMonitor:wlan0 cnt=166 dispatchEvent: HEART-BEAT-ACK: 124
,E/WifiStateMachine( 3052):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3052):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3052):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3052):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3052):  SupplicantStartedState what:147506 0 0
,TIME-OUT KILL (timeout was 1800000ms)
```
