#### Test 584164489c56086_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
--------- beginning of /dev/log/system
D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 4535): 
D/AndroidRuntime( 4535): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4535): CheckJNI is OFF
D/dalvikvm( 4535): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4535): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4535): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4535): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4535): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4535): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  961): battery changed pluggedType: 2
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4535): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4535): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4535): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4535
D/AndroidRuntime( 4535): Shutting down VM
D/dalvikvm( 4535): GC_CONCURRENT freed 99K, 15% free 615K/716K, paused 0ms+0ms, total 2ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,E/ThermalEngine(  283): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,W/ContextImpl( 2628): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/ActivityManager(  961): Killing 3829:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431671f0 stackId=1, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560547 Y: -0.351120 Z: 9.797989 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560547 .y:-0.351120 .z:9.797989
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.575699 Y: -0.331192 Z: 9.826111 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.575699 .y:-0.331192 .z:9.826111
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/rmt_storage(  481): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb762a178
I/rmt_storage(  481): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  481): wakelock acquired: 1, error no: 42
,I/rmt_storage(  481): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218273560)
,I/rmt_storage(  481): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  481): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  481): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218273560) wakelock released: 1, error no: 0
I/rmt_storage(  481): 
I/rmt_storage(  481): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb762a178
,E/Diag_Lib(  691): [IMS_FATAL]| 2912 | 699 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009660043, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009660056, nextTick: 59976, mDrawingTime: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.573425 Y: -0.345047 Z: 9.825195 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573425 .y:-0.345047 .z:9.825195
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.568985 Y: -0.352829 Z: 9.809448 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.568985 .y:-0.352829 .z:9.809448
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  283): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL,
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.576752 Y: -0.345963 Z: 9.815414 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576752 .y:-0.345963 .z:9.815414
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.582474 Y: -0.329834 Z: 9.837265 
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.562500 Y: -0.334274 Z: 9.812836 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.582474 .y:-0.329834 .z:9.837265,
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,E/ThermalEngine(  283): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.555344 Y: -0.323624 Z: 9.819366 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.555344 .y:-0.323624 .z:9.819366
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.570862 Y: -0.310547 Z: 9.841415 
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.587524 Y: -0.342712 Z: 9.835861 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.570862 .y:-0.310547 .z:9.841415
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
,D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9059 usec
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560165 Y: -0.321762 Z: 9.830109 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560165 .y:-0.321762 .z:9.830109
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  442): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.563858 Y: -0.316223 Z: 9.819351 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.563858 .y:-0.316223 .z:9.819351
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560349 Y: -0.339935 Z: 9.817413 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560349 .y:-0.339935 .z:9.817413
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.575333 Y: -0.324829 Z: 9.828491 
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.550934 Y: -0.335922 Z: 9.850677 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.575333 .y:-0.324829 .z:9.828491
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.553391 Y: -0.319138 Z: 9.837738 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.553391 .y:-0.319138 .z:9.837738
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.556870 Y: -0.323914 Z: 9.833572 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.556870 .y:-0.323914 .z:9.833572
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42e62d20)
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb82e8450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1141): notifyScreenOnLocked
D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  961): No lock screen! windowToken=null
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.560196 Y: -0.323349 Z: 9.815033 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560196 .y:-0.323349 .z:9.815033
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,E/SlideAside( 4002): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  961): handleScreenStateChanged: true
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2016): wlan0: Control interface command 'SIGNAL_POLL'
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/wpa_supplicant( 2016): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131127
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  961): handleMessage: E msg.what=132097
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  961): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2016): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2016): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4330c9a0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1886): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:21:39
,I/SlideAside( 4002): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1886): 2 : This is isUpdating : false
,D/WeatherAncestor( 1886): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:21:39
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1886): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 399ms
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009700199, nextTick: 19829, mDrawingTime: 4
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009700232, nextTick: 19801, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
D/WeatherService( 1886): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:21:40
,D/WeatherService( 1886): 2 : ACTION screen on
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1886): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:21:40
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
E/Parcel  (  468): Reading a NULL string not supported here.
E/Parcel  (  468): Reading a NULL string not supported here.
E/Parcel  (  468): Reading a NULL string not supported here.
,E/Parcel  (  468): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_ON
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2}
D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,W/ProcessCpuTracker(  961): Skipping unknown process pid 4632
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/UsbSettingsControl( 2576): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2576): [AUTORUN] onPause() : mActiveCurrentFunction = boot
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  961): Vibrator off
W/ProcessCpuTracker(  961): Skipping unknown process pid 4634
W/ProcessCpuTracker(  961): Skipping unknown process pid 4640
,V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/UsbSettings( 2576): [AUTORUN] onStop()
D/ActivityManager(  961): Not finishing noHistory ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2} (stop requested)
D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
D/wpa_supplicant( 2016): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2016): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/WifiController(  961): CMD_SCREEN_OFF 
D/WifiController(  961): shouldWifiStayAwake TRUE
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{433ca548 u0 com.android.settings/.UsbSettings t2} (stop complete)
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
,D/wpa_supplicant( 2016): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  961):    returned true
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
D/WifiStateMachine(  961): handleMessage: X
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
D/WeatherService( 1886): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:21:40
,D/WeatherService( 1886): 2 : ACTION screen off
,D/WeatherService( 1886): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:21:40
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,E/Parcel  (  468): Reading a NULL string not supported here.
E/Parcel  (  468): Reading a NULL string not supported here.
E/Parcel  (  468): Reading a NULL string not supported here.
,E/Parcel  (  468): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/NfcService( 1475): NFC-C OFF
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  442): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  283): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009718073414159; DSPS: 5272933; Offset: 1455009557156269384
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009720036, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009720043, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009738073869642; DSPS: 5928308; Offset: 1455009557156267103
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009758074306921; DSPS: 6583682; Offset: 1455009557156277136
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1535): Vacuum at: now=1455009762829 tag=VacuumService
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1535): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1535): GC_CONCURRENT freed 1836K, 28% free 18038K/24836K, paused 4ms+6ms, total 76ms
,D/dalvikvm( 1535): WAIT_FOR_CONCURRENT_GC blocked 10ms
,W/Uploader( 1535): No account for auth token provided
,W/Uploader( 1535):  no longer exists, so no auth token.
,W/Uploader( 1535): No account for auth token provided
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009778075466130; DSPS: 7239080; Offset: 1455009557156276677
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009780045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009780054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009798075911070; DSPS: 7894455; Offset: 1455009557156263854
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009818076376160; DSPS: 8549830; Offset: 1455009557156271180
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009838077261992; DSPS: 9205219; Offset: 1455009557156272002
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009840033, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009840041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009858077704612; DSPS: 9860593; Offset: 1455009557156287376
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009878078143820; DSPS: 10515968; Offset: 1455009557156268820
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43107360: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1535): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1535): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1535): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1535): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1535): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4202): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4202): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4202): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4202): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4202): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4202): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4202): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4202): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4202): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4202): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009898079092924; DSPS: 11171359; Offset: 1455009557156271880
,I/LocationManagerService(  961): remove 43164fa0
,D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009900038, nextTick: 59970, mDrawingTime: 10
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009900055, nextTick: 59978, mDrawingTime: 0
,D/dalvikvm( 2628): GC_CONCURRENT freed 7683K, 32% free 16953K/24836K, paused 4ms+3ms, total 50ms
,D/dalvikvm( 2628): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 2628): GC_CONCURRENT freed 1788K, 31% free 17213K/24836K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2628): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2628): GC_CONCURRENT freed 1866K, 30% free 17393K/24836K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2628): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/Mlt MonitorService( 2628): parseLastkmsg to dump
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009918079533169; DSPS: 11826733; Offset: 1455009557156284878
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009938079977519; DSPS: 12482108; Offset: 1455009557156271465
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009958080430503; DSPS: 13137483; Offset: 1455009557156266685
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009960031, nextTick: 59983, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455009960055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009978082852629; DSPS: 13792922; Offset: 1455009557156277922
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455009998083276424; DSPS: 14448296; Offset: 1455009557156274471
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010018083725723; DSPS: 15103671; Offset: 1455009557156266007
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010020031, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010020056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010038084600692; DSPS: 15759059; Offset: 1455009557156286484
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010058085036709; DSPS: 16414433; Offset: 1455009557156295254
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010078085490988; DSPS: 17069808; Offset: 1455009557156291770
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010080048, nextTick: 59966, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010080059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010098085930050; DSPS: 17725183; Offset: 1455009557156273068
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010118086374003; DSPS: 18380557; Offset: 1455009557156289775
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010138087293830; DSPS: 19035948; Offset: 1455009557156263557
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010140045, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010140055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010158087713449; DSPS: 19691321; Offset: 1455009557156286448
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010178088586869; DSPS: 20346710; Offset: 1455009557156274858
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010198089044402; DSPS: 21002085; Offset: 1455009557156274627
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010200043, nextTick: 59975, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010200053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010218089484784; DSPS: 21657459; Offset: 1455009557156287763
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010238089935896; DSPS: 22312834; Offset: 1455009557156281111
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010258091474205; DSPS: 22968245; Offset: 1455009557156263024
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010260045, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010260052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010278091902036; DSPS: 23623619; Offset: 1455009557156263609
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010298092764953; DSPS: 24279007; Offset: 1455009557156272034
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010318093215689; DSPS: 24934382; Offset: 1455009557156265006
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010320044, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010320055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010338093668101; DSPS: 25589756; Offset: 1455009557156290172
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010358094120932; DSPS: 26245131; Offset: 1455009557156285239
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010378094571688; DSPS: 26900506; Offset: 1455009557156278231
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010380046, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010380054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010398095022478; DSPS: 27555881; Offset: 1455009557156271258
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010418095895841; DSPS: 28211270; Offset: 1455009557156259611
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010438096360462; DSPS: 28866645; Offset: 1455009557156266468
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010440049, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010440053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010458096817357; DSPS: 29522020; Offset: 1455009557156265600
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010478097278649; DSPS: 30177395; Offset: 1455009557156269128
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1535): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010498097722954; DSPS: 30832769; Offset: 1455009557156286187
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010500042, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010500055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010518098164611; DSPS: 31488144; Offset: 1455009557156270080
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010538099057550; DSPS: 32143533; Offset: 1455009557156278009
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010558099506946; DSPS: 32798908; Offset: 1455009557156269642
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010560048, nextTick: 59968, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010560057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010578099952894; DSPS: 33454283; Offset: 1455009557156257826
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010598106016898; DSPS: 34109841; Offset: 1455009557156279350
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010618106937213; DSPS: 34765231; Offset: 1455009557156284137
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010620047, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010620055, nextTick: 59978, mDrawingTime: 0,
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010638107371636; DSPS: 35420605; Offset: 1455009557156291314
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010658107817861; DSPS: 36075980; Offset: 1455009557156279776
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010678108788167; DSPS: 36731372; Offset: 1455009557156273519
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010680047, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010680054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010698109709768; DSPS: 37386762; Offset: 1455009557156279593
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010718110155954; DSPS: 38042137; Offset: 1455009557156268015
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010738110614073; DSPS: 38697512; Offset: 1455009557156268370
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010740048, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010740054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010758111615126; DSPS: 39352905; Offset: 1455009557156262343
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010778112507710; DSPS: 40008294; Offset: 1455009557156269918
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010798112960365; DSPS: 40663669; Offset: 1455009557156264809
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010800046, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1455010800052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010818121144233; DSPS: 41319297; Offset: 1455009557156269966
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1455010838121998096; DSPS: 41974685; Offset: 1455009557156269337
,TIME-OUT KILL (timeout was 1200000ms)
```
