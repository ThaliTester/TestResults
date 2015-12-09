#### Test 50650278d0426ce_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
I/appproc ( 7435): CLASSPATH=/system/framework/am.jar
I/appproc ( 7435): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 7435): app_process:number,5,0
I/AndroidRuntime( 7435): readDownloadBoosterConfig: 'false'
I/        ( 7435): power log dlsym ok
E/android_hardware_fm.cpp( 7435): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 7435): ========64bit long size = 8
E/FM_HAL  ( 7435): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 7435): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 7435): 
I/fm_hisi ( 7435): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 7435): 
I/fm_hisi ( 7435): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 7435): 
E/android_hardware_fm.cpp( 7435): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2929): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2929): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2929): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2929): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 3468): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3468): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3682): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3682): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3682): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3468): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3682): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3682): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/WebViewFactory( 7454): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 7454): Loading: webviewchromium
I/LibraryLoader( 7454): Time to load native libraries: 45 ms (timestamps 8051-8096)
I/LibraryLoader( 7454): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 7454): Expected native library version number "",actual native library version number ""
I/chromium( 7454): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7454): Initializing chromium process, renderers=0
W/art     ( 7454): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7454): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7454): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 7454): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 7454): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7454): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 7454): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 7454): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7454): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 7454): Can not find class: Landroid/widget/ViewStub;
I/art     ( 7454): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 7454): Can not find class: Landroid/app/ViewStub;
W/art     ( 7454): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7454): Attempt to remove local handle scope entry from IRT, ignoring
I/PhoneStatusBar( 3209): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3209): shouldTranslucent:true
I/PhoneStatusBar( 3209): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/OpenGLRenderer( 7454): Initialized EGL, version 1.4
,I/ActivityManager( 2929): Displayed com.test.thalitest/.MainActivity: +1s49ms (total +1s119ms)
,W/IInputConnectionWrapper( 7454): showStatusIcon on inactive InputConnection
,I/chromium( 7454): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7454): 
,I/art     ( 5913): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,W/jxcore-log( 7454): Initializing JXcore engine
W/jxcore-log( 7454): JXcore engine is ready
,W/jxcore-log( 7454): Starting JXcore engine
,W/jxcore-log( 7454): Platform android
W/jxcore-log( 7454): 
W/jxcore-log( 7454): Process ARCH arm
W/jxcore-log( 7454): 
,I/art     ( 2929): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 7454): JXcore Cordova bridge is ready!
I/jxcore-log( 7454): 
W/jxcore-log( 7454): JXcore engine is started
,I/jxcore-log( 7454): Toggling radios to true
I/jxcore-log( 7454): 
,I/HwSystemManager( 3468): HoldService:checkBeforeShowDialog: uid:10295 pid:7454, permissionType:2097152
I/HwSystemManager( 3468): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2929): allowOpenWifi blocked:false
,E/WifiStateMachine( 2929):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 2929): [111,173,779 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
I/jxcore-log( 7454): Radios toggled
I/jxcore-log( 7454): 
I/wpa_supplicant( 3274): set current WIFI status to BT!
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3274): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 3274): check_associate_result func start
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2929): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/System.err( 2929): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2929): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 2929): This is not beta user build
,E/WifiMonitor( 2929): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,W/wpa_supplicant( 3274): STA MODE: Set shutdown wlan cmd SUCCESS
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/wpa_supplicant( 3274): check_associate_result func start
,I/wpa_supplicant( 3274): set current WIFI status to BT!
E/WifiStateMachine( 2929): WifiStateMachine: Leaving Connected state
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
E/WifiStateMachine( 2929): setScanAlarm false period 20000 initial delay 0
,I/bluetooth-coex( 4724): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
E/WifiStateMachine( 2929): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2929): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/native  ( 2929): do suspend true
,I/wpa_supplicant( 3274): set current WIFI status to BT!
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = com.google.android.gcm.DISCONNECTED
,E/ArpVerifier( 2929): current SSID is empty.
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 2929):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
E/WifiStateMachine( 2929): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 2929):  DisconnectingState CMD_RECONNECT 0 0
,E/WifiStateMachine( 2929):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 2929): [111,306,148 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
,W/wpa_supplicant( 3274): check_associate_result func start
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 3274): wlan is down..., now start up...
I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,E/WifiStateMachine( 2929):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=111327
,E/WifiStateMachine( 2929):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=111328
,E/native  ( 2929): do suspend true
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =1
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,W/wpa_supplicant( 3274): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4724): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4724): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3274): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2929): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2929): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3274): set current WIFI status to BT!
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/art     ( 2929): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,E/WifiStateMachine( 2929):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
E/WifiStateMachine( 2929): setScanAlarm true period 0 initial delay 200
,E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=112094  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=112095  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 2929):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2929):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2929):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=112115  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=112122  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 2929): handleEvent 12  CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2929): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=34 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 2929): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
E/WifiStateMachine( 2929):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:280 bcn=0
E/WifiStateMachine( 2929):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:280 bcn=0
I/wpa_supplicant( 3274): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 2929):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:280 bcn=0
E/WifiStateMachine( 2929):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 dur:280 bcn=0
E/WifiStateMachine( 2929): [1,449,681,182,322 ms] noteScanEnd no scan source
W/wpa_supplicant( 3274): check_associate_result func start
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 4724): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 4724): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiStateMachine( 2929): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3448e936 sup_state=SCANNING debouncing=false
,E/WifiAutoJoinController ( 2929): NG700 c0:ff:d4:d3:aa:48 rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 2929): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-87 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS] is not scored
E/WifiAutoJoinController ( 2929): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 2929): ageScanResultsOut delay 40000 size 3 now 1449681182329
E/WifiAutoJoinController ( 2929): newSupplicantResults size=3 known=1 true
,E/WifiAutoJoinController ( 2929): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController ( 2929): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2929): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2929): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
E/WifiAutoJoinController ( 2929): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
,E/WifiStateMachine( 2929):  DisconnectedState CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112788
,E/WifiStateMachine( 2929):  ConnectModeState CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112789
E/WifiStateMachine( 2929):  DriverStartedState CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112789
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112789
E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112790  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=112795  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,W/wpa_supplicant( 3274): check_associate_result func start
I/wpa_supplicant( 3274): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=113429  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=113430  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 2929): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72 SSID=0x
,E/WifiStateMachine( 2929):  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=113443
E/WifiStateMachine( 2929):  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=113443
E/WifiStateMachine( 2929):  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=113443
E/WifiStateMachine( 2929):  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=113444
,E/WifiStateMachine( 2929):  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=113444
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,W/wpa_supplicant( 3274): check_associate_result func start
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=113463  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=113469  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/wpa_supplicant( 3274): check_associate_result func start
,W/wpa_supplicant( 3274): check_associate_result func start
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 3274): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 2929): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/HI110X_CHR_LOGD( 2664): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
I/wpa_supplicant( 3274): set current WIFI status to BT!
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/wpa_supplicant( 3274): set current WIFI status to BT!
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 2929): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3274): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
W/wpa_supplicant( 3274): check_associate_result func start
E/WifiStateMachine( 2929):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=113478  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 2929): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=113479  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 2929):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113480
E/WifiStateMachine( 2929):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113480
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,W/System.err( 2929): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2929): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2929): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 2929): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 2929): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
,W/System.err( 2929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2929): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2929): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 2929): This is not beta user build
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE,
E/WifiStateMachine( 2929): setScanAlarm false period 0 initial delay 0
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2929): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2929): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 2929): obtaining wifi is conencted
,I/WiFi_PRO( 2929): obtaining wifi is conencted
,E/WifiStateMachine( 2929): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 2929): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,E/WifiStateMachine( 2929): Start Dhcp Watchdog 2
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/WifiStateMachine( 2929):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=113526  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 2929):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=113527  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 2929):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=113527  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 2929):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
,E/native  ( 2929): do suspend false
,E/WifiStateMachine( 2929): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 2929): noteBatchedScanstop()
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,I/DHCPCD  ( 7534): version 5.5.6 starting
,W/DHCPCD  ( 7534): hw_parse_xidfile 
I/DHCPCD  ( 7534): wlan0: dhcp start reboot
I/DHCPCD  ( 7534): wlan0: rebinding lease of 192.168.1.120
,W/ArpVerifier( 2929): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3659): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/SUPL20_SCM( 3659): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
,E/GpsLocationProvider( 2929): No APN found to select.
,W/GNSS_ADAPTER( 2929): This function not used.
,W/GNSS_ADAPTER( 2929): This function not used.
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 2929): No APN found to select.
,W/GNSS_ADAPTER( 2929): This function not used.
W/GNSS_ADAPTER( 2929): This function not used.
,I/HwEmailTag( 7541): MailAppProvider->onCreate->begin, consuming 1449681184732ms->-prefixstartupperformance-
,I/HwEmailTag( 7541): MailAppProvider->onCreate->end, consuming 1449681184756ms->-prefixstartupperformance-
,I/HwCust  ( 7541): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 7541): Constructor found for class com.android.email.HwCustUtilityImpl
,I/DHCPCD  ( 7534): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,I/HwCust  ( 7541): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 7541): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 7541): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7541): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7541): HwUtils->initStaticVarsAsync
I/HwEmailTag( 7541): HwUtils->initStaticVarsAsync
,I/HwCust  ( 7541): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7541): EmailContent->init->consuming:16ms->;-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 7541): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 7541): EmailProvider->onCreate->end, consuming 29ms->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailProvider->onCreate->end, consuming 30ms->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailProvider->resetVisibleLimits->start:1449681184811 ->-prefixstartupperformance-
I/HwEmailTag( 7541): EmailProvider->resetVisibleLimits->start:1449681184812 ->-prefixstartupperformance-
,I/HwCust  ( 7541): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 7541): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7541): EmailApplication->onCreate->begin, consuming 48ms->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwCust  ( 7541): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 7541): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
I/HwEmailTag( 7541): HwUtils->initStaticVarsAsync->run:consuming:49ms; bidiFormatter:android.support.v4.text.BidiFormatter@124168d3;accountsProjSize:42
,I/HwEmailTag( 7541): HwUtils->initStaticVarsAsync->run:consuming:50ms; bidiFormatter:android.support.v4.text.BidiFormatter@124168d3;accountsProjSize:42
,I/HwEmailTag( 7541): EmailApplication->onCreate->end, consuming 55ms->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7541): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7541): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 27ms.
I/HwEmailTag( 7541): EmailProvider->notifyNetworkChanged->
,I/HwEmailTag( 7541): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7541): EmailProvider->initBuildCache->start->1449681184888->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 7541): EmailProvider->initBuildCache->start->1449681184888; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 7541): EmailProvider->uiAccounts->start:1449681184890
,I/HwEmailTag( 7541): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7541): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 12ms.
,I/HwEmailTag( 7541): DBHelper->onOpen-> EmailProvider.db
,I/DHCPCD  ( 7534): wlan0: checking for 192.168.1.120
,I/HwEmailTag( 7541): EmailProvider->resetVisibleLimits->getDatabase, consuming:127ms;-prefixstartupperformance-
I/HwEmailTag( 7541): EmailProvider->resetVisibleLimits->getDatabase, consuming:126ms;-prefixstartupperformance-
I/HwEmailTag( 7541): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 7541): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7541): EmailProvider->uiAccounts->start:1449681184890;end,consuming:51
,I/HwEmailTag( 7541): EmailProvider->query->1449681184810;end;;consuming:132ms;
,I/DownloadManager( 3237): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwSystemManager( 3468): HoldService:uid:10050 pid:7158 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10050,7158
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10050
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10050, pid: 7158
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10050, pid: 7158
,I/HwCust  ( 6913): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwCust  ( 6913): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/MagazineUtils( 3142): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 6913): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 6913): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 2929): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2929): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/art     ( 2929): Explicit concurrent mark sweep GC freed 61070(3MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 2.137ms total 193.818ms
,E/HwOUC   ( 7573): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7573): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7573): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 7573): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7573): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7573): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7573): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7573): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 3468): HoldService:uid:10001 pid:6844 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10001,6844
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10001, pid: 6844
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10001, pid: 6844
,W/asset   ( 7600): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 7600): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/DHCPCD  ( 7534): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 226us total 25.063ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 314us total 22.831ms
,I/HwSystemManager( 3468): HoldService:uid:10004 pid:6148 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10004,6148
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10004
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10004, pid: 6148
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10004, pid: 6148
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 240us total 25.017ms
,W/asset   ( 7627): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 7627): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/HwSystemManager( 6522): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2929):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 2929):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2929):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 2929):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/HwSystemManager( 3468): HoldService:uid:10010 pid:7135 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10010,7135
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10010
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10010, pid: 7135
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10010, pid: 7135
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 2929): do suspend true
,I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 2929): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 2929): link address 192.168.1.120/24
,E/WifiStateMachine( 2929): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 2929): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 2929):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE,
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 5
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=44 dispatchEvent: HEART-BEAT-ACK: 5
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 2929): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine( 2929): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 2929): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
,I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/System  ( 2929): core_booster, getBoosterConfig = false
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
E/WifiStateMachine( 2929):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:42267] from screen [on:0 period:-2017759921] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/HwSystemManager( 3468): HoldService:uid:1000 pid:7241 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:1000,7241
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
W/MediaProcessHandler( 2929): processOp uid 1000 is not concerned!
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3209): STATE =1
,I/WifiTracker( 3209): STATE =1
,W/ContextImpl( 7692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/ContextImpl( 7692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7692): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7692):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7692):   adb logcat -s GAv4
,W/ContextImpl( 7692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7692): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7692): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7692): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 7692): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 7692): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 7692): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 7692): Loading: webviewchromium
,I/LibraryLoader( 7692): Time to load native libraries: 3 ms (timestamps 6991-6994)
,I/LibraryLoader( 7692): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 7692): Expected native library version number "",actual native library version number ""
,I/chromium( 7692): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7692): Initializing chromium process, renderers=0
,W/art     ( 7692): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7692): Requires BLUETOOTH permission
W/chromium( 7692): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7692): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
,I/chromium( 7692): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 7692): Starting up...
,I/System  ( 5997): core_booster, getBoosterConfig = false
,I/HwEmailTag( 7541): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7541): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7541): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3237): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 6913): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 6913): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3142): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 7573): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7573): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/art     ( 7600): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7600): ThemeHelperretry to get Settings
,E/HwSystemManager( 6522): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwEmailTag( 7541): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 7541): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 7541): EmailProvider->query->1449681186816;end;;consuming:1ms;
,I/HwEmailTag( 7541): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 7541): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 7541): CleanRecipient->onCreate
I/HwEmailTag( 7541): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 7541): Device->getDeviceId->
,I/HwEmailTag( 7541): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 7541): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 7541): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 7541): CleanRecipient->onStartCommand->action is null
,I/HwEmailTag( 7541): CleanRecipient->onHandleIntent->action is null
,I/HwEmailTag( 7541): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 7541): CleanRecipient->onDestroy
,I/HwEmailTag( 7541): AccountReconciler->reconcileAccountsInternal->consuming:74ms
,I/HwEmailTag( 7541): EmailProvider->query->1449681186894;end;;consuming:2ms;
,I/HwEmailTag( 7541): AccountReconciler->reconcileAccountsInternal->consuming:3ms
,I/HwCust  ( 7771): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7771): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 7771): Exchange->onCreate
,I/PG Utils( 7771): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7771): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7541): EmailProvider->query->1449681186978;end;;consuming:1ms;
,I/HwEmailTag( 7771): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/HwSystemManager( 3468): HoldService:uid:10044 pid:7279 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10044,7279
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10044, pid: 7279
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10044, pid: 7279
,W/ArpVerifier( 2929): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3659): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
,I/HwEmailTag( 7541): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7541): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7541): EmailProvider->notifyNetworkChanged->
,I/NetworkMonitor( 6949): type=WIFI subType= reason=null isConnected=true
,I/AccountTypeManager( 6913): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2c575590 in the cache
,I/SimFactoryManager( 6913): Get SIM state from SIM factory manager: 1,For slotId:0
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/SimFactoryManager( 6913): Get SIM state from SIM factory manager: 1,For slotId:1
,E/GpsLocationProvider( 2929): No APN found to select.
,I/DownloadManager( 3237): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/AccountTypeManager( 6913): Adding account type = com.android.contacts.model.account.ExternalAccountType@3aa17e89 in the cache
,W/GNSS_ADAPTER( 2929): This function not used.
,W/GNSS_ADAPTER( 2929): This function not used.
,W/ResourceType( 6913): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,W/ResourceType( 6913): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6913): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6913): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6913): Adding account type = com.android.contacts.model.account.ExternalAccountType@3d043abc in the cache
,I/AccountTypeManager( 6913): Adding account type = com.android.contacts.model.account.GoogleAccountType@2e1a7a45 in the cache
,I/Mms_TXM_SVC( 6913): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6913): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3142): is magazine unlock on, now is lock screen diabled mode
I/HwOUC   ( 7573): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,E/ExternalAccountType( 6913): Unsupported attribute readOnly
,I/HwOUC   ( 7573): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 7573): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 7573): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 7573): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
I/AccountTypeManager( 6913): AccountManager, account size is: 2
,I/AccountTypeManager( 6913): Loaded meta-data for 5 account types, 3 accounts in 56ms(wall) 22ms(cpu)
,I/art     ( 7600): Can not find class: Landroid/provider/Settings$Systemex;
E/HwThemeManager( 7600): ThemeHelperretry to get Settings
,I/HwOUC   ( 7573): [Thread-124-124]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,E/HwSystemManager( 6522): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,E/WifiStateMachine( 2929):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 2929):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/art     ( 3634): Explicit concurrent mark sweep GC freed 26751(1420KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.049ms total 66.220ms
,I/HwOUC   ( 7573): [Thread-124-124]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/Process ( 7573): Sending signal. PID: 7573 SIG: 9
,I/HwSystemManager( 3468): HoldService:uid:10052 pid:7573 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10052,7573
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10052
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10052, pid: 7573
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10052, pid: 7573
,I/HwEmailTag( 7541): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 7541): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 7541): EmailProvider->triggerPeroidSync->accountId:-1
,I/jxcore-log( 7454): Test app app.js loaded
I/jxcore-log( 7454): 
,I/chromium( 7454): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7454): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/HwEmailTag( 7541): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 7541): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7541): EmailProvider->triggerPeroidSync->accountId:-1
I/HwEmailTag( 7541): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 7541): EmailProvider->query->1449681191973;end;;consuming:2ms;
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 30099 firstTime = 92729 firstmBatteryCapacity =2203
,W/ArpVerifier( 2929): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 33822 firstTime = 92729 firstmBatteryCapacity =2203
,I/ActivityManager( 2929): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/HwLauncher( 3682): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3209): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3209): hand message 1
I/TimeManager( 3209): notify time change. size = 2
I/TimeLayout( 3209): time = 18:13
,I/TimeLayout( 3209): updateDate date = 12/9/2015
,I/TimeLayout( 3209): weekDay = Wednesday
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/VacuumService( 3869): Vacuum at: now=1449681198196 tag=VacuumService
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2929): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 5913): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 3869): Scheduling Phenotype for one-off execution 8642 seconds from now (1449681198547)
,I/ActivityManager( 2929): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PhenotypeFlagCommitter( 3869): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 3869): Using platform SSLCertificateSocketFactory
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 3869): core_booster, getBoosterConfig = false
,I/System  ( 3869): core_booster, getBoosterConfig = false
,I/PG Utils( 3869): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=45 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/art     ( 7600): System.exit called, status: 0
I/AndroidRuntime( 7600): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3468): HoldService:uid:10060 pid:7600 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10060,7600
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10060
,E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10060, pid: 7600
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10060, pid: 7600
,E/Thermal-daemon( 2331): [ap] temp_new :30  temp_old :31
,E/Thermal-daemon( 2331): [charger_ic] temp_new :30  temp_old :31
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 3468): LauncherPredicate:get default launcher is null, set hwlauncher
,I/art     ( 2929): Explicit concurrent mark sweep GC freed 56478(3MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/42MB, paused 1.982ms total 184.924ms
,I/HwSystemManager( 3468): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3468): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3468): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3468): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3468): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 3468): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 3468): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1120051200 [332800000,437657600,542515200]
I/HwSystemManager( 3468): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 3468): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,E/WifiStateMachine( 2929):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 2929):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2929):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 2929):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/ClearcutLoggerApiImpl( 3869): disconnect managed GoogleApiClient
,I/ActivityManager( 2929): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/bluedroid( 4724): bt interface: [set_adapter_property]
W/bt-btif ( 4724): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4724): adapterPropertyChangedCallback with type:9 len:4
I/bluedroid( 4724): bt interface: [set_adapter_property]
W/bt-btm  ( 4724): BTM_SetDiscoverability
,W/bt-btif ( 4724): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 4724): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4724): adapterPropertyChangedCallback with type:7 len:4
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 8
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 9
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 90264 firstTime = 92729 firstmBatteryCapacity =2203
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 93824 firstTime = 92729 firstmBatteryCapacity =2203
,E/Thermal-daemon( 2331): [ap] temp_new :29  temp_old :30
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 10
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwLauncher( 3682): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3209): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3209): hand message 1
I/TimeManager( 3209): notify time change. size = 2
,I/TimeLayout( 3209): time = 18:14
,I/TimeLayout( 3209): updateDate date = 12/9/2015
,I/TimeLayout( 3209): weekDay = Wednesday
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :30
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 12
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 15
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=55 dispatchEvent: HEART-BEAT-ACK: 16
E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2929): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5
E/WifiMonitor( 2929): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 9e:93:4e:3e:ba:c5
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=58 dispatchEvent: HEART-BEAT-ACK: 17
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 210577 firstTime = 92729 firstmBatteryCapacity =2203
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 213820 firstTime = 92729 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=59 dispatchEvent: HEART-BEAT-ACK: 18
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/art     ( 2929): Can not find class: Lcom/android/server/power/PowerManagerService$5$1;
,I/System  ( 2929): core_booster, getBoosterConfig = false
,I/System  ( 2929): core_booster, getBoosterConfig = false
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 19
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 19
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 20
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 20
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/art     ( 2929): Can not find class: Lcom/android/server/am/ActivityManagerService$31$1;
,I/OAM     ( 2663): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2663): [rename_old_file:107]rename_old_file
I/OAM     ( 2663): 
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 21
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=62 dispatchEvent: HEART-BEAT-ACK: 21
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 270748 firstTime = 92729 firstmBatteryCapacity =2203
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 273823 firstTime = 92729 firstmBatteryCapacity =2203
,I/art     ( 2929): Can not find class: Lcom/android/server/am/ActivityManagerService$33$1;
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 22
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=63 dispatchEvent: HEART-BEAT-ACK: 22
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 23
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=64 dispatchEvent: HEART-BEAT-ACK: 23
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 300824 firstTime = 92729 firstmBatteryCapacity =2203
E/HwSystemManager( 3468): BgPowerManagerService: conusmPower = -1 result = -11 flag1 =false flag2 = false
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 24
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=65 dispatchEvent: HEART-BEAT-ACK: 24
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 25
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=66 dispatchEvent: HEART-BEAT-ACK: 25
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 0 firstTime = 426553 firstmBatteryCapacity =2204
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 26
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=67 dispatchEvent: HEART-BEAT-ACK: 26
,E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3274): wlan0: HEART-BEAT-ACK: 27
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=68 dispatchEvent: HEART-BEAT-ACK: 27
E/WifiStateMachine( 2929):  ConnectedState what:147506 0 0
E/WifiStateMachine( 2929):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 2929):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 2929):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState what:147506 0 0
,I/jxcore-log( 7454): Toggling radios to false
I/jxcore-log( 7454): 
,I/BluetoothAdapter( 7454): Start to disable Bluetooth!
,I/art     ( 2929): Can not find class: Lcom/android/server/DropBoxManagerService$1$1;
,I/BluetoothAdapterState( 4724): Bluetooth adapter state changed: 12-> 13
,I/bluedroid( 4724): bt interface: [set_adapter_property]
W/bt-btm  ( 4724): BTM_SetDiscoverability
I/BluetoothAdapterState( 4724): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/ActivityManager( 2929): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,W/bt-btm  ( 4724): BTM_SetConnectability
W/bt-btif ( 4724): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4724): adapterPropertyChangedCallback with type:7 len:4
,I/bluedroid( 4724): bt interface: [disable]
W/bt-btif ( 4724): btif_disable_bluetooth, btif_core_radio_ref_count=0
W/bt-btif ( 4724): BTIF DISABLE BLUETOOTH
W/bt-btif ( 4724): bta_sys_disable: module 0
W/bt-btm  ( 4724): BTM_SetDiscoverability
W/bt-btm  ( 4724): BTM_SetConnectability
W/bt-btif ( 4724): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/BtOppRfcommListener( 4724): stopping Accept Thread
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
I/HwSystemManager( 3468): HoldService:checkBeforeShowDialog: uid:10295 pid:7454, permissionType:2097152
I/HwSystemManager( 3468): OverseaCfgHelper:permissionStatus is 0
E/BtOppRfcommListener( 4724): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BtOppRfcommListener( 4724): BluetoothSocket listen thread finished
,I/bluetooth-coex( 4724): bt_coex_deinit: bt_coex_deinit
I/ConnectPermission( 2929): allowOpenWifi blocked:false
I/bluetooth-coex( 4724): btcoex_send_msg: send bt_state(0) to wifi, sock_fd(72)
I/bluetooth-coex( 4724): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4724): btcoex_send_msg: bt closing, exit coex server, sock_fd(72)
I/bluetooth-coex( 4724): btcoex_socket_server: BT_COEX_PTHREAD_EXIT
I/bluetooth-coex( 4724): bt_coex_deinit: clear coex timer list entry
I/bluetooth-coex( 4724): bt_coex_deinit: free g_bt_coex_cb
,E/WifiStateMachine( 2929):  ConnectedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 2929):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 7454): Radios toggled
I/jxcore-log( 7454): 
E/WifiStateMachine( 2929):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2929):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2929): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 2929): setScanAlarm false period 0 initial delay 0
E/WifiStateMachine( 2929): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 2929): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,E/native  ( 2929): do suspend true
,I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiConfigStore( 2929): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ArpVerifier( 2929): current SSID is empty.
,E/WifiStateMachine( 2929): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 2929): noteBatchedScanstop()
E/WifiStateMachine( 2929): [1,449,681,518,649 ms] noteScanEnd no scan source
E/WifiStateMachine( 2929):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 2929): Can not find class: Lcom/android/server/wifi/RttService$RttServiceImpl$ClientInfo;
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2929):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2929):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2929): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2929):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,E/native  ( 2929): do suspend true
,I/wpa_supplicant( 3274): set current WIFI status to BT!
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 3274): set current WIFI status to BT!
I/wpa_supplicant( 3274): WIFI closed already, cancel
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
,I/wpa_supplicant( 3274): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 3274): check_associate_result func start
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2929): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/System.err( 2929): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2929): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2929): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 2929): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 2929): This is not beta user build
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,W/bt-btif ( 4724): bta_sys_hw_api_disable for 0, active modules: 0x0001
W/bt-btif ( 4724): bta_sys_disable: module 0
W/bt-btif ( 4724): call bta_sys_hw_co_disable
W/bt-btif ( 4724): sending BTA_SYS_EVT_DISABLED_EVT
W/bt-btif ( 4724): bta_sys_hw_evt_disabled - module 0x0
W/bt-btif ( 4724):  bta_dm_sys_hw_cback with event: 0
W/bt-btif ( 4724): btif_disable not allocated
W/bt-btif ( 4724): btif_disable not allocated, btif_core_is_radio_req = 0
W/bt-btif ( 4724): btif_dm_disable_bt_services
W/bt-btif ( 4724): btif_dm_disable_bt_services i=6
E/bt-btif ( 4724): BTA AG is already disabled, ignoring ...
W/bt-btif ( 4724): btif_dm_disable_bt_services i=18
W/bt-l2cap( 4724): btif_dm_disable_bt_services i=20
W/bt-btif ( 4724): btif_dm_disable_bt_services i=20
W/bt-l2cap( 4724): btif_dm_disable_bt_services i=25
W/bt-btif ( 4724): btif_dm_disable_bt_services i=25
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4724): L2CAP - PSM: 0x0019
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-btif ( 4724): bte_main_disable
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4724): ag scb idx 1 not allocated
E/bt-btif ( 4724): BTA AG is already disabled, ignoring ...
W/bt_lpm  ( 4724): Still busy on processing prior LPM enable/disable request...
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4724): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_userial( 4724): select_read return size <=0:-1, exiting userial_read_thread
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,W/wpa_supplicant( 3274): STA MODE: Set shutdown wlan cmd SUCCESS,
E/WifiMonitor( 2929): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/wpa_supplicant( 3274): check_associate_result func start
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null,
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/ActivityManager( 2929): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 2929):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=449205
E/WifiStateMachine( 2929):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=449205
,E/WifiStateMachine( 2929):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=449206  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 2929):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=449207  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,I/HwSystemManager( 3468): MainReceiver:receive action:android.net.wifi.WIFI_STATE_CHANGED
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null,
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
,I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,E/WifiStateMachine( 2929):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 2929):  DefaultState CMD_ON_QUIT 0 0
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
,I/WifiTracker( 3209): STATE =0
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 2929): handleEvent 13  CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
,W/wpa_supplicant( 3274): ioctl error:ret = -1
E/wpa_supplicant( 3274): wpa_driver_set_wps_p2p_ie failed ret=-1
,I/NetworkSpeedManagerEx( 3209): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3209): wifiManager = android.net.wifi.WifiManager@3a51037c
,I/HwSystemManager( 3468): HoldService:uid:10026 pid:7105 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10026,7105
,I/NetworkSpeedManagerEx( 3209): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3209): stop
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10026
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10026, pid: 7105
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10026, pid: 7105
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
I/WifiTracker( 3209): STATE =0
,I/WifiTracker( 3209): STATE =0
,I/WifiTracker( 3209): STATE =0
,I/WifiTracker( 3209): STATE =0
,W/View    ( 3209): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{308052ed V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/wpa_supplicant( 3274): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiMonitor( 2929): WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine( 2929):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 72 0
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT type, proxy, port FROM carriers WHERE (numeric = ',' and carrier_enabled = 1)
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/HwSystemManager( 3468): WifiApStateReceiver:onReceive: action = android.net.conn.TETHER_STATE_CHANGED
,I/HwSystemManager( 3468): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@5e058e2
,I/HwSystemManager( 3468): HsmIntentService:started for intent:Intent { act=android.net.conn.TETHER_STATE_CHANGED flg=0x24000010 cmp=com.huawei.systemmanager/com.huawei.netassistant.wifiap.WifiApStateReceiver (has extras) }, action:android.net.conn.TETHER_STATE_CHANGED, class:com.huawei.netassistant.wifiap.WifiApStateReceiver
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwSystemManager( 3468): HsmIntentService:invoked com.huawei.netassistant.wifiap.WifiApStateReceiver
I/HwSystemManager( 3468): WifiApStateReceiver:handleTetherStateChange: Wifi AP is not enabled ,skip
I/HwSystemManager( 3468): HsmIntentService:task completed for intent:Intent { act=android.net.conn.TETHER_STATE_CHANGED flg=0x24000010 cmp=com.huawei.systemmanager/com.huawei.netassistant.wifiap.WifiApStateReceiver (has extras) }, action:android.net.conn.TETHER_STATE_CHANGED
I/HwSystemManager( 3468): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3468): HsmIntentService:last work complete! lets stop service.
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/        ( 4724): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_cleanup 354][bt_vendor] cleanup
,I/GKI_LINUX( 4724): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 4724): GKI_exit_task 0 done
I/GKI_LINUX( 4724): GKI_shutdown(): task [BTU] terminated
W/bt-btif ( 4724): HAL bt_hal_cbacks->adapter_state_changed_cb
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,W/BluetoothHeadsetServiceJni( 4724): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4724): Cleaning up Bluetooth Handsfree callback object
,I/HwSystemManager( 3468): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@5e058e2
,I/GKI_LINUX( 4724): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4724): GKI_exit_task 2 done
I/GKI_LINUX( 4724): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 4724): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 4724): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 4724): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 4724): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 4724): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 4724): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 4724): Cleaning up Bluetooth PAN callback object
,I/BluetoothAdapterState( 4724): Bluetooth adapter state changed: 13-> 10,
I/BluetoothAdapterState( 4724): Entering OffState
,I/ActivityManager( 2929): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 5997): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 3869): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
I/System.out( 3659): Stale Location error
I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 193
,I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
I/HwSystemManager( 3468): MainReceiver:receive action:android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 2929): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED,
I/bluedroid( 4724): bt interface: [cleanup]
W/bt-btif ( 4724): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 4724): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 4724): GKI_exit_task 1 done
I/GKI_LINUX( 4724): GKI_shutdown(): task [BTIF] terminated,
I/BluetoothServiceJni( 4724): cleanupNative: return from cleanup
I/BluetoothServiceJni( 4724): OoO sJniCallbacksObj has init before clean? 1
,I/art     ( 4724): System.exit called, status: 0
,I/AndroidRuntime( 4724): VM exiting with result code 0, cleanup skipped.
,E/JavaBinder( 2929): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 2929): !!! FAILED BINDER TRANSACTION !!!
,E/WifiStateMachine( 2929): could not open wifi state sys nodejava.io.FileNotFoundException: /sys/devices/platform/bcmdhd_wlan.1/wifi_open_state: open failed: ENOENT (No such file or directory)
,E/WifiStateMachine( 2929):  InitialState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 2929):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,I/HwSystemManager( 3468): HoldService:uid:1002 pid:4724 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:1002,4724
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 1002
,E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
W/MediaProcessHandler( 2929): processOp uid 1002 is not concerned!
,I/WifiTracker( 3209): STATE =0
,I/HwSystemManager( 3468): HoldService:uid:10007 pid:7365 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10007,7365
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10007
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10007, pid: 7365
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10007, pid: 7365
,W/ArpVerifier( 2929): ignore msg MSG_CHECK_WIFI_STATE, msg token = 10, expected token = 14
,W/ArpVerifier( 2929): ignore msg MSG_CHECK_WIFI_STATE, msg token = 11, expected token = 14
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 2929): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 3659): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
,I/SUPL20_SCM( 3659): Network connection true
I/SUPL20_SPIMESLP-SENDING( 3659): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 3659): bBrokenPipe = false
,I/HwEmailTag( 7541): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7541): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7541): EmailProvider->notifyNetworkChanged->
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 2929): No APN found to select.
,W/GNSS_ADAPTER( 2929): This function not used.
,W/GNSS_ADAPTER( 2929): This function not used.
,I/DownloadManager( 3237): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,E/TEST-APN( 3634): query for APN: check-permission succ 
E/TEST-APN( 3634): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 2929): No APN found to select.
,W/GNSS_ADAPTER( 2929): This function not used.
,W/GNSS_ADAPTER( 2929): This function not used.
,I/Mms_TXM_SVC( 6913): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6913): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3142): is magazine unlock on, now is lock screen diabled mode
,E/HwOUC   ( 8206): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8206): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8206): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 8206): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8206): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8206): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8206): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8206): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 3468): HoldService:uid:10025 pid:7186 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10025,7186
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10025
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10025, pid: 7186
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10025, pid: 7186
,W/asset   ( 8229): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8229): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,E/HwSystemManager( 6522): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/Babel   ( 5997): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 5913): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5913): num queued entries: 0
,I/iu.UploadsManager( 5913): num updated entries: 0
,I/iu.SyncManager( 5913): NEXT; no task
,I/HwSystemManager( 3468): HoldService:uid:10005 pid:7771 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10005,7771
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10005
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10005, pid: 7771
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10005, pid: 7771
,I/HwEmailTag( 7541): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7541): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7541): EmailProvider->notifyNetworkChanged->
,I/DownloadManager( 3237): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/Mms_TXM_SVC( 6913): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6913): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3142): is magazine unlock on, now is lock screen diabled mode
,I/HwOUC   ( 8206): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8206): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,E/HwSystemManager( 6522): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 27164 firstTime = 426553 firstmBatteryCapacity =2204
,E/WifiStateMachine( 2929):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 2929):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,I/HwEmailTag( 7541): EmailProvider->handleNetworkChanged->network is bad, WON'T start new EmailConnectivityTask
I/HwEmailTag( 7541): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7541): EmailProvider->triggerPeroidSync->accountId:-1
,I/PG Utils( 2929): startservicepkg:[com.android.bluetooth] pid:[8179]  maybe timeout , send to PG
,I/art     ( 8229): System.exit called, status: 0
I/AndroidRuntime( 8229): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 3468): HoldService:uid:10060 pid:8229 died
I/HwSystemManager( 3468): HoldService:oldVersionKey:10060,8229
I/HwSystemManager( 3468): BgPowerManagerService:onProcessDied uid = 10060
E/HsmCoreServiceImpl( 2929): onTransact in code is: 102
I/MediaProcessHandler( 2929): processOp opType: 1, uid: 10060, pid: 8229
W/MediaProcessHandler( 2929): remove target not exist, maybe the UI process: uid: 10060, pid: 8229
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 119996 firstTime = 426553 firstmBatteryCapacity =2204
,E/Thermal-daemon( 2331): [ap] temp_new :28  temp_old :29
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 237722 firstTime = 426553 firstmBatteryCapacity =2204
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 358039 firstTime = 426553 firstmBatteryCapacity =2204
E/HwSystemManager( 3468): BgPowerManagerService: conusmPower = 0 result = 0 flag1 =false flag2 = false
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 0 firstTime = 786549 firstmBatteryCapacity =2204
,I/HwLauncher( 3682): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
I/TimeManager( 3209): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3209): hand message 1
I/TimeManager( 3209): notify time change. size = 2
,I/TimeLayout( 3209): time = 18:24
,I/TimeLayout( 3209): updateDate date = 12/9/2015
,I/TimeLayout( 3209): weekDay = Wednesday
,I/PG Utils( 5913): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/EventLogService( 5913): Aggregate from 1449679549561 (log), 1449679549561 (data)
,I/PG Utils( 5913): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5913): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 88278 firstTime = 786549 firstmBatteryCapacity =2204
,I/AGNSSCONTROL( 2666): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2666): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876063616
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2876092904
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2666): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2666): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
,E/Lss-gw  ( 2666): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449681976499, wifi_time:1449681519196
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:9e:93:4e:3e:ba:c5
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:2
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:1
,I/AGNSSCONTROL( 2666): int MyLssGwCommunicator::sendRequestWithWlanInfo(EPH_TYPE, unsigned char*, int, bool) -- 73: sendRequestWithWlanInfo called, wlanLen:12
,E/Lss     ( 8646): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 8646): No reference location.
W/Lss     ( 8646): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3199 bytes of data
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:4024913, nTOWassist:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
,I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:14, iode3:14, m0:-275078661.000000, delta_n:15199.000000, ecc:129367327.000000, ek:0.000000, sqrt_a:2702008595.000000, omega_0:550424560.000000, i0:643849521.000000, omega:-1507308778.000000, omega_dot:-24168.000000, i_dot:1485.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:910.000000, cus:3531.000000, crc:7900.000000, crs:915.000000, cic:-13.000000, cis:118.000000, group_delay:-44.000000, af0:1283267.000000, af1:6.000000, af2:0.000000, aodc:14, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:15
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:67, iode3:67, m0:734840789.000000, delta_n:13487.000000, ecc:1947353.000000, ek:0.000000, sqrt_a:2701964350.000000, omega_0:573249747.000000, i0:658290710.000000, omega:-2128452942.000000, omega_dot:-22690.000000, i_dot:1398.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:729.000000, cus:3496.000000, crc:8225.000000, crs:913.000000, cic:1.000000, cis:-4.000000, group_delay:9.000000, af0:234757.000000, af1:57.000000, af2:0.000000, aodc:67, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:21, iode3:21, m0:1752672124.000000, delta_n:11560.000000, ecc:13887319.000000, ek:0.000000, sqrt_a:2701982353.000000, omega_0:-144459514.000000, i0:657467991.000000, omega:-1097889150.000000, omega_dot:-21625.000000, i_dot:580.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2210.000000, cus:5865.000000, crc:5418.000000, crs:-2556.000000, cic:15.000000, cis:-5.000000, group_delay:10.000000, af0:-33412.000000, af1:-13.000000, af2:0.000000, aodc:21, health:0, toc:20247, toe:20247, status:0, code_on_L2:1, fit_interval_flag:0, aodo:8
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:1, iode2:89, iode3:89, m0:-2058717377.000000, delta_n:13793.000000, ecc:7541359.000000, ek:0.000000, sqrt_a:2702011804.000000, omega_0:1288019051.000000, i0:655573594.000000, omega:-2015043838.000000, omega_dot:-22679.000000, i_dot:-1190.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-748.000000, cus:3658.000000, crc:7970.000000, crs:-901.000000, cic:13.000000, cis:-19.000000, group_delay:7.000000, af0:85379.000000, af1:59.000000, af2:0.000000, aodc:89, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:17, iode3:17, m0:-1390744736.000000, delta_n:10842.000000, ecc:48049920.000000, ek:0.000000, sqrt_a:2701952499.000000, omega_0:-822694761.000000, i0:676759697.000000, omega:437729435.000000, omega_dot:-22137.000000, i_dot:-775.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2912.000000, cus:2285.000000, crc:9991.000000, crs:-3410.000000, cic:3.000000, cis:-21.000000, group_delay:-27.000000, af0:755881.000000, af1:26.000000, af2:0.000000, aodc:17, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:59, iode3:59, m0:792294261.000000, delta_n:11596.000000, ecc:71574599.000000, ek:0.000000, sqrt_a:2702025193.000000, omega_0:2058615121.000000, i0:660007111.000000, omega:-1330321052.000000, omega_dot:-22080.000000, i_dot:-651.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2173.000000, cus:6395.000000, crc:4937.000000, crs:2485.000000, cic:-89.000000, cis:7.000000, group_delay:-20.000000, af0:35476.000000, af1:-21.000000, af2:0.000000, aodc:59, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:14, iode3:14, m0:1502947682.000000, delta_n:10946.000000, ecc:70853268.000000, ek:0.000000, sqrt_a:2702007883.000000, omega_0:-809880920.000000, i0:677125064.000000, omega:215021709.000000, omega_dot:-22301.000000, i_dot:-949.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2836.000000, cus:1974.000000, crc:10492.000000, crs:-3257.000000, cic:-44.000000, cis:7.000000, group_delay:-22.000000, af0:-126520.000000, af1:31.000000, af2:0.000000, aodc:14, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:19, iode3:19, m0:1887950407.000000, delta_n:15697.000000, ecc:140914052.000000, ek:0.000000, sqrt_a:2701992412.000000, omega_0:1272378088.000000, i0:631967844.000000, omega:-1316131501.000000, omega_dot:-23019.000000, i_dot:-1380.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1067.000000, cus:3233.000000, crc:7704.000000, crs:-1192.000000, cic:77.000000, cis:-105.000000, group_delay:-24.000000, af0:990105.000000, af1:34.000000, af2:0.000000, aodc:19, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:15
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:12, iode3:12, m0:340040941.000000, delta_n:16130.000000, ecc:43247938.000000, ek:0.000000, sqrt_a:2702004018.000000, omega_0:1236777945.000000, i0:632791768.000000, omega:880900026.000000, omega_dot:-24209.000000, i_dot:-1236.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-726.000000, cus:3324.000000, crc:7780.000000, crs:-916.000000, cic:-19.000000, cis:18.000000, group_delay:-18.000000, af0:809850.000000, af1:25.000000, af2:0.000000, aodc:12, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:7
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:9, iode3:9, m0:1556623627.000000, delta_n:16168.000000, ecc:68802139.000000, ek:0.000000, sqrt_a:2702002058.000000, omega_0:1272931115.000000, i0:630488741.000000, omega:-1400224766.000000, omega_dot:-23728.000000, i_dot:-1133.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-997.000000, cus:3331.000000, crc:7696.000000, crs:-1107.000000, cic:29.000000, cis:-105.000000, group_delay:-38.000000, af0:897771.000000, af1:30.000000, af2:0.000000, aodc:9, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:16
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:18, iode3:18, m0:-436789293.000000, delta_n:13630.000000, ecc:33355847.000000, ek:0.000000, sqrt_a:2701994585.000000, omega_0:-1586495307.000000, i0:650401386.000000, omega:208977043.000000, omega_dot:-23834.000000, i_dot:451.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2687.000000, cus:1616.000000, crc:10174.000000, crs:3137.000000, cic:56.000000, cis:2.000000, group_delay:6.000000, af0:-19457.000000, af1:-5.000000, af2:0.000000, aodc:18, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:24
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:23, iode3:23, m0:-2027894385.000000, delta_n:12985.000000, ecc:4256816.000000, ek:0.000000, sqrt_a:2702011379.000000, omega_0:-860249541.000000, i0:656519511.000000, omega:-218219206.000000, omega_dot:-23535.000000, i_dot:-760.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2528.000000, cus:1354.000000, crc:10622.000000, crs:-2945.000000, cic:31.000000, cis:20.000000, group_delay:16.000000, af0:-338783.000000, af1:-151.000000, af2:0.000000, aodc:23, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:6, iode3:6, m0:1352282083.000000, delta_n:10472.000000, ecc:171953493.000000, ek:0.000000, sqrt_a:2702025786.000000, omega_0:-806363906.000000, i0:676214500.000000, omega:-1122714617.000000, omega_dot:-21568.000000, i_dot:-807.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3007.000000, cus:1927.000000, crc:10352.000000, crs:-3257.000000, cic:137.000000, cis:-163.000000, group_delay:-24.000000, af0:1046083.000000, af1:23.000000, af2:0.000000, aodc:6, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:5
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:47, iode3:47, m0:-1143126617.000000, delta_n:13339.000000, ecc:14116658.000000, ek:0.000000, sqrt_a:2702005278.000000, omega_0:-1524417683.000000, i0:652166110.000000, omega:2141839135.000000, omega_dot:-23517.000000, i_dot:530.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2509.000000, cus:1334.000000, crc:10504.000000, crs:2923.000000, cic:0.000000, cis:8.000000, group_delay:7.000000, af0:147403.000000, af1:46.000000, af2:0.000000, aodc:47, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:53, iode3:53, m0:-834264952.000000, delta_n:14654.000000, ecc:97735313.000000, ek:0.000000, sqrt_a:2701991690.000000, omega_0:1345128802.000000, i0:646935329.000000, omega:131117693.000000, omega_dot:-23243.000000, i_dot:-943.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1046.000000, cus:3528.000000, crc:7847.000000, crs:-1187.000000, cic:59.000000, cis:-103.000000, group_delay:-7.000000, af0:91635.000000, af1:106.000000, af2:0.000000, aodc:53, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31,
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 106656
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:1, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:1, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:2, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:5, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:2, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:1, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:6, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:1, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:6, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:6, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:0, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:6, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:6, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:4, usIod:81, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
,I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
,I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
,I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 148444 firstTime = 786549 firstmBatteryCapacity =2204
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 178527 firstTime = 786549 firstmBatteryCapacity =2204
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 240000 firstTime = 786549 firstmBatteryCapacity =2204
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,E/Thermal-daemon( 2331): [charger_ic] temp_new :29  temp_old :28
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 268759 firstTime = 786549 firstmBatteryCapacity =2204
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 298843 firstTime = 786549 firstmBatteryCapacity =2204
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 300003 firstTime = 786549 firstmBatteryCapacity =2204
E/HwSystemManager( 3468): BgPowerManagerService: conusmPower = -1 result = -11 flag1 =false flag2 = false
,E/Thermal-daemon( 2331): [charger_ic] temp_new :28  temp_old :29
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 0 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 1001 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 30098 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 60174 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 61005 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 120325 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 121000 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 150405 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 240640 firstTime = 1145548 firstmBatteryCapacity =2205
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 360970 firstTime = 1145548 firstmBatteryCapacity =2205
E/HwSystemManager( 3468): BgPowerManagerService: conusmPower = -1 result = -9 flag1 =false flag2 = false
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 0 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 30059 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 120307 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 150381 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 180469 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 210544 firstTime = 1566689 firstmBatteryCapacity =2206
,I/HwSystemManager( 3468): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3468): BgPowerManagerService: mTimes = 239862 firstTime = 1566689 firstmBatteryCapacity =2206
,I/AGNSSCONTROL( 2666): void pgps_timer_func(sigval) -- 62: Timer: overflow invoke time func
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 488: m_pgps_mode:1
I/AGNSSCONTROL( 2666): void kill_timer(timer_t) -- 102: Timer: kill a timer 2876092904
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 498: Timer: set a timer again 2876107016
I/AGNSSCONTROL( 2666): AGNSS_STATUS_ENUM_UINT32 PACommMgr::RequestFunc() -- 504: create thread
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 588: mcc:0, mnc:0, lac:0, cid:0
I/AGNSSCONTROL( 2666): void PACommMgr::SetAllowSendingCellIdsWlanApnToServerStatus(MyLssGwCommunicator*) -- 537: persist.sys.pgps.config=[0], not allow to send cell ids or wlan apn to server!
I/AGNSSCONTROL( 2666): void MyLssGwCommunicator::allowSendingCellIdsToServer(bool) -- 161: allowSendingCellIdsToServer allow = 0
E/Lss-gw  ( 2666): AllowSendingCellIdsToServer could not remove file. Error 2
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 595: Send RequestAssistance times: 0
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 621: current_time:1449682876498, wifi_time:1449681519196
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:c0:ff:d4:d3:aa:48
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:9e:93:4e:3e:ba:c5
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 630: mac:
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 634: MAC ADDRESS is empty, so continue
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 674: WIFI MAC ADDRESS COUNT:2
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 686: Request using wifi, flag:1
I/AGNSSCONTROL( 2666): int MyLssGwCommunicator::sendRequestWithWlanInfo(EPH_TYPE, unsigned char*, int, bool) -- 73: sendRequestWithWlanInfo called, wlanLen:12
,E/Lss     ( 9437): Unable to open cell info file /data/gnss/pgps/cell_info.dat
E/Lss     ( 9437): No reference location.
W/Lss     ( 9437): Cannot calculate visible satellites. Returning all odd satellite ids
,I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 790: Received 3199 bytes of data
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 830: Decode msg to pdu
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGPSAssistance(SUPL_GPS_ASSISTANCE_DATA*) -- 1001: pstGpsAssistanceData->field_valid = 378
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectRefTime(SUPL_GPS_ASSISTANCE_DATA*) -- 1073: gpsTime.gpsWeek:850, gpsTime.gpsTOW23b:4036163, nTOWassist:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectIonospheric(SUPL_GPS_ASSISTANCE_DATA*) -- 1204: SUPL_IONOSPHERE_STRU size 8
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectUTCModel(SUPL_GPS_ASSISTANCE_DATA*) -- 1253: SUPL_UTC_PARAMETER_STRU size 20
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:1, acc:0, iode2:14, iode3:14, m0:-275078661.000000, delta_n:15199.000000, ecc:129367327.000000, ek:0.000000, sqrt_a:2702008595.000000, omega_0:550424560.000000, i0:643849521.000000, omega:-1507308778.000000, omega_dot:-24168.000000, i_dot:1485.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:910.000000, cus:3531.000000, crc:7900.000000, crs:915.000000, cic:-13.000000, cis:118.000000, group_delay:-44.000000, af0:1283267.000000, af1:6.000000, af2:0.000000, aodc:14, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:15
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:5, acc:0, iode2:67, iode3:67, m0:734840789.000000, delta_n:13487.000000, ecc:1947353.000000, ek:0.000000, sqrt_a:2701964350.000000, omega_0:573249747.000000, i0:658290710.000000, omega:-2128452942.000000, omega_dot:-22690.000000, i_dot:1398.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:729.000000, cus:3496.000000, crc:8225.000000, crs:913.000000, cic:1.000000, cis:-4.000000, group_delay:9.000000, af0:234757.000000, af1:57.000000, af2:0.000000, aodc:67, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:7, acc:0, iode2:21, iode3:21, m0:1752672124.000000, delta_n:11560.000000, ecc:13887319.000000, ek:0.000000, sqrt_a:2701982353.000000, omega_0:-144459514.000000, i0:657467991.000000, omega:-1097889150.000000, omega_dot:-21625.000000, i_dot:580.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2210.000000, cus:5865.000000, crc:5418.000000, crs:-2556.000000, cic:15.000000, cis:-5.000000, group_delay:10.000000, af0:-33412.000000, af1:-13.000000, af2:0.000000, aodc:21, health:0, toc:20247, toe:20247, status:0, code_on_L2:1, fit_interval_flag:0, aodo:8
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:9, acc:1, iode2:89, iode3:89, m0:-2058717377.000000, delta_n:13793.000000, ecc:7541359.000000, ek:0.000000, sqrt_a:2702011804.000000, omega_0:1288019051.000000, i0:655573594.000000, omega:-2015043838.000000, omega_dot:-22679.000000, i_dot:-1190.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-748.000000, cus:3658.000000, crc:7970.000000, crs:-901.000000, cic:13.000000, cis:-19.000000, group_delay:7.000000, af0:85379.000000, af1:59.000000, af2:0.000000, aodc:89, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:11, acc:0, iode2:17, iode3:17, m0:-1390744736.000000, delta_n:10842.000000, ecc:48049920.000000, ek:0.000000, sqrt_a:2701952499.000000, omega_0:-822694761.000000, i0:676759697.000000, omega:437729435.000000, omega_dot:-22137.000000, i_dot:-775.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2912.000000, cus:2285.000000, crc:9991.000000, crs:-3410.000000, cic:3.000000, cis:-21.000000, group_delay:-27.000000, af0:755881.000000, af1:26.000000, af2:0.000000, aodc:17, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:13, acc:0, iode2:59, iode3:59, m0:792294261.000000, delta_n:11596.000000, ecc:71574599.000000, ek:0.000000, sqrt_a:2702025193.000000, omega_0:2058615121.000000, i0:660007111.000000, omega:-1330321052.000000, omega_dot:-22080.000000, i_dot:-651.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2173.000000, cus:6395.000000, crc:4937.000000, crs:2485.000000, cic:-89.000000, cis:7.000000, group_delay:-20.000000, af0:35476.000000, af1:-21.000000, af2:0.000000, aodc:59, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:15, acc:0, iode2:14, iode3:14, m0:1502947682.000000, delta_n:10946.000000, ecc:70853268.000000, ek:0.000000, sqrt_a:2702007883.000000, omega_0:-809880920.000000, i0:677125064.000000, omega:215021709.000000, omega_dot:-22301.000000, i_dot:-949.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2836.000000, cus:1974.000000, crc:10492.000000, crs:-3257.000000, cic:-44.000000, cis:7.000000, group_delay:-22.000000, af0:-126520.000000, af1:31.000000, af2:0.000000, aodc:14, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:17, acc:0, iode2:19, iode3:19, m0:1887950407.000000, delta_n:15697.000000, ecc:140914052.000000, ek:0.000000, sqrt_a:2701992412.000000, omega_0:1272378088.000000, i0:631967844.000000, omega:-1316131501.000000, omega_dot:-23019.000000, i_dot:-1380.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1067.000000, cus:3233.000000, crc:7704.000000, crs:-1192.000000, cic:77.000000, cis:-105.000000, group_delay:-24.000000, af0:990105.000000, af1:34.000000, af2:0.000000, aodc:19, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:15
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:19, acc:0, iode2:12, iode3:12, m0:340040941.000000, delta_n:16130.000000, ecc:43247938.000000, ek:0.000000, sqrt_a:2702004018.000000, omega_0:1236777945.000000, i0:632791768.000000, omega:880900026.000000, omega_dot:-24209.000000, i_dot:-1236.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-726.000000, cus:3324.000000, crc:7780.000000, crs:-916.000000, cic:-19.000000, cis:18.000000, group_delay:-18.000000, af0:809850.000000, af1:25.000000, af2:0.000000, aodc:12, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:7
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:21, acc:0, iode2:9, iode3:9, m0:1556623627.000000, delta_n:16168.000000, ecc:68802139.000000, ek:0.000000, sqrt_a:2702002058.000000, omega_0:1272931115.000000, i0:630488741.000000, omega:-1400224766.000000, omega_dot:-23728.000000, i_dot:-1133.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-997.000000, cus:3331.000000, crc:7696.000000, crs:-1107.000000, cic:29.000000, cis:-105.000000, group_delay:-38.000000, af0:897771.000000, af1:30.000000, af2:0.000000, aodc:9, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:16
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:23, acc:0, iode2:18, iode3:18, m0:-436789293.000000, delta_n:13630.000000, ecc:33355847.000000, ek:0.000000, sqrt_a:2701994585.000000, omega_0:-1586495307.000000, i0:650401386.000000, omega:208977043.000000, omega_dot:-23834.000000, i_dot:451.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2687.000000, cus:1616.000000, crc:10174.000000, crs:3137.000000, cic:56.000000, cis:2.000000, group_delay:6.000000, af0:-19457.000000, af1:-5.000000, af2:0.000000, aodc:18, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:24
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:25, acc:0, iode2:23, iode3:23, m0:-2027894385.000000, delta_n:12985.000000, ecc:4256816.000000, ek:0.000000, sqrt_a:2702011379.000000, omega_0:-860249541.000000, i0:656519511.000000, omega:-218219206.000000, omega_dot:-23535.000000, i_dot:-760.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-2528.000000, cus:1354.000000, crc:10622.000000, crs:-2945.000000, cic:31.000000, cis:20.000000, group_delay:16.000000, af0:-338783.000000, af1:-151.000000, af2:0.000000, aodc:23, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:19
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:27, acc:0, iode2:6, iode3:6, m0:1352282083.000000, delta_n:10472.000000, ecc:171953493.000000, ek:0.000000, sqrt_a:2702025786.000000, omega_0:-806363906.000000, i0:676214500.000000, omega:-1122714617.000000, omega_dot:-21568.000000, i_dot:-807.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-3007.000000, cus:1927.000000, crc:10352.000000, crs:-3257.000000, cic:137.000000, cis:-163.000000, group_delay:-24.000000, af0:1046083.000000, af1:23.000000, af2:0.000000, aodc:6, health:0, toc:20249, toe:20249, status:0, code_on_L2:1, fit_interval_flag:0, aodo:5
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:29, acc:0, iode2:47, iode3:47, m0:-1143126617.000000, delta_n:13339.000000, ecc:14116658.000000, ek:0.000000, sqrt_a:2702005278.000000, omega_0:-1524417683.000000, i0:652166110.000000, omega:2141839135.000000, omega_dot:-23517.000000, i_dot:530.000000
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:2509.000000, cus:1334.000000, crc:10504.000000, crs:2923.000000, cic:0.000000, cis:8.000000, group_delay:7.000000, af0:147403.000000, af1:46.000000, af2:0.000000, aodc:47, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1463: svid:31, acc:0, iode2:53, iode3:53, m0:-834264952.000000, delta_n:14654.000000, ecc:97735313.000000, ek:0.000000, sqrt_a:2701991690.000000, omega_0:1345128802.000000, i0:646935329.000000, omega:131117693.000000, omega_dot:-23243.000000, i_dot:-943.000000
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectEphemeris(SUPL_GPS_ASSISTANCE_DATA*) -- 1484: cuc:-1046.000000, cus:3528.000000, crc:7847.000000, crs:-1187.000000, cic:59.000000, cis:-103.000000, group_delay:-7.000000, af0:91635.000000, af1:106.000000, af2:0.000000, aodc:53, health:0, toc:20250, toe:20250, status:0, code_on_L2:1, fit_interval_flag:0, aodo:31
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAlmanac(SUPL_GPS_ASSISTANCE_DATA*) -- 1535: remainder: 82
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 969: pstGanssAsstData is NULL
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
I/AGNSSCONTROL( 2666): static void* PACommMgr::RequestAssistance(void*) -- 892: HandleGanssAsstData called
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 960: pstGpsAssistanceData is NULL
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1702: pstGanssAsstData->field_valid = 1
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSAssistance(SUPL_GANSS_ASSISTANCE_DATA*) -- 1705: ganss inject ref time
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1747: pstGanssGenAsstData->field_valid = 106656
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1751: ganss inject timemodel list
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1761: ganss inject navmodel
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:0, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:1, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:2, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:3, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:4, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:5, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:6, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:7, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:8, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:9, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:10, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:11, ucSVHealth:4, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:12, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:13, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:14, ucSVHealth:5, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:15, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:17, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
,I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:19, ucSVHealth:4, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:20, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:21, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:22, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2055: ucSatId:23, ucSVHealth:3, usIod:83, ucIsOrbMdl:1, ucIsSVHealthMSB:0, ucSVHealthMSB:0,ucIsIodMSB:0,ucIodMSB:0
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSNavModel(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 2147: SUPL_GANSS_EPHEMERIS_MODEL_STRU size 11016
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1791: ganss inject alm
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1801: ganss inject addl utc model
I/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectGANSSGenAssistance(SUPL_GANSS_GENERIC_ASSISTANCE_DATA*) -- 1806: ganss inject auxi info
W/AGNSSCONTROL( 2666): static void PACommMgr::PAInjectAssistance(SUPL_GPS_ASSISTANCE_DATA*, SUPL_GANSS_ASSISTANCE_DATA*, SUPL_ADDITIONAL_ASSISTANCE_DATA*) -- 978: pstAddlAsstData is NULL
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000651
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectRefTime(CtrlFSM&) -- 646: PGPSInjectRefTime cmd received by CtrlFSMWaitState
,I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000655
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectIonospheric(CtrlFSM&) -- 688: PGPSInjectIonospheric cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000656
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectUTCModel(CtrlFSM&) -- 709: PGPSInjectUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000654
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectNavModel(CtrlFSM&) -- 751: PGPSInjectNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000657
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectAlmanac(CtrlFSM&) -- 772: PGPSInjectAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000659
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectRTIData(CtrlFSM&) -- 814: PGPSInjectRTIData cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065a
,I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSRefTime(CtrlFSM&) -- 821: PGPSInjectGANSSRefTime cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000065f
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSTimeModel(CtrlFSM&) -- 856: PGPSInjectGANSSTimeModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000661
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSNavModel(CtrlFSM&) -- 870: PGPSInjectGANSSNavModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000667
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAlmanac(CtrlFSM&) -- 912: PGPSInjectGANSSAlmanac cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x00000669
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAddlUTCModel(CtrlFSM&) -- 926: PGPSInjectGANSSAddlUTCModel cmd received by CtrlFSMWaitState
I/AGNSSCONTROL( 2666): static void* CtrlCommMgr::ProcessThreadProc(void*) -- 121: process cmd id:0x0000066a
I/AGNSSCONTROL( 2666): virtual void CtrlFSMWaitState::PGPSInjectGANSSAuxi(CtrlFSM&) -- 933: PGPSInjectGANSSAuxi cmd received by CtrlFSMWaitState
,I/art     ( 2929): Can not find class: Lcom/android/server/AppOpsService$1$1;
,I/ActivityManager( 2929): filter receiver for action = com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS
,I/art     ( 2929): Can not find class: Lcom/android/server/am/ActivityManagerService$24;
,I/art     ( 2929): Can not find class: Lcom/android/server/am/ProcessStatsService$2;
,I/HwLauncher( 3682): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3209): receiver action = android.intent.action.TIME_TICK
I/TimeManager( 3209): hand message 1
I/TimeManager( 3209): notify time change. size = 2
,I/TimeLayout( 3209): time = 18:42
,I/TimeLayout( 3209): updateDate date = 12/9/2015
,I/TimeLayout( 3209): weekDay = Wednesday
,I/HwSystemManager( 3468): aor:Network Stats Updated
I/HwSystemManager( 3468): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/art     ( 2929): Can not find class: Lcom/android/server/pm/PackageManagerService$PackageUsage$1;
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3468): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3468): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 3468): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3468): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3468): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3468): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/PG Utils( 5913): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,TIME-OUT KILL (timeout was 1800000ms)
```
