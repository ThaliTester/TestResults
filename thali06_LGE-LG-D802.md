#### Test 5753124305d96c2_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
D/WeatherService( 1844): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:16:0
D/WeatherService( 1844): 2 : TimeTick Intent And Screen On
D/WeatherService( 1844): 2 : SDK version : 19
D/WeatherQuickCover( 1844): 2 : quick cover state : opened : 0
D/Weather.Utils( 1844): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1844): 2 : Utils getTopActivity com.lge.easyhome / false
D/WeatherService( 1844): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1844): 2 : TimeTick Receiver Unregister
D/WeatherService( 1844): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:16:0
D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422560033, nextTick: 59999, mDrawingTime: 0
D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422560035, nextTick: 59998, mDrawingTime: 0
D/WifiStateMachine(  956): handleMessage: E msg.what=131155
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  956): handleMessage: X
--------- beginning of /dev/log/system
W/ContextImpl( 2667): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4564): 
D/AndroidRuntime( 4564): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4564): CheckJNI is OFF
D/dalvikvm( 4564): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4564): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4564): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4564): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4564): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4564): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4564): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4564): failed to load memtrack module: -2
D/AndroidRuntime( 4564): Calling main entry com.android.commands.am.Am
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4564): Shutting down VM
D/dalvikvm( 4564): GC_CONCURRENT freed 99K, 15% free 615K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  956): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4564
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.591064 Y: -0.354691 Z: 9.793121 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.591064 .y:-0.354691 .z:9.793121
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.582657 Y: -0.350540 Z: 9.787720 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.582657 .y:-0.350540 .z:9.787720
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  956): Killing 3878:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  956): resumeTopActivitiesLocked(): target Stack:ActivityStack{432b2258 stackId=1, 1 tasks}
,D/ActivityManager(  956): resumeTopActivityLocked: Top activity resumed ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2}
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/rmt_storage(  424): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8c53178
I/rmt_storage(  424): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  424): wakelock acquired: 1, error no: 42
,I/rmt_storage(  424): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1195036952)
,I/rmt_storage(  424): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  424): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  424): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1195036952) wakelock released: 1, error no: 0
I/rmt_storage(  424): 
I/rmt_storage(  424): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8c53178
,E/Diag_Lib(  697): [IMS_FATAL]| 2912 | 705 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.579605 Y: -0.323715 Z: 9.804932 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579605 .y:-0.323715 .z:9.804932
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.576385 Y: -0.339661 Z: 9.806000 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576385 .y:-0.339661 .z:9.806000
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13,
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.567825 Y: -0.329086 Z: 9.809326 ,
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.567825 .y:-0.329086 .z:9.809326
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.559738 Y: -0.354996 Z: 9.795517 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559738 .y:-0.354996 .z:9.795517
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,E/ThermalEngine(  290): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.571411 Y: -0.341553 Z: 9.830444 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571411 .y:-0.341553 .z:9.830444
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.569122 Y: -0.329208 Z: 9.810547 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569122 .y:-0.329208 .z:9.810547,
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
,D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.565155 Y: -0.333267 Z: 9.836517 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565155 .y:-0.333267 .z:9.836517
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.579483 Y: -0.341690 Z: 9.820221 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579483 .y:-0.341690 .z:9.820221
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,I/PowerManagerService(  956): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  956): [updateScreenState] screen on = false
D/KnockOnPowerController(  956): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  956): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  956): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  956): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  956): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  956): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  956): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8528 usec
,D/qcom_sensors_hal(  956): hal_acquire_resources
,I/qcom_sensors_hal(  956): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  956): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  956): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  956): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  956): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  956): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  956): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.589249 Y: -0.354889 Z: 9.823532 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.589249 .y:-0.354889 .z:9.823532
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.573227 Y: -0.346573 Z: 9.815750 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573227 .y:-0.346573 .z:9.815750
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,I/Sensors (  323): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  956): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  956): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  956): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  956): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  956): proximitySensorChanged  positive = true
I/KnockOnPowerController(  956): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.562439 Y: -0.352875 Z: 9.831161 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.562439 .y:-0.352875 .z:9.831161
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.574493 Y: -0.348434 Z: 9.811401 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.574493 .y:-0.348434 .z:9.811401
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0,
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.582718 Y: -0.340256 Z: 9.807709 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.582718 .y:-0.340256 .z:9.807709
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.566360 Y: -0.336472 Z: 9.834641 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.566360 .y:-0.336472 .z:9.834641
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  956): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42d44160)
,D/SurfaceFlinger(  272): Screen released, type=0 flinger=0xb8143450
,D/qdhwcomposer(  272): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
V/KeyguardServiceDelegate(  956): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,I/WindowManager(  956): No lock screen! windowToken=null
V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.560425 Y: -0.334854 Z: 9.838226 
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560425 .y:-0.334854 .z:9.838226
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,E/SlideAside( 4061): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  956): handleScreenStateChanged: true
D/WifiStateMachine(  956): handleMessage: E msg.what=131154
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  956): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  956): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  956): stopMonitoring
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131127
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): handleMessage: X
,D/WifiStateMachine(  956): handleMessage: E msg.what=131158
,D/WifiStateMachine(  956): processMsg: ConnectedState
,D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
,D/WifiStateMachine(  956): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  956): handleMessage: X
,D/WifiStateMachine(  956): handleMessage: E msg.what=132097
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): processMsg: ConnectModeState
D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  956): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2019): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  956): handleMessage: X
,E/AudioSystem(  956): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 956
V/SRS_Proc(  275): ParamSet string: screen_state=on
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
,V/voice   (  275): voice_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43280dc0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WeatherAncestor( 1844): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:16:57
,I/SlideAside( 4061): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1844): 2 : This is isUpdating : false
,D/WeatherAncestor( 1844): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:16:57
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1844): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1844): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1844): 2 : shouldTimeTickRegistered : false
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdhwcomposer(  272): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  956): Excessive delay in blankDisplay() while turning screen off: 400ms
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422617574, nextTick: 2459, mDrawingTime: 0
D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422617606, nextTick: 2427, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
D/WeatherService( 1844): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:16:57
,D/WeatherService( 1844): 2 : ACTION screen on
,D/WeatherService( 1844): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1844): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:16:57
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  412): Reading a NULL string not supported here.
E/Parcel  (  412): Reading a NULL string not supported here.
E/Parcel  (  412): Reading a NULL string not supported here.
,E/Parcel  (  412): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  956): ACTION_SCREEN_ON
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  956): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  956): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  956): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  956): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  956): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  956): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  956): hal_process_report_ind: X: -0.574600 Y: -0.320877 Z: 9.842880 
,D/qcom_sensors_hal(  956): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.574600 .y:-0.320877 .z:9.842880
,V/ActivityManager(  956): Moving to PAUSING: ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2}
D/qcom_sensors_hal(  956): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  956): hal_acquire_resources
D/qcom_sensors_hal(  956): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  956): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  956): hal_wait_for_response: timeout=1000
D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,V/qcom_sensors_hal(  956): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  956): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  956): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  956): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/UsbSettingsControl( 2604): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettings( 2604): [AUTORUN] onPause() : mActiveCurrentFunction = boot
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  956): Vibrator off
D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
,D/UsbSettings( 2604): [AUTORUN] onStop()
V/ActivityManager(  956): Moving to PAUSED: ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/ActivityManager(  956): Not finishing noHistory ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
V/ActivityManager(  956): Moving to STOPPING: ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2} (stop requested)
,D/WifiStateMachine(  956): handleScreenStateChanged: false
D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
D/WifiStateMachine(  956): handleMessage: E msg.what=131154
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
D/WifiStateMachine(  956): handleMessage: E msg.what=131158
D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
D/WifiStateMachine(  956): processMsg: ConnectModeState
,D/WifiStateMachine(  956): processMsg: DriverStartedState
D/WifiStateMachine(  956): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  956): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  956): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 956
V/SRS_Proc(  275): ParamSet string: screen_state=off
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  275): platform_set_parameters: exit with code(-2)
V/ActivityManager(  956): Moving to STOPPED: ActivityRecord{43125e90 u0 com.android.settings/.UsbSettings t2} (stop complete)
D/WifiController(  956): CMD_SCREEN_OFF 
,D/WifiController(  956): shouldWifiStayAwake TRUE
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/VolumeVibrator( 1154): clear
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  956):    returned true
D/WifiStateMachine(  956): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1844): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:16:57
,D/WeatherService( 1844): 2 : ACTION screen off
,D/WeatherService( 1844): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:16:57
,V/TelephonyAutoProfiling(  956): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  412): Reading a NULL string not supported here.
,E/Parcel  (  412): Reading a NULL string not supported here.
E/Parcel  (  412): Reading a NULL string not supported here.
E/Parcel  (  412): Reading a NULL string not supported here.
D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/NfcService( 1473): NFC-C OFF
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  956): ACTION_SCREEN_OFF
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  323): sns_pwr.c(320):releasing wakelock
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422620040, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422620053, nextTick: 59979, mDrawingTime: 0
,D/WifiStateMachine(  956): handleMessage: E msg.what=131155
,D/WifiStateMachine(  956): processMsg: ConnectedState
D/WifiStateMachine(  956): processMsg: L2ConnectedState
,D/WifiStateMachine(  956): handleMessage: X
,E/ThermalEngine(  290): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422635460285119; DSPS: 5291588; Offset: 1454422473973834924
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422655461652854; DSPS: 5946993; Offset: 1454422473973829368
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422675462083226; DSPS: 6602367; Offset: 1454422473973832494
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422680029, nextTick: 60001, mDrawingTime: 3,
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422680051, nextTick: 59982, mDrawingTime: 0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1942): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/VacuumService( 1532): Vacuum at: now=1454422680290 tag=VacuumService
,I/GoogleURLConnFactory( 1532): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1532): No account for auth token provided
,D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1532): GC_CONCURRENT freed 1762K, 28% free 17989K/24836K, paused 4ms+6ms, total 43ms
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1532):  no longer exists, so no auth token.
,W/Uploader( 1532): No account for auth token provided
,D/wpa_supplicant( 2019): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 4 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 5 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a],
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  956): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422695469254234; DSPS: 7257962; Offset: 1454422473973831871
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422715469704234; DSPS: 7913336; Offset: 1454422473973854625
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422735470580735; DSPS: 8568725; Offset: 1454422473973846116
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422740037, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422740056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422755473139014; DSPS: 9224169; Offset: 1454422473973840919
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422775473571531; DSPS: 9879543; Offset: 1454422473973846190
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  956): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422795474479473; DSPS: 10534933; Offset: 1454422473973838604
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422800029, nextTick: 59985, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422800055, nextTick: 59975, mDrawingTime: 1
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  956): updateLightListLocked :r=NotificationRecord(0x431bce18: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  956): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1532): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1532): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1532): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1532): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1532): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4253): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4253): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4253): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4253): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4253): isDataSchedulerEnabled():false
D/libc    (  269): _dns_getaddrinfo: iptype =1
,D/libc    (  269): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422815475817376; DSPS: 11190337; Offset: 1454422473973833734
,D/LocationManagerService(  956): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  956): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  956): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/LocationManagerService(  956): remove 43296578
,D/LocationManagerService(  956): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  956): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2667): GC_CONCURRENT freed 7590K, 32% free 17063K/24836K, paused 3ms+2ms, total 49ms
,D/dalvikvm( 2667): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 2667): GC_FOR_ALLOC freed 1671K, 31% free 17254K/24836K, paused 22ms, total 22ms
,I/Mlt MonitorService( 2667): parseLastkmsg to dump
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422835477189207; DSPS: 11845742; Offset: 1454422473973832274
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422855478039597; DSPS: 12501129; Offset: 1454422473973858689
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422860024, nextTick: 60001, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422860054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422875479501543; DSPS: 13156537; Offset: 1454422473973855792
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422895480366943; DSPS: 13811926; Offset: 1454422473973836182
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422915480787350; DSPS: 14467300; Offset: 1454422473973829343
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422920035, nextTick: 59988, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422920057, nextTick: 59971, mDrawingTime: 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422935483651985; DSPS: 15122753; Offset: 1454422473973855843
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422955484111439; DSPS: 15778128; Offset: 1454422473973857533
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422975484979833; DSPS: 16433517; Offset: 1454422473973840917
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422980051, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454422980053, nextTick: 59976, mDrawingTime: 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454422995485915561; DSPS: 17088908; Offset: 1454422473973830601
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423015486353119; DSPS: 17744282; Offset: 1454422473973840912
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423035487219771; DSPS: 18399670; Offset: 1454422473973853072
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423040050, nextTick: 59967, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423040061, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423055489255220; DSPS: 19055097; Offset: 1454422473973843844
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423075489680235; DSPS: 19710471; Offset: 1454422473973841612
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423095491092483; DSPS: 20365877; Offset: 1454422473973850052
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423100080, nextTick: 59946, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423100084, nextTick: 59947, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423115491989918; DSPS: 21021267; Offset: 1454422473973831960
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423135492436593; DSPS: 21676641; Offset: 1454422473973851388
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423155493325868; DSPS: 22332030; Offset: 1454422473973855654
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423160042, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423160049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423175494721735; DSPS: 22987436; Offset: 1454422473973847712
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423195495150737; DSPS: 23642810; Offset: 1454422473973849468
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423215496015242; DSPS: 24298198; Offset: 1454422473973859481
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423220043, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423220053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423235497462213; DSPS: 24953606; Offset: 1454422473973841608
,D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423255497894324; DSPS: 25608980; Offset: 1454422473973846473
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  956): battery changed pluggedType: 2
,W/Settings(  956): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  956): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423275499251365; DSPS: 26264385; Offset: 1454422473973830223
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423280040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423280043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423295500179106; DSPS: 26919775; Offset: 1454422473973842437
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423315500622708; DSPS: 27575149; Offset: 1454422473973858792
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423335501499892; DSPS: 28230538; Offset: 1454422473973850967
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423340042, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423340054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423355502426580; DSPS: 28885929; Offset: 1454422473973831610
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423375502883780; DSPS: 29541304; Offset: 1454422473973831046
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423395503753223; DSPS: 30196692; Offset: 1454422473973845997
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423400039, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423400053, nextTick: 59978, mDrawingTime: 1
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  956): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  956): Done.
,D/QcConnectivityService(  956): Setting timer for 720seconds
,I/GCM     ( 1942): Message from null null
,E/GCM     ( 1942): Dropping message from null
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1532): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  264): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  956): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  956): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423415504726230; DSPS: 30852084; Offset: 1454422473973842441
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423435505191775; DSPS: 31507459; Offset: 1454422473973850223
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423455506507960; DSPS: 32162863; Offset: 1454422473973823634
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423460056, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423460060, nextTick: 59971, mDrawingTime: 1,
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423475507434090; DSPS: 32818253; Offset: 1454422473973834237
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423495507872643; DSPS: 33473627; Offset: 1454422473973845544
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423515510787465; DSPS: 34129083; Offset: 1454422473973830678
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423520029, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423520052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423535512160726; DSPS: 34784488; Offset: 1454422473973830648
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423555512585992; DSPS: 35439862; Offset: 1454422473973828668
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423575513468456; DSPS: 36095251; Offset: 1454422473973826123
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423580044, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423580053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423595514418444; DSPS: 36750642; Offset: 1454422473973830066
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423615514854330; DSPS: 37406016; Offset: 1454422473973838705
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423635515718099; DSPS: 38061404; Offset: 1454422473973847982
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423640040, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423640047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423655516705571; DSPS: 38716796; Offset: 1454422473973858892
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423675517152370; DSPS: 39372171; Offset: 1454422473973847927
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423695518021986; DSPS: 40027560; Offset: 1454422473973832533
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423700042, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423700057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423715519047829; DSPS: 40682953; Offset: 1454422473973851296
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423735519915264; DSPS: 41338342; Offset: 1454422473973833722
,D/qcom_sensors_hal(  956): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  956): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  956): hal_ts_offset_is: Apps: 1454423755520791691; DSPS: 41993730; Offset: 1454422473973855656
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423760054, nextTick: 59974, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1454423760057, nextTick: 59974, mDrawingTime: 1
,TIME-OUT KILL (timeout was 1200000ms)
```
