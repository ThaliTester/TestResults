#### Test 58741471ee11130_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2646): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2018): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
E/BatteryObserver( 1158): usb Uevent not necessary.
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4506): 
D/AndroidRuntime( 4506): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4506): CheckJNI is OFF
D/dalvikvm( 4506): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4506): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4506): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4506): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4506): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4506): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4506): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4506): failed to load memtrack module: -2
D/AndroidRuntime( 4506): Calling main entry com.android.commands.am.Am
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4506): Shutting down VM
D/dalvikvm( 4506): GC_CONCURRENT freed 99K, 15% free 614K/716K, paused 0ms+0ms, total 3ms
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4506
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.565964 Y: -0.344635 Z: 9.823532 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.564850 Y: -0.332397 Z: 9.824646 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.565964 .y:-0.344635 .z:9.823532
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.573318 Y: -0.339355 Z: 9.819382 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573318 .y:-0.339355 .z:9.819382
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/ActivityManager(  967): Killing 3874:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43367158 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2}
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023220061, nextTick: 59972, mDrawingTime: 0
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023220061, nextTick: 59971, mDrawingTime: 0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/rmt_storage(  427): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb855f178
I/rmt_storage(  427): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  427): wakelock acquired: 1, error no: 42
,I/rmt_storage(  427): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1202327832)
,I/rmt_storage(  427): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  427): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  427): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1202327832) wakelock released: 1, error no: 0
I/rmt_storage(  427): 
I/rmt_storage(  427): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb855f178
,E/Diag_Lib(  683): [IMS_FATAL]| 2912 | 692 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.564178 Y: -0.365448 Z: 9.807007 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564178 .y:-0.365448 .z:9.807007
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.581512 Y: -0.339737 Z: 9.811325 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.581512 .y:-0.339737 .z:9.811325
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1158): usb Uevent not necessary.
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.555481 Y: -0.338272 Z: 9.825150 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.555481 .y:-0.338272 .z:9.825150
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.568619 Y: -0.324158 Z: 9.833496 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.568619 .y:-0.324158 .z:9.833496
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  415): Reading a NULL string not supported here.
,E/Parcel  (  415): Reading a NULL string not supported here.
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
E/Parcel  (  415): Reading a NULL string not supported here.
,E/Parcel  (  415): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.546906 Y: -0.337234 Z: 9.808670 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.546906 .y:-0.337234 .z:9.808670
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0,
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0,
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.553207 Y: -0.333862 Z: 9.827454 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.553207 .y:-0.333862 .z:9.827454
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0,
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 7135 usec
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,D/qcom_sensors_hal(  967): hal_acquire_resources
I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35,
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.571259 Y: -0.347748 Z: 9.836960 
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20,
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571259 .y:-0.347748 .z:9.836960
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0,
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.571594 Y: -0.341705 Z: 9.824692 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571594 .y:-0.341705 .z:9.824692
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  382): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.566238 Y: -0.355545 Z: 9.824387 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.566238 .y:-0.355545 .z:9.824387
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.555649 Y: -0.353241 Z: 9.818741 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.555649 .y:-0.353241 .z:9.818741
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.567749 Y: -0.334732 Z: 9.799896 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.567749 .y:-0.334732 .z:9.799896
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.562805 Y: -0.366852 Z: 9.821960 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.572754 Y: -0.342514 Z: 9.813110 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.562805 .y:-0.366852 .z:9.821960
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.564651 Y: -0.352127 Z: 9.828705 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564651 .y:-0.352127 .z:9.828705
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43148e98)
,D/KeyguardViewMediator( 1144): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1144): notifyScreenOnLocked
,D/KeyguardViewMediator( 1144): handleNotifyScreenOn
,D/KeyguardViewManager( 1144): onScreenTurnedOn()
V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
I/WindowManager(  967): No lock screen! windowToken=null
,D/SurfaceFlinger(  269): Screen released, type=0 flinger=0xb8bdb450
,D/qdhwcomposer(  269): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL,
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2018): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2018): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  273): ParamSet string: screen_state=on
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=on
V/voice   (  273): voice_set_parameters: enter: screen_state=on
,V/voice   (  273): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  273): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1158): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43043758 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WeatherAncestor( 1859): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:7:43
,E/SlideAside( 3756): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3756): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1859): 2 : This is isUpdating : false
,D/WeatherAncestor( 1859): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:7:43
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/WeatherService( 1859): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.562378 Y: -0.347549 Z: 9.824387 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.562378 .y:-0.347549 .z:9.824387
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/EmotionalLed( 1158): enqueuing start. mLedList.size()=2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1158): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.555466 Y: -0.350800 Z: 9.817261 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.555466 .y:-0.350800 .z:9.817261
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1158): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 255, B = 255
,D/qdhwcomposer(  269): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1158): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 249, B = 249
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1158): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 243, B = 243
,D/GlobalAccess( 1144): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1144): changeTargets() succeeded. size: 20
D/qdlights( 1158): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 237, B = 237
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023263835, nextTick: 16198, mDrawingTime: 0
,D/qdlights( 1158): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 231, B = 231
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023263852, nextTick: 16181, mDrawingTime: 0
D/qdlights( 1158): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 225, B = 225
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1158): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 219, B = 219
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1859): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:7:43
D/WeatherService( 1859): 2 : ACTION screen on
D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1859): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:7:43
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1158): set_light_notifications: 2,ff00d5d5,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 213, B = 213
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1158): set_light_notifications: 2,ff00cfcf,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 207, B = 207
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1144): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1144): notifyScreenOffLocked
,D/qdlights( 1158): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 201, B = 201
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2}
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
D/qdlights( 1158): set_light_notifications: 2,ff00c3c3,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 195, B = 195
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,D/UsbSettingsControl( 2588): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettings( 2588): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/qdlights( 1158): set_light_notifications: 2,ff00bdbd,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 189, B = 189
,D/KeyguardViewMediator( 1144): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  967): Vibrator off
W/ProcessCpuTracker(  967): Skipping unknown process pid 4589
W/ProcessCpuTracker(  967): Skipping unknown process pid 4590
W/ProcessCpuTracker(  967): Skipping unknown process pid 4592
W/ProcessCpuTracker(  967): Skipping unknown process pid 4598
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/ActivityManager(  967): Not finishing noHistory ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2} (stop requested)
D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1158): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 183, B = 183
,D/KeyguardViewMediator( 1144): handleNotifyScreenOff
,D/KeyguardViewManager( 1144): onScreenTurnedOff()
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{431d0500 u0 com.android.settings/.UsbSettings t2} (stop complete)
,D/UsbSettings( 2588): [AUTORUN] onStop()
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  273): ParamSet string: screen_state=off
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=off
V/voice   (  273): voice_set_parameters: enter: screen_state=off
V/voice   (  273): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  273): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/qdlights( 1158): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 177, B = 177
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
I/EmotionalLed( 1158): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1158): clear
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
E/CliptrayService( 1158): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
D/qdlights( 1158): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 171, B = 171
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1158): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 165, B = 165
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
D/PhoneInterfaceManager( 1450): [PhoneIntfMgr] sigLevel = 5
D/BubblePopupHelper( 1144): isShowingBubblePopup : false
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
E/Parcel  (  415): Reading a NULL string not supported here.
D/GsmSST  ( 1450): Emergency Service
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1450): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/WeatherService( 1859): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:7:43
D/WeatherService( 1859): 2 : ACTION screen off
D/WeatherService( 1859): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:7:43
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1158): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 159, B = 159
V/TelephonyAutoProfiling( 1450): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1450): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1450): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
D/NfcService( 1474): NFC-C OFF
D/qdlights( 1158): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1158): [Current] = 255, R = 0, G = 153, B = 153
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1158): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1158): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1158): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1158): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1158): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1158): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1158): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1158): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1158): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1158): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1158): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1158): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1158): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1158): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1158): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 63, B = 63
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/qdlights( 1158): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1158): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1158): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1158): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1158): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1158): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1158): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1158): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1158): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1158): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1158): set_light_notifications: 1,ff00ff00,500,2000,1
,I/EmotionalLed( 1158): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  382): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1144): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1144): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1144): OMADM Lock is OFF
,D/KeyguardViewMediator( 1144): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1144): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023280038, nextTick: 59994, mDrawingTime: 0
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023280040, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023281860820956; DSPS: 5279595; Offset: 1455023120740368076
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023301862188684; DSPS: 5935000; Offset: 1455023120740362513
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023321862605601; DSPS: 6590374; Offset: 1455023120740352184
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1552): Vacuum at: now=1455023326672 tag=VacuumService
,I/GoogleURLConnFactory( 1552): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1552): No account for auth token provided
,D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1552): No account for auth token provided
,D/dalvikvm( 1552): GC_CONCURRENT freed 1709K, 28% free 18027K/24832K, paused 4ms+5ms, total 43ms
,W/Uploader( 1552):  no longer exists, so no auth token.
,W/Uploader( 1552): No account for auth token provided
,D/wpa_supplicant( 2018): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 2 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023340037, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023340051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023341864058713; DSPS: 7245781; Offset: 1455023120740370969
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023361865388239; DSPS: 7901185; Offset: 1455023120740357722
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023381865817041; DSPS: 8556559; Offset: 1455023120740359278
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023400042, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023400056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023401866745421; DSPS: 9211949; Offset: 1455023120740372130
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023421868070593; DSPS: 9867353; Offset: 1455023120740354529
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023441868517004; DSPS: 10522727; Offset: 1455023120740373694
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023460030, nextTick: 59997, mDrawingTime: 3
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023460049, nextTick: 59984, mDrawingTime: 0
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x431b6ec8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4265): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4265): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4265): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4265): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4265): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4265): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4265): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4265): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/System  ( 4265): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4265): isDataSchedulerEnabled():false
D/libc    (  266): _dns_getaddrinfo: iptype =1
,D/libc    (  266): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023461869975605; DSPS: 11178135; Offset: 1455023120740367451
,I/LocationManagerService(  967): remove 430c6388
D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2646): GC_CONCURRENT freed 7649K, 32% free 17003K/24832K, paused 4ms+3ms, total 49ms
,D/dalvikvm( 2646): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 2646): GC_CONCURRENT freed 1796K, 31% free 17254K/24832K, paused 3ms+1ms, total 31ms
,D/dalvikvm( 2646): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/Mlt MonitorService( 2646): parseLastkmsg to dump
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023481871369506; DSPS: 11833541; Offset: 1455023120740357544
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023501872241817; DSPS: 12488929; Offset: 1455023120740375362
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023520034, nextTick: 59995, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023520050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023521873200150; DSPS: 13144321; Offset: 1455023120740357133
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023541874513546; DSPS: 13799724; Offset: 1455023120740358273
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023561875388090; DSPS: 14455113; Offset: 1455023120740347807
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023580044, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023580047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023581876316515; DSPS: 15110503; Offset: 1455023120740360705
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023601877644090; DSPS: 15765906; Offset: 1455023120740376024
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023621878498391; DSPS: 16421294; Offset: 1455023120740375833
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023640037, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023640046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023641881504268; DSPS: 17076753; Offset: 1455023120740360470
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023661882813461; DSPS: 17732156; Offset: 1455023120740357407
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023681883680170; DSPS: 18387544; Offset: 1455023120740369624
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023700052, nextTick: 59971, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023700058, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023701884593499; DSPS: 19042934; Offset: 1455023120740367425
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023721885916475; DSPS: 19698337; Offset: 1455023120740378145
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023741886782636; DSPS: 20353726; Offset: 1455023120740359297
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023760045, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023760048, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023761888241693; DSPS: 21009134; Offset: 1455023120740353510
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023781889146509; DSPS: 21664523; Offset: 1455023120740373316
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023801890022017; DSPS: 22319912; Offset: 1455023120740363814
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023820039, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023820042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023821891038420; DSPS: 22975305; Offset: 1455023120740373137
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023841892367710; DSPS: 23630709; Offset: 1455023120740359654
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023861893225851; DSPS: 24286097; Offset: 1455023120740363303
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023880042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023880045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023881893690899; DSPS: 24941472; Offset: 1455023120740370587
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023901894155425; DSPS: 25596847; Offset: 1455023120740377349
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023921894607834; DSPS: 26252222; Offset: 1455023120740371995
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023940039, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455023940049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023941895064798; DSPS: 26907597; Offset: 1455023120740371195
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023961895532059; DSPS: 27562972; Offset: 1455023120740380692
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455023981896414104; DSPS: 28218361; Offset: 1455023120740377728
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024000033, nextTick: 59972, mDrawingTime: 11
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024000053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024001897333341; DSPS: 28873751; Offset: 1455023120740381437
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024021898185928; DSPS: 29529140; Offset: 1455023120740349014
,I/Vold    (  261): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1144): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1144): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024041899725001; DSPS: 30184550; Offset: 1455023120740362209
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/EventLogService( 1963): Aggregate from 1455023153513 (log), 1455021741545 (data)
,D/GCM     ( 1552): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/BubblePopupHelper( 1144): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024060042, nextTick: 59983, mDrawingTime: 6
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024060056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024061900650690; DSPS: 30839940; Offset: 1455023120740372370
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024081901071429; DSPS: 31495314; Offset: 1455023120740365863
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024101901958483; DSPS: 32150703; Offset: 1455023120740367907
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024120061, nextTick: 59969, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024120062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024121902411111; DSPS: 32806078; Offset: 1455023120740362772
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024141902869600; DSPS: 33461453; Offset: 1455023120740363497
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024161903744591; DSPS: 34116842; Offset: 1455023120740353478
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024180052, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024180055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024181904220107; DSPS: 34772217; Offset: 1455023120740371231
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024201904670038; DSPS: 35427592; Offset: 1455023120740363398
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024221905108930; DSPS: 36082966; Offset: 1455023120740375044
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024240044, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024240057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024241905579330; DSPS: 36738342; Offset: 1455023120740357163
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024261906465988; DSPS: 37393731; Offset: 1455023120740358811
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024281907333878; DSPS: 38049119; Offset: 1455023120740372209
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024300040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024300043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024301907780012; DSPS: 38704494; Offset: 1455023120740360579
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024321910679022; DSPS: 39359949; Offset: 1455023120740360419
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024341911103340; DSPS: 40015323; Offset: 1455023120740357491
,D/KeyguardUpdateMonitor( 1144): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1144): handleTimeUpdate
,D/KeyguardModel( 1144): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024360039, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1144): Clock updated, drawingStartTime : 1455024360044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024361912009017; DSPS: 40670712; Offset: 1455023120740378158
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024381913371845; DSPS: 41326117; Offset: 1455023120740367695
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1455024401913797653; DSPS: 41981491; Offset: 1455023120740366257
,TIME-OUT KILL (timeout was 1200000ms)
```
