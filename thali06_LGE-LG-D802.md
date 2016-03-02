#### Test 61432979123161a_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
,D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
--------- beginning of /dev/log/system
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
W/ContextImpl( 2618): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/AndroidRuntime( 3984): 
D/AndroidRuntime( 3984): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3984): CheckJNI is OFF
D/dalvikvm( 3984): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3984): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3984): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3984): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3984): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3984): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3984): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3984): failed to load memtrack module: -2
D/AndroidRuntime( 3984): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 3984): Shutting down VM
D/dalvikvm( 3984): GC_CONCURRENT freed 99K, 15% free 615K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3984
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/ActivityManager(  963): Killing 3449:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432eae30 stackId=1, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2}
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.389709 Y: -0.317383 Z: 9.848587 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.389709 .y:-0.317383 .z:9.848587
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.387146 Y: -0.298126 Z: 9.872971 
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13,
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.399353 Y: -0.292587 Z: 9.833008 ,
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.387146 .y:-0.298126 .z:9.872971,
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36,
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/rmt_storage(  421): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb849a178
I/rmt_storage(  421): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  421): wakelock acquired: 1, error no: 42
,I/rmt_storage(  421): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203134744)
,I/rmt_storage(  421): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  421): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  421): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203134744) wakelock released: 1, error no: 0
I/rmt_storage(  421): 
I/rmt_storage(  421): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb849a178
,E/Diag_Lib(  754): [IMS_FATAL]| 2912 | 762 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.380066 Y: -0.289139 Z: 9.827087 
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.402252 Y: -0.299133 Z: 9.864822 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.380066 .y:-0.289139 .z:9.827087
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.372589 Y: -0.295380 Z: 9.814713 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.372589 .y:-0.295380 .z:9.814713
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940280057, nextTick: 59970, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940280062, nextTick: 59970, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.377899 Y: -0.304382 Z: 9.874130 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.377899 .y:-0.304382 .z:9.874130
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.401154 Y: -0.306122 Z: 9.860641 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.401154 .y:-0.306122 .z:9.860641
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.378952 Y: -0.320938 Z: 9.858215 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.378952 .y:-0.320938 .z:9.858215
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.386719 Y: -0.286621 Z: 9.858002 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.386719 .y:-0.286621 .z:9.858002
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
,D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8507 usec
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.378159 Y: -0.305435 Z: 9.865967 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.378159 .y:-0.305435 .z:9.865967
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.379852 Y: -0.307495 Z: 9.872314 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.379852 .y:-0.307495 .z:9.872314
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  372): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1,
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.379684 Y: -0.295761 Z: 9.817917 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.379684 .y:-0.295761 .z:9.817917
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.365997 Y: -0.287292 Z: 9.813675 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.365997 .y:-0.287292 .z:9.813675
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.374359 Y: -0.292923 Z: 9.829285 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.374359 .y:-0.292923 .z:9.829285
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.381683 Y: -0.288025 Z: 9.845261 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.381683 .y:-0.288025 .z:9.845261
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.386566 Y: -0.288040 Z: 9.853180 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.386566 .y:-0.288040 .z:9.853180
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8bd1450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42ab59e0)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
I/WindowManager(  963): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
,D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: InitialState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): setSuspendOptimizations: 4 false
D/WifiStateMachine(  963): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4331a168 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/WeatherAncestor( 1859): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:38:34
,E/SlideAside( 3547): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3547): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1859): 2 : This is isUpdating : false
,D/WeatherAncestor( 1859): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:38:34
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/WeatherService( 1859): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
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
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 412ms
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 7145K, 13% free 68747K/78392K, paused 30ms, total 34ms
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940315172, nextTick: 24859, mDrawingTime: 1
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940315194, nextTick: 24838, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
,D/WeatherService( 1859): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:38:35
,D/WeatherService( 1859): 2 : ACTION screen on
,D/WeatherService( 1859): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1859): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:38:35
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  407): Reading a NULL string not supported here.
E/Parcel  (  407): Reading a NULL string not supported here.
E/Parcel  (  407): Reading a NULL string not supported here.
,E/Parcel  (  407): Reading a NULL string not supported here.
D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 2
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2}
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
D/qcom_sensors_hal(  963): hal_acquire_resources
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/UsbSettingsControl( 2560): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2560): [AUTORUN] onPause() : mActiveCurrentFunction = boot
,I/LGImmersionVibrator(  963): Vibrator off
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: InitialState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): setSuspendOptimizations: 4 true
,D/WifiStateMachine(  963): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  963): handleMessage: X
,D/UsbSettings( 2560): [AUTORUN] onStop()
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/ActivityManager(  963): Not finishing noHistory ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2} (stop requested)
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/WifiController(  963): CMD_SCREEN_OFF 
D/WifiController(  963): shouldWifiStayAwake TRUE
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{433e4180 u0 com.android.settings/.UsbSettings t2} (stop complete)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1859): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:38:35
D/WeatherService( 1859): 2 : ACTION screen off
D/WeatherService( 1859): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:38:35
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
E/Parcel  (  407): Reading a NULL string not supported here.
E/Parcel  (  407): Reading a NULL string not supported here.
E/Parcel  (  407): Reading a NULL string not supported here.
E/Parcel  (  407): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 2
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/NfcService( 1475): NFC-C OFF
D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
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
,I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,I/Sensors (  372): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940318370213607; DSPS: 4785033; Offset: 1456940172342595199
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940338371516467; DSPS: 5440435; Offset: 1456940172342616321
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940340052, nextTick: 59978, mDrawingTime: 1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940340054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940358372420070; DSPS: 6095825; Offset: 1456940172342604397
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940378373724101; DSPS: 6751227; Offset: 1456940172342626689
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940398375019157; DSPS: 7406630; Offset: 1456940172342609490
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940400037, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940400042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940418375885001; DSPS: 8062018; Offset: 1456940172342620841
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940438377841476; DSPS: 8717442; Offset: 1456940172342624191
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940458379129265; DSPS: 9372845; Offset: 1456940172342599724
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940460032, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940460050, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940478380435581; DSPS: 10028248; Offset: 1456940172342593785
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940498381761733; DSPS: 10683651; Offset: 1456940172342607681
,I/LocationManagerService(  963): remove 431aeef0
D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1543): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43336d00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1543): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1543): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3729): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3729): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3729): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/dalvikvm( 2618): GC_CONCURRENT freed 7586K, 32% free 16969K/24832K, paused 4ms+2ms, total 47ms
,D/dalvikvm( 2618): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 2618): GC_FOR_ALLOC freed 1721K, 31% free 17156K/24832K, paused 21ms, total 21ms
,D/dalvikvm( 2618): GC_FOR_ALLOC freed 1234K, 31% free 17308K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2618): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940518382582580; DSPS: 11339038; Offset: 1456940172342604553
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940520054, nextTick: 59970, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940520058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940538383898558; DSPS: 11994441; Offset: 1456940172342608275
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940558385183870; DSPS: 12649843; Offset: 1456940172342611849
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940578386042965; DSPS: 13305231; Offset: 1456940172342616452
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940580037, nextTick: 59979, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940580049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940598387326683; DSPS: 13960633; Offset: 1456940172342618432
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940618388607984; DSPS: 14616035; Offset: 1456940172342617994
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940638389884833; DSPS: 15271437; Offset: 1456940172342613105
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940640052, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940640058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940658391175203; DSPS: 15926839; Offset: 1456940172342621737
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940678392478371; DSPS: 16582242; Offset: 1456940172342612649
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940698393767255; DSPS: 17237645; Offset: 1456940172342589277
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940700048, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940700058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940718394618587; DSPS: 17893032; Offset: 1456940172342616634
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940738395931675; DSPS: 18548435; Offset: 1456940172342617467
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940758397914621; DSPS: 19203860; Offset: 1456940172342616770
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940760038, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940760043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940778399212733; DSPS: 19859263; Offset: 1456940172342602626
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940798400545294; DSPS: 20514666; Offset: 1456940172342622931
,I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1543): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x433dda78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1543): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1543): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3729): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3729): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3729): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940818401890994; DSPS: 21170071; Offset: 1456940172342595340
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940820038, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940820044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940838403207274; DSPS: 21825474; Offset: 1456940172342599364
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940858404537107; DSPS: 22480877; Offset: 1456940172342616941
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940878404960623; DSPS: 23136251; Offset: 1456940172342613211
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940880050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940880053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940898405405487; DSPS: 23791626; Offset: 1456940172342600312
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940918405861991; DSPS: 24447001; Offset: 1456940172342599052
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940938407338612; DSPS: 25102409; Offset: 1456940172342610829
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940940056, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456940940059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940958407783931; DSPS: 25757784; Offset: 1456940172342598385
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940978408217835; DSPS: 26413158; Offset: 1456940172342605043
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456940998408681013; DSPS: 27068533; Offset: 1456940172342610457
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941000040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941000043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941018409113799; DSPS: 27723907; Offset: 1456940172342615997
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941038409554999; DSPS: 28379281; Offset: 1456940172342629951
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941058410432006; DSPS: 29034670; Offset: 1456940172342621948
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941060042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941060045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941078410886129; DSPS: 29690045; Offset: 1456940172342618307
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941098411338906; DSPS: 30345420; Offset: 1456940172342613321
,I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1543): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_FOR_ALLOC freed 2028K, 9% free 27625K/30056K, paused 116ms, total 116ms
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x4352a070: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1543): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1543): 	at dalvik.system.NativeStart.run(Native Method)
E/PlayEventLogger( 3729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3729): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3729): 	at dalvik.system.NativeStart.run(Native Method)
W/System  ( 3729): Ignoring header User-Agent because its value was null.
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941118412238261; DSPS: 31000809; Offset: 1456940172342627666
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941120051, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941120058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941138413104635; DSPS: 31656198; Offset: 1456940172342609030
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941158413540643; DSPS: 32311572; Offset: 1456940172342617792
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941178413991975; DSPS: 32966947; Offset: 1456940172342611360
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941180037, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941180044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941198414442423; DSPS: 33622322; Offset: 1456940172342604045
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941218414903411; DSPS: 34277697; Offset: 1456940172342607269
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941238415353557; DSPS: 34933072; Offset: 1456940172342599651
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941240040, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941240058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941258415801582; DSPS: 35588446; Offset: 1456940172342620430
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941278418265212; DSPS: 36243887; Offset: 1456940172342612136
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941298418688173; DSPS: 36899261; Offset: 1456940172342607851
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941300032, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941300043, nextTick: 59989, mDrawingTime: 0,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941318419127343; DSPS: 37554635; Offset: 1456940172342619775
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941338419576850; DSPS: 38210010; Offset: 1456940172342611518
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941358420033041; DSPS: 38865385; Offset: 1456940172342609946
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941360027, nextTick: 59994, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941360053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941378420960948; DSPS: 39520775; Offset: 1456940172342622325
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941398421402841; DSPS: 40176150; Offset: 1456940172342606455
,I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1543): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x4350ae80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1543): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1543): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1543): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3729): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3729): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3729): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941418421872698; DSPS: 40831525; Offset: 1456940172342618548
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941420043, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1456941420054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941438422749898; DSPS: 41486914; Offset: 1456940172342610738
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1456941458423176382; DSPS: 42142288; Offset: 1456940172342609976
,TIME-OUT KILL (timeout was 1200000ms)
```
