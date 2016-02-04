#### Test 575312431745da8_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/HeadsetStateMachine( 1224): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4447): 
D/AndroidRuntime( 4447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4447): CheckJNI is OFF
D/dalvikvm( 4447): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4447): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4447): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4447): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4447): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4447): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4447): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4447): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4447): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 4447): Shutting down VM
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4447
D/dalvikvm( 4447): GC_CONCURRENT freed 99K, 15% free 615K/716K, paused 0ms+0ms, total 2ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.603256 Y: -0.339310 Z: 9.803146 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.603256 .y:-0.339310 .z:9.803146
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.588745 Y: -0.335495 Z: 9.795990 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.588745 .y:-0.335495 .z:9.795990
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.576141 Y: -0.332581 Z: 9.778503 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576141 .y:-0.332581 .z:9.778503
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/ActivityManager(  962): Killing 3448:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433edf80 stackId=1, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2}
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2042): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/rmt_storage(  544): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb71db178
I/rmt_storage(  544): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  544): wakelock acquired: 1, error no: 42
,I/rmt_storage(  544): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222791448)
,I/rmt_storage(  544): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  544): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  544): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222791448) wakelock released: 1, error no: 0
I/rmt_storage(  544): 
I/rmt_storage(  544): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb71db178
,E/Diag_Lib(  672): [IMS_FATAL]| 2912 | 689 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.564224 Y: -0.343384 Z: 9.816177 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564224 .y:-0.343384 .z:9.816177
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.570282 Y: -0.334320 Z: 9.818161 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.570282 .y:-0.334320 .z:9.818161
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593080033, nextTick: 60000, mDrawingTime: 0
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593080034, nextTick: 59999, mDrawingTime: 0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.577713 Y: -0.343048 Z: 9.809845 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.577713 .y:-0.343048 .z:9.809845
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.565186 Y: -0.347275 Z: 9.805328 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565186 .y:-0.347275 .z:9.805328
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.565094 Y: -0.321091 Z: 9.817078 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565094 .y:-0.321091 .z:9.817078
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.566406 Y: -0.327087 Z: 9.827896 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.566406 .y:-0.327087 .z:9.827896
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8463 usec
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.561356 Y: -0.334625 Z: 9.841751 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.561356 .y:-0.334625 .z:9.841751
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.584427 Y: -0.329773 Z: 9.820007 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.584427 .y:-0.329773 .z:9.820007
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  322): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.571716 Y: -0.328568 Z: 9.813293 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571716 .y:-0.328568 .z:9.813293
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.548019 Y: -0.326309 Z: 9.820709 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.548019 .y:-0.326309 .z:9.820709
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.547409 Y: -0.331802 Z: 9.820190 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.547409 .y:-0.331802 .z:9.820190
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.557358 Y: -0.337280 Z: 9.818192 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.557358 .y:-0.337280 .z:9.818192
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.558807 Y: -0.330322 Z: 9.817688 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.558807 .y:-0.330322 .z:9.817688
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7496450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432f2b18)
,D/KeyguardViewMediator( 1139): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1139): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
D/KeyguardViewMediator( 1139): handleNotifyScreenOn
,D/KeyguardViewManager( 1139): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
I/WindowManager(  962): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2042): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2042): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2042): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2042): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
,E/SlideAside( 3694): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1153): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4327c120 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1153): enqueuing start. mLedList.size()=2
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1153): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1153): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1153): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1822): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:38:30
,I/SlideAside( 3694): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1822): 2 : This is isUpdating : false
,D/WeatherAncestor( 1822): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:38:30
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.565002 Y: -0.322189 Z: 9.820724 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565002 .y:-0.322189 .z:9.820724
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/WeatherService( 1822): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1822): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1822): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.565170 Y: -0.333099 Z: 9.824936 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565170 .y:-0.333099 .z:9.824936
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1153): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1153): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1153): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1153): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1153): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 410ms
D/qdlights( 1153): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1153): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1153): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1153): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593110393, nextTick: 29640, mDrawingTime: 0
D/qdlights( 1153): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1153): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1153): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1153): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 171, B = 171
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593110435, nextTick: 29598, mDrawingTime: 0
,D/qdlights( 1153): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 165, B = 165
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,D/qdlights( 1153): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1153): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 153, B = 153
D/WeatherService( 1822): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:38:30
,D/WeatherService( 1822): 2 : ACTION screen on
,D/WeatherService( 1822): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1822): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:38:30
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1153): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  533): Reading a NULL string not supported here.
E/Parcel  (  533): Reading a NULL string not supported here.
E/Parcel  (  533): Reading a NULL string not supported here.
,E/Parcel  (  533): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/qdlights( 1153): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
,D/qdlights( 1153): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 135, B = 135
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1139): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1139): notifyScreenOffLocked
D/qdlights( 1153): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 129, B = 129
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.559677 Y: -0.333893 Z: 9.821121 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559677 .y:-0.333893 .z:9.821121
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2}
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,D/qdlights( 1153): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 123, B = 123
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1153): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1153): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 111, B = 111
W/ProcessCpuTracker(  962): Skipping unknown process pid 4533
D/UsbSettingsControl( 2605): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettings( 2605): [AUTORUN] onPause() : mActiveCurrentFunction = boot
,D/KeyguardViewMediator( 1139): setting alarm to turn off keyguard, seq = 2, timeout = 5000
W/ProcessCpuTracker(  962): Skipping unknown process pid 4534
W/ProcessCpuTracker(  962): Skipping unknown process pid 4538
W/ProcessCpuTracker(  962): Skipping unknown process pid 4539
W/ProcessCpuTracker(  962): Skipping unknown process pid 4540
W/ProcessCpuTracker(  962): Skipping unknown process pid 4544
,D/qdlights( 1153): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 105, B = 105
,I/LGImmersionVibrator(  962): Vibrator off
,D/UsbSettings( 2605): [AUTORUN] onStop()
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/ActivityManager(  962): Not finishing noHistory ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2} (stop requested)
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{431fc338 u0 com.android.settings/.UsbSettings t2} (stop complete)
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/qdlights( 1153): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 99, B = 99
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2042): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2042): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  962): CMD_SCREEN_OFF 
,D/WifiController(  962): shouldWifiStayAwake TRUE
E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
D/KeyguardViewMediator( 1139): handleNotifyScreenOff
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
D/KeyguardViewManager( 1139): onScreenTurnedOff()
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/qdlights( 1153): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 93, B = 93
,I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/wpa_supplicant( 2042): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/qdlights( 1153): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 87, B = 87
,D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): handleMessage: X
,E/CliptrayService( 1153): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/VolumeVibrator( 1153): clear
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
,D/qdlights( 1153): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 81, B = 81
,I/[LGHome]EVENT( 1486): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1153): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 75, B = 75
D/WeatherService( 1822): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:38:30
D/WeatherService( 1822): 2 : ACTION screen off
,D/WeatherService( 1822): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:38:30
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  533): Reading a NULL string not supported here.
E/Parcel  (  533): Reading a NULL string not supported here.
E/Parcel  (  533): Reading a NULL string not supported here.
,E/Parcel  (  533): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/qdlights( 1153): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 69, B = 69
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1153): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 63, B = 63
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1471): NFC-C OFF
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/qdlights( 1153): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 57, B = 57
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1153): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1153): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1153): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1153): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1153): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1153): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1153): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1153): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1153): updateLightsLocked() start. mLedList.size=2
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  322): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1139): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1139): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/KeyguardViewMediator( 1139): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1139): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593128481183939; DSPS: 5280277; Offset: 1454592967339918070
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593140040, nextTick: 59992, mDrawingTime: 0
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593140054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593148482045860; DSPS: 5935665; Offset: 1454592967339925499
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593168482493369; DSPS: 6591040; Offset: 1454592967339915244
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1552): Vacuum at: now=1454593173098 tag=VacuumService
,I/GoogleURLConnFactory( 1552): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1552): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1552): GC_CONCURRENT freed 1828K, 28% free 18016K/24832K, paused 8ms+5ms, total 71ms
,W/Uploader( 1552): No account for auth token provided
,W/Uploader( 1552):  no longer exists, so no auth token.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1552): No account for auth token provided
,D/wpa_supplicant( 2042): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2042): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2042): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2042): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2042): wlan0: BSS: Remove id 3 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2042): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593188483446936; DSPS: 7246431; Offset: 1454592967339922767
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593200040, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593200047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593208483899302; DSPS: 7901806; Offset: 1454592967339917369
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593228484337140; DSPS: 8557181; Offset: 1454592967339897443
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593248484793392; DSPS: 9212555; Offset: 1454592967339926449
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593260039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593260042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593268485688725; DSPS: 9867945; Offset: 1454592967339906255
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593288486554562; DSPS: 10523333; Offset: 1454592967339917600
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x431c0c90: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4183): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4183): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4183): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4183): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4183): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4183): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4183): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4183): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4183): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4183): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593308486977850; DSPS: 11178707; Offset: 1454592967339913642
,I/LocationManagerService(  962): remove 432d9cc0
D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2657): GC_CONCURRENT freed 7734K, 32% free 16911K/24832K, paused 19ms+2ms, total 84ms
,D/dalvikvm( 2657): WAIT_FOR_CONCURRENT_GC blocked 68ms
,D/dalvikvm( 2657): GC_CONCURRENT freed 1821K, 31% free 17137K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2657): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Mlt MonitorService( 2657): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593320034, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593320037, nextTick: 59995, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593328490143336; DSPS: 11834171; Offset: 1454592967339905299
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593348490994071; DSPS: 12489559; Offset: 1454592967339901542
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593368491447153; DSPS: 13144934; Offset: 1454592967339896861
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593380034, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593380046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593388491898995; DSPS: 13800308; Offset: 1454592967339921456
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593408496891648; DSPS: 14455832; Offset: 1454592967339909227
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593428497319790; DSPS: 15111206; Offset: 1454592967339910123
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593440053, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593440056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593448497764796; DSPS: 15766581; Offset: 1454592967339897365
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593468498212296; DSPS: 16421955; Offset: 1454592967339917619
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593488499823448; DSPS: 17077368; Offset: 1454592967339911339
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593500046, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593500056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593508500268499; DSPS: 17732743; Offset: 1454592967339898626
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593528500704154; DSPS: 18388117; Offset: 1454592967339907035
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593548501637625; DSPS: 19043508; Offset: 1454592967339894461
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593560044, nextTick: 59977, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593560054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593568502082217; DSPS: 19698882; Offset: 1454592967339911807
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593588502940089; DSPS: 20354270; Offset: 1454592967339915187
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593608503401025; DSPS: 21009645; Offset: 1454592967339918359
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593620028, nextTick: 59989, mDrawingTime: 7
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593620051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593628510890008; DSPS: 21665251; Offset: 1454592967339900018
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593648512189921; DSPS: 22320653; Offset: 1454592967339918193
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593668513523433; DSPS: 22976057; Offset: 1454592967339908932
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593680046, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593680051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593688514434851; DSPS: 23631447; Offset: 1454592967339904822
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1224): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593708515798279; DSPS: 24286852; Offset: 1454592967339894959
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593728517127876; DSPS: 24942255; Offset: 1454592967339912300
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593740045, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593740054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593748518053450; DSPS: 25597645; Offset: 1454592967339922347
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593768519571696; DSPS: 26253055; Offset: 1454592967339914714
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593788520468250; DSPS: 26908444; Offset: 1454592967339926258
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593800029, nextTick: 60001, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593800048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593808521375797; DSPS: 27563834; Offset: 1454592967339918278
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593828522236813; DSPS: 28219222; Offset: 1454592967339924802
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593848522688614; DSPS: 28874597; Offset: 1454592967339918839
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593860035, nextTick: 59994, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593860038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593868523672158; DSPS: 29529990; Offset: 1454592967339895303
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593888525000235; DSPS: 30185393; Offset: 1454592967339911124
,D/Finsky  ( 4183): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,D/GCM     ( 1552): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4183): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4183): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 4183): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4183): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4183): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4183): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,D/dalvikvm(  962): GC_CONCURRENT freed 2742K, 10% free 28045K/30984K, paused 7ms+10ms, total 202ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593908525461535; DSPS: 30840768; Offset: 1454592967339914660
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4183): [396] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4183): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593920036, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593920045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593928526351630; DSPS: 31496157; Offset: 1454592967339919746
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593948527269247; DSPS: 32151547; Offset: 1454592967339921835
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593968527725996; DSPS: 32806922; Offset: 1454592967339920821
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593980054, nextTick: 59974, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454593980057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454593988528167936; DSPS: 33462297; Offset: 1454592967339904997
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594008529645997; DSPS: 34117705; Offset: 1454592967339918214
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594028530552282; DSPS: 34773095; Offset: 1454592967339908972
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594040060, nextTick: 59970, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594040061, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594048531457561; DSPS: 35428485; Offset: 1454592967339898724
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594068532323923; DSPS: 36083873; Offset: 1454592967339910593
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594088532814851; DSPS: 36739249; Offset: 1454592967339913240
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594100051, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594100054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594108533253705; DSPS: 37394623; Offset: 1454592967339924848
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594128534128044; DSPS: 38050012; Offset: 1454592967339914177
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594148534597779; DSPS: 38705387; Offset: 1454592967339926149
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594160079, nextTick: 59947, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594160084, nextTick: 59948, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594168535050593; DSPS: 39360762; Offset: 1454592967339921199
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594188535928241; DSPS: 40016151; Offset: 1454592967339913837
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594208536378822; DSPS: 40671526; Offset: 1454592967339906655
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594220032, nextTick: 59997, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1454594220054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594228536846749; DSPS: 41326901; Offset: 1454592967339916818
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1454594248537705631; DSPS: 41982289; Offset: 1454592967339921208
,TIME-OUT KILL (timeout was 1200000ms)
```
