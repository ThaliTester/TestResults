#### Test 586024278176cca_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/AndroidRuntime( 4525): 
D/AndroidRuntime( 4525): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4525): CheckJNI is OFF
D/dalvikvm( 4525): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4525): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4525): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4525): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4525): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4525): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2022): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
E/memtrack( 4525): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4525): failed to load memtrack module: -2
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4525): Calling main entry com.android.commands.am.Am
D/AndroidRuntime( 4525): Shutting down VM
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4525
D/dalvikvm( 4525): GC_CONCURRENT freed 99K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,W/ContextImpl( 2668): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1212 android.content.ContextWrapper.sendBroadcast:365 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.573593 Y: -0.338730 Z: 9.796432 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573593 .y:-0.338730 .z:9.796432
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.569901 Y: -0.329559 Z: 9.793930 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569901 .y:-0.329559 .z:9.793930
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/ActivityManager(  964): Killing 3905:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1157): GC_CONCURRENT freed 1242K, 6% free 25451K/26872K, paused 26ms+2ms, total 69ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/rmt_storage(  610): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb817b178
I/rmt_storage(  610): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  610): wakelock acquired: 1, error no: 42
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1206406600)
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1206406600) wakelock released: 1, error no: 0
I/rmt_storage(  610): 
I/rmt_storage(  610): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb817b178
,E/Diag_Lib(  696): [IMS_FATAL]| 2912 | 704 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.576981 Y: -0.341766 Z: 9.812363 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576981 .y:-0.341766 .z:9.812363
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.575821 Y: -0.347580 Z: 9.805969 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.575821 .y:-0.347580 .z:9.805969
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.565506 Y: -0.330048 Z: 9.830521 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.565506 .y:-0.330048 .z:9.830521
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.573715 Y: -0.330276 Z: 9.837173 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573715 .y:-0.330276 .z:9.837173
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935080031, nextTick: 59964, mDrawingTime: 13
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935080076, nextTick: 59957, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.577255 Y: -0.316101 Z: 9.815109 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.577255 .y:-0.316101 .z:9.815109
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.553406 Y: -0.340576 Z: 9.813675 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.553406 .y:-0.340576 .z:9.813675
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL',
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.571213 Y: -0.335663 Z: 9.800934 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571213 .y:-0.335663 .z:9.800934
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.560562 Y: -0.339737 Z: 9.809692 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.560562 .y:-0.339737 .z:9.809692
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8093 usec
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.569504 Y: -0.337433 Z: 9.827209 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569504 .y:-0.337433 .z:9.827209
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.571976 Y: -0.335800 Z: 9.823929 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.571976 .y:-0.335800 .z:9.823929
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  320): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.580948 Y: -0.341644 Z: 9.811707 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.580948 .y:-0.341644 .z:9.811707
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.582642 Y: -0.336929 Z: 9.808319 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.582642 .y:-0.336929 .z:9.808319
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.564240 Y: -0.339706 Z: 9.815109 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.564240 .y:-0.339706 .z:9.815109
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.559753 Y: -0.333344 Z: 9.810043 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559753 .y:-0.333344 .z:9.810043
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43306628)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb71b5450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
I/WindowManager(  964): No lock screen! windowToken=null
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.558990 Y: -0.327362 Z: 9.796738 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.558990 .y:-0.327362 .z:9.796738
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,E/SlideAside( 3787): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  964): handleScreenStateChanged: true
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2022): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2022): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=132097
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2022): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2022): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4327c3a0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1824): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:38:15
,I/SlideAside( 3787): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherAncestor( 1824): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:38:15
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 391ms
D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935095848, nextTick: 44179, mDrawingTime: 6
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935095896, nextTick: 44137, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:15
,D/WeatherService( 1824): 2 : ACTION screen on
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  599): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:38:15
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): Emergency Service
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123,
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2}
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/UsbSettingsControl( 2606): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/UsbSettings( 2606): [AUTORUN] onPause() : mActiveCurrentFunction = boot
,I/LGImmersionVibrator(  964): Vibrator off
,D/UsbSettings( 2606): [AUTORUN] onStop()
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/ActivityManager(  964): Not finishing noHistory ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2} on stop because we're just sleeping
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2} (stop requested)
,D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
,V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
D/VolumeVibrator( 1157): clear
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42de58c0 u0 com.android.settings/.UsbSettings t2} (stop complete)
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1475): NFC-C OFF
D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:16
,D/WeatherService( 1824): 2 : ACTION screen off
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:38:16
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  320): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935113642124047; DSPS: 5276308; Offset: 1454934952621982446
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/GoogleURLConnFactory( 1552): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1552): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1552): No account for auth token provided
,W/Uploader( 1552): No account for auth token provided
,W/Uploader( 1552):  no longer exists, so no auth token.
,W/Uploader( 1552): No account for auth token provided
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935133643000058; DSPS: 5931697; Offset: 1454934952621973447
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935140044, nextTick: 59965, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935140060, nextTick: 59972, mDrawingTime: 0
,I/rmt_storage(  610): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb817b178
I/rmt_storage(  610): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1206407448)
,I/rmt_storage(  610): wakelock acquired: 1, error no: 42
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  610): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1206407448) wakelock released: 1, error no: 0
I/rmt_storage(  610): 
I/rmt_storage(  610): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb817b178
,E/Diag_Lib(  696): [IMS_FATAL]| 2912 | 704 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935153643451192; DSPS: 6587071; Offset: 1454934952621997335
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 3 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48],
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935173643907920; DSPS: 7242446; Offset: 1454934952621996299
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935193651606972; DSPS: 7898059; Offset: 1454934952621974404
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935200031, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935200061, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935213652047300; DSPS: 8553433; Offset: 1454934952621987486
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935233652948886; DSPS: 9208823; Offset: 1454934952621973545
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935253660934448; DSPS: 9864444; Offset: 1454934952621994019
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935260041, nextTick: 59963, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935260058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935273661850828; DSPS: 10519834; Offset: 1454934952621994871
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43022658: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4276): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4276): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4276): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4276): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4276): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4276): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4276): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4276): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4276): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4276): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935293662767714; DSPS: 11175224; Offset: 1454934952621996230
,I/LocationManagerService(  964): remove 4337c028
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/dalvikvm( 2668): GC_CONCURRENT freed 7679K, 32% free 16952K/24832K, paused 14ms+2ms, total 58ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 2668): GC_CONCURRENT freed 1585K, 30% free 17414K/24832K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2668): GC_CONCURRENT freed 2104K, 31% free 17357K/24832K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2668): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Mlt MonitorService( 2668): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935313663208743; DSPS: 11830599; Offset: 1454934952621979495
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935320021, nextTick: 60002, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935320067, nextTick: 59963, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935333667053670; DSPS: 12486085; Offset: 1454934952621979208
,D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Disconnect event
D/wpa_supplicant( 2022): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2022): wlan0: Deauthentication notification
D/wpa_supplicant( 2022): wlan0:  * reason 0
D/wpa_supplicant( 2022): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2022): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2022): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2022): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2022): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2022): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  964): handleMessage: E msg.what=147460,
D/WifiStateMachine(  964): processMsg: ConnectedState,
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState,
,D/WifiStateMachine(  964): Network connection lost,
,D/WifiStateMachine(  964): Stopping DHCP and clearing IP
,D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1,
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8210d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2022): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.168/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/wpa_supplicant( 2022): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2022): wlan0: nl80211: scan request
,D/wpa_supplicant( 2022): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2022): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2022): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiHS20(  964): hidePasspointNotification off =false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/QCNEA   (  599): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  599): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  599): |CAC| updateNetCfgInfo
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC|                   Netconfig               
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  599): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  599): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  599): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  599): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  599): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  599): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| Received bssid= 
D/QCNEA   (  599): |CAC| net type = 3
V/QCNEA   (  599): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  599): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  599): |CAC| 	ssid           =NG700
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  599): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  599): |CAC| dispatchNetCfg: updating:0xb8d818dc
D/QCNEA   (  599): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4926 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): handleMessage: X
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4926): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4926): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4926): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  964): '
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  964): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  964): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x60941d68 clazz=0x6a800001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4970 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 3660:com.android.providers.calendar/u0a16 (adj 15): empty #17
,V/NativeCrypto( 1552): Read error: ssl=0x63ab3b78: I/O error during system call, Connection timed out
,D/DhcpStateMachine(  964): StoppedState
,V/NativeCrypto( 1552): SSL shutdown failed: ssl=0x63ab3b78: I/O error during system call, Broken pipe
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4970): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4970): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QRemote ( 4970): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4970): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4970): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4970): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4970): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4970): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 4015:com.lge.task/u0a43 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935353667493832; DSPS: 13141459; Offset: 1454934952621992124
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2022): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2022): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2022): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2022): nl80211: Survey data missing
D/wpa_supplicant( 2022): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Add new id 5 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): wlan0: BSS: Add new id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos',
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2022): wlan0: BSS: Add new id 7 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 2022): wlan0: New scan results available,
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:4a type 0 added,
D/wpa_supplicant( 2022): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2022): WPS: AP 00:37:b7:9d:3e:73 type 0 added,
,D/wpa_supplicant( 2022): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
,D/wpa_supplicant( 2022): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1,
,D/wpa_supplicant( 2022): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 2022): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2022): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2022): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2022): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80
,D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch,
,D/wpa_supplicant( 2022): wlan0: 3: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-91 wps,
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2022): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2022): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:4a],
D/wpa_supplicant( 2022): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 2022): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2022): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2022): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2022): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2022): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
,D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2022): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82125a8  current_ssid=0x0
,D/wpa_supplicant( 2022): scard is not null..,
D/wpa_supplicant( 2022): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2022): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2022): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
,D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): TDLS: TDLS is allowed in the target BSS,
,I/wpa_supplicant( 2022): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2022): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2022): RSN: PMKSA cache search - network_ctx=0xb82125a8 try_opportunistic=0
D/wpa_supplicant( 2022): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2022): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2022): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2022): wlan0: WPA: using KEY_MGMT WPA-PSK
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:37:b7:9d:3e:73]
D/wpa_supplicant( 2022): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2022): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 2022): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2022): nl80211: Unsubscribe mgmt frames handle 0xb8211590 (mode change)
D/wpa_supplicant( 2022): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590,
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0d,
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
,D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590,
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2022): nl80211: Register frame type=0xd0 nl_handle=0xb8211590
,D/wpa_supplicant( 2022): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2022): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 2022):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022):   * freq=2412
D/wpa_supplicant( 2022):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2022):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2022):   * Auth Type 0
D/wpa_supplicant( 2022):   * WPA Versions 0x2,
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState,
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt,
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
D/wpa_supplicant( 2022): nl80211: Connect request send successfully
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2022): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2022): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event,
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462,
D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2022): nl80211: Event message available
D/wpa_supplicant( 2022): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2022): nl80211: Connect event
D/wpa_supplicant( 2022): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2022): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2022): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2022): wlan0: Association info event
D/wpa_supplicant( 2022): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2022): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2022): wlan0: freq=2412 MHz
D/wpa_supplicant( 2022): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2022): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2022): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2022): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): scard is not null..
D/wpa_supplicant( 2022): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2022): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2022): TDLS: Remove peers on association
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2022): EAPOL: enable timer tick
,D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: Cancelling scan request
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ...
D/wpa_supplicant( 2022): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ef 06 4a 44 14 78 67 74 72 39 12 e4 14 23 c1 dd 91
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ...
D/wpa_supplicant( 2022): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2022): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2022): WPA: Renewed SNonce - hexdump(len=32): aa b1 d7 b6 19 3e 04 84 3b ba 60 20 29 a7 70 ca 26 58 a8 0a f9 7e 84 34 28 e3 2d 2d 44 24 ea 87
,D/wpa_supplicant( 2022): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): WPA: Nonce1 - hexdump(len=32): aa b1 d7 b6 19 3e 04 84 3b ba 60 20 29 a7 70 ca 26 58 a8 0a f9 7e 84 34 28 e3 2d 2d 44 24 ea 87
D/wpa_supplicant( 2022): WPA: Nonce2 - hexdump(len=32): 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ef 06 4a 44 14 78 67 74 72 39 12 e4 14 23 c1 dd 91
D/wpa_supplicant( 2022): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2022): WPA: PTK - hexdump(len=48): [REMOVED]
,D/wpa_supplicant( 2022): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): 9b ee ec 05 dd af cc 2e 88 1a 42 7d 9a ab 8f f5
D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 aa b1 d7 b6 19 3e 04 84 3b ba 60 20 29 a7 70 ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState,
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4048): onReceive
D/wpa_supplicant( 2022): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2022): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ...
D/wpa_supplicant( 2022): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2022): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2022): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2022): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2022):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2022):   key_nonce - hexdump(len=32): 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ef 06 4a 44 14 78 67 74 72 39 12 e4 14 23 c1 dd 91
D/wpa_supplicant( 2022):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_rsc - hexdump(len=8): 9c 09 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2022):   key_mic - hexdump(len=16): 90 9a 87 8a 3f f4 99 58 7c ab 04 57 7d 84 a9 8b
D/wpa_supplicant( 2022): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 28 70 5f 6c 5c 7c bc 99 ed d6 19 fd ca 82 76 ...
D/wpa_supplicant( 2022): RSN: encrypted key data - hexdump(len=56): a5 22 74 fa e5 3d 08 72 54 a9 e2 62 42 22 73 7c d8 b1 49 5f ab 38 31 50 72 66 ef 1b 54 41 69 41 ...
D/wpa_supplicant( 2022): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2022): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2022): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 3e 04 ...
D/wpa_supplicant( 2022): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2022): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2022): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2022): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2022): WPA: Derived Key MIC - hexdump(len=16): a6 26 83 c1 f0 4b d0 9f 14 d9 ce 14 47 7e 88 b6
,D/wpa_supplicant( 2022): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2022): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8211c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 2022):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2022): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2022): WPA: Group Key - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2022): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2022): WPA: RSC - hexdump(len=6): 9c 09 00 00 00 00
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f4f03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2022):    broadcast key,
,I/wpa_supplicant( 2022): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2022): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2022): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2022): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2022): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2022): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2022): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2022): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2022): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2022): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2022): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2022): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 2022): EAPOL authentication completed successfully
D/wpa_supplicant( 2022): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2022): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2022): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]],
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X,
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2022): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/AppUp4:CustFacade( 4048): Context : android.app.ReceiverRestrictedContext@427fa378
D/AppUp4:CustFacade( 4048): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4048): isOpenOperator : true
,D/AppUp4:CustFacade( 4048): isPhone : true
,I/LicenseContentProvider( 4230): start selecting data
,D/SIMObserver( 4230): simInfo1
,D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/AppUp4:EulaManager( 4048): getAgreementForKK : Eula agreement is false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/AppUp4:CustModeStarterReceiver( 4048): begin check event
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
I/AppUp4:CustModeStarterReceiver( 4048): Event For GoodConnectivity
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-30ms what=147462 obj=android.net.wifi.StateChangeResult@4347b938 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@4347d360 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-23ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5014 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/HyLog   ( 5014): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5014): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5014): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/LGEmail ( 5014): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43238578 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43238578 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  964): addressUpdated: 192.168.1.168/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.168/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2022): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2022): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2022): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2022): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2022): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2022): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): handleMessage: X
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,E/Parcel  (  599): Reading a NULL string not supported here.
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/LGEmail ( 5014): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 5014): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5014): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
W/BaseRuntimeLoader( 5014): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5014): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5014): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/QCNEA   (  599): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  599): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  599): |CAC| updateNetCfgInfo
V/QCNEA   (  599): |CAC| *********************************************
,V/QCNEA   (  599): |CAC|                   Netconfig               
V/QCNEA   (  599): |CAC| *********************************************
V/QCNEA   (  599): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  599): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  599): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  599): |CAC| 	NetConfig: ip4        =192.168.1.168
V/QCNEA   (  599): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  599): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  599): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  599): |CAC| net type = 1
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  599): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  599): |CAC| Received ssid= NG700
V/QCNEA   (  599): |CAC| 	ssid           =NG700
V/QCNEA   (  599): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  599): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  599): |CAC| *********************************************
D/QCNEA   (  599): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  599): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  599): |CAC| dispatchNetCfg: updating:0xb8d818dc
D/QCNEA   (  599): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
I/LgeMiscReceiver( 4378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4378): action = android.net.conn.CONNECTIVITY_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/LgeMiscReceiver( 4378): networkInfo.isConnected() = false
W/linker  ( 5014): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 5014): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5014): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 5014): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 5014): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 5014): register_HtmlEditor, Success
D/HtmlEditor( 5014): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5056 uid=10052 gids={50052, 3003}
D/HtmlEditor( 5014): register_HtmlEditorTimer, Success
D/HtmlEditor( 5014): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 5014): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5014): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5014): register_HtmlEditorFont, Success
D/HtmlEditor( 5014): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5014): register_HtmlEditorDrawText, Success
D/HtmlEditor( 5014): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5014): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 5014): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5014): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 5014): JNI_OnLoad Success
,I/HubEmail( 5014): JNI_OnLoad()
I/HubEmail( 5014): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5014): registerNatives()
,I/HubEmail( 5014): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5014): registerNativeMethods()
,I/HubEmail( 5014): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 5014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 5056): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5056): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5056): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): Killing 3611:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/LGRssiData( 5056): [loadRssi] File not exist 
,V/LGRssiData( 5056): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5056): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5056): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5056): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5056): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5056): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 5056): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5056): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 5056): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5056): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5056): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5077 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 5056): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5056): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Killing 4073:com.google.android.gm/u0a68 (adj 15): empty #17
,D/HyLog   ( 5077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5077): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5077): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 3ms+3ms, total 38ms
,I/CheckinService( 1961): Checking schedule, now: 1454935355289 next: 1454935018154
,I/CheckinService( 1961): active receiver: enabled
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
I/CheckinService( 1961): Preparing to send checkin request
,I/EventLogService( 1961): Accumulating logs since 1454934984877
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 28ms
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5091 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  964): Killing 4182:com.google.android.talk/u0a77 (adj 15): empty #17
E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5091): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2894): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2894): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  964): Killing 4243:com.android.contacts/u0a21 (adj 15): empty #17
I/LGDMClient( 2894): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5104 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,E/LGDMClient( 2894): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2894): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LGDMClient( 2894): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2894): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HyLog   ( 5104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5104): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5104): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5104): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5118 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4258:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dalvikvm(  964): GC_CONCURRENT freed 2514K, 9% free 28122K/30844K, paused 4ms+12ms, total 172ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 137ms
,D/wpa_supplicant( 2022): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2022): EAPOL: disable timer tick
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 208K, 10% free 27914K/30844K, paused 4ms+9ms, total 145ms
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5118): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5118): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5118): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5118): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Wireless_Storage( 5118): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5118): intf.getDisplayName() = lo
I/Wireless_Storage( 5118): intf.getDisplayName() = sit0
I/Wireless_Storage( 5118): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 5118): intf.getDisplayName() = teql0
I/Wireless_Storage( 5118): intf.getDisplayName() = wlan0
,D/NFS     ( 5118): interface name:wlan0 name:wlan0
D/NFS     ( 5118): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 5118): interface name:wlan0 name:wlan0
D/NFS     ( 5118): addr:192.168.1.168 broadcast:192.168.1.255
,I/Wireless_Storage( 5118): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5136 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 3927:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 5136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5136): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5136): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1552): GC_CONCURRENT freed 1768K, 28% free 18048K/24832K, paused 4ms+5ms, total 81ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 5136): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1961): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x434a0b50: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5164 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5164): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5164): VFY: replacing opcode 0x60 at 0x000b
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/dalvikvm( 5164): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5164): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5164): VFY: replacing opcode 0x62 at 0x005e
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.168/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/MultiDex( 5164): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5164): install
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/MultiDex( 5164): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/MultiDex( 5164): loading existing secondary dex files
,I/MultiDex( 5164): load found 3 secondary dex files
,I/MultiDex( 5164): install done
,D/dalvikvm( 5164): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 5164): VFY: unable to resolve instance field 61
,D/dalvikvm( 5164): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5164): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5164): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5164): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5164): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5164): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5164): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5164): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5164): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5164): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e7638
,D/dalvikvm( 5164): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e7638
,D/dalvikvm( 5164): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e7638, skipping init
,D/dalvikvm( 5164): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e7638
D/dalvikvm( 5164): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e7638
,V/JNIHelp ( 5164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5136): Binding Chromium to the main looper Looper (main, tid 1) {427dff60}
,I/chromium( 5136): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5136): Initializing chromium process, renderers=0
,W/chromium( 5136): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5136): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5136): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5136): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5136): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5136): Remote Branch: 
I/Adreno-EGL( 5136): Local Patches: 
I/Adreno-EGL( 5136): Reconstruct Branch: 
,D/dalvikvm( 5164): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427e7638
,D/dalvikvm( 5164): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427e7638
D/dalvikvm( 5164): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427e7638
,D/dalvikvm( 5164): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427e7638
,I/NSApplication( 5136): Starting up...
,I/ActivityManager(  964): Killing 4359:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,I/ProviderInstaller( 5164): Installed default security provider GmsCore_OpenSSL
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4926): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4926): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/dalvikvm( 5164): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5164): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5164): VFY: replacing opcode 0x6e at 0x000d
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4970): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4970): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4970): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1552): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1552): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1552): Proximity feature is not enabled.
I/dalvikvm( 5164): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5164): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5164): VFY: replacing opcode 0x6e at 0x0201
,V/GmsCoreStatsServiceLauncher( 1961): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1753): callingUid 10006, callindPid: 1753
,E/MDM     ( 1426): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1961): Restart initialization of location
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f7d000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f7d000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=1920933259
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5164): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/D445EC754642D6B27C593D485C6FEFAD7DCE27E5/lib/libd317EF1D9D4A2.so 0x429aa578
,D/dalvikvm( 5164): Added shared lib /data/data/com.google.android.gms/app_dg_cache/D445EC754642D6B27C593D485C6FEFAD7DCE27E5/lib/libd317EF1D9D4A2.so 0x429aa578
,D/dalvikvm( 5164): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/D445EC754642D6B27C593D485C6FEFAD7DCE27E5/lib/libd317EF1D9D4A2.so 0x429aa578, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.168
,V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5164): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5164): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/GCM     ( 1552): Connected
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1552): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 5235): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5164): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5164): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 112ms
,I/Adreno-EGL( 5164): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5164): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5164): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5164): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5164): Remote Branch: 
I/Adreno-EGL( 5164): Local Patches: 
I/Adreno-EGL( 5164): Reconstruct Branch: 
,I/Adreno-EGL( 5164): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5164): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5164): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5164): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5164): Remote Branch: 
I/Adreno-EGL( 5164): Local Patches: 
I/Adreno-EGL( 5164): Reconstruct Branch: 
,I/Adreno-EGL( 5164): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5164): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5164): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5164): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5164): Remote Branch: 
I/Adreno-EGL( 5164): Local Patches: 
I/Adreno-EGL( 5164): Reconstruct Branch: 
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=3337378190
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4048): onReceive
,D/AppUp4:CustFacade( 4048): Context : android.app.ReceiverRestrictedContext@427fa378
D/AppUp4:CustFacade( 4048): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4048): isOpenOperator : true
,D/AppUp4:CustFacade( 4048): isPhone : true
,I/LicenseContentProvider( 4230): start selecting data
,D/SIMObserver( 4230): simInfo1
,I/AppUp4:EulaManager( 4048): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4048): begin check event
I/AppUp4:CustModeStarterReceiver( 4048): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4048): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4048): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4048): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4048): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4048): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 3161): DownloadService onCreate
,I/DownloadManager( 3161): in removeSpuriousFiles
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 5014): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@42882100 on behalf of 3161
,D/eas_req ( 5014): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 3161): in trimDatabase
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@428831d0 on behalf of 3161
,V/DownloadManager( 3161): DownloadService onStartCommand
I/LgeMiscReceiver( 4378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4378): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4378): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5056): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5056): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 5014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@42885cc0 on behalf of 3161
,D/LGDMClient( 2894): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/NativeCrypto( 1961): SSL shutdown failed: ssl=0x6b5f1e30: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LGDMSGCM( 5104): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2894): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 5104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NFS     ( 5118): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5118): CONNECT : WIFI_CONNECT
I/LGDMClient( 2894): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3161): DownloadService onDestroy
,E/LGDMClient( 2894): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2894): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2894): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2894): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4048): onReceive
,D/AppUp4:CustFacade( 4048): Context : android.app.ReceiverRestrictedContext@427fa378
D/AppUp4:CustFacade( 4048): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4048): isOpenOperator : true
,D/AppUp4:CustFacade( 4048): isPhone : true
,I/LicenseContentProvider( 4230): start selecting data
,D/SIMObserver( 4230): simInfo1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 4048): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4048): begin check event
,I/AppUp4:CustModeStarterReceiver( 4048): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 3161): DownloadService onCreate
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 5014): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 3161): in removeSpuriousFiles
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@4288a430 on behalf of 3161
,I/DownloadManager( 3161): in trimDatabase
V/DownloadManager( 3161): DownloadService onStartCommand
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4378): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4378): networkInfo.isConnected() = true
D/PhoneState( 4378): setPdpRejectCasuse : false
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@4288bce0 on behalf of 3161
,W/Settings( 5014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@4288d9b0 on behalf of 3161
,D/MobileConnectivityChangeReceiver( 5056): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5056): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2894): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3161): DownloadService onDestroy
,D/LGDMClient( 2894): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5104): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2894): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5118): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5118): CONNECT : WIFI_CONNECT
E/LGDMClient( 2894): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2894): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2894): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2894): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinTask( 1961): Sending checkin request (11477 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4048): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4048): onReceive
,D/AppUp4:CustFacade( 4048): Context : android.app.ReceiverRestrictedContext@427fa378
D/AppUp4:CustFacade( 4048): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4048): isOpenOperator : true
,D/AppUp4:CustFacade( 4048): isPhone : true
,I/LicenseContentProvider( 4230): start selecting data
,D/SIMObserver( 4230): simInfo1
,I/AppUp4:EulaManager( 4048): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4048): begin check event
,I/AppUp4:CustModeStarterReceiver( 4048): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 3161): DownloadService onCreate
,D/EAS     ( 5014): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4378): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4378): networkInfo.isConnected() = true
,D/PhoneState( 4378): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5056): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5056): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2894): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5104): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5118): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5118): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2894): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 3161): in removeSpuriousFiles
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2894): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 5014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@42891c28 on behalf of 3161
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2894): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2894): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2894): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3161): in trimDatabase
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@428934d0 on behalf of 3161
,I/LGDMClient( 2894): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 3161): DownloadService onStartCommand
,V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@428957e8 on behalf of 3161
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 3161): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  964): GC_FOR_ALLOC freed 1307K, 10% free 28100K/30928K, paused 132ms, total 132ms
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x427ff3e0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1961): awaiting user notification for token
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/CheckinTask( 1961): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1961): Checking schedule, now: 1454935359984 next: 1455512755981
,I/CheckinService( 1961): active receiver: disabled
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinService( 1961): Checking schedule, now: 1454935360025 next: 1455512755981
,I/CheckinService( 1961): active receiver: disabled
,D/GCM     ( 1552): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1961): GC_CONCURRENT freed 1927K, 24% free 19086K/24832K, paused 4ms+4ms, total 65ms
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 5136): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Killing 4276:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5327 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  964): Handling package changes for user 0
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/dalvikvm(  964): Jit: resizing JitTable from 8192 to 16384
,E/SlideAside( 3787): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3787): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5327): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5327): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5327): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5327): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5327): MmsConfig.loadMmsSettings
,I/Babel   ( 5327): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5327): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5327): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5327): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5327): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5327): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/Settings( 5327): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 5327): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5327): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5327): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5327): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5327): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5327): MmsConfig.loadFromResources
,E/Babel   ( 5327): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5327): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1426): DISABLE
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,D/dalvikvm(  964): GC_EXPLICIT freed 1639K, 10% free 28064K/30924K, paused 6ms+13ms, total 159ms
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4048): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4048): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4048): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5327): [loadRssi] File not exist 
V/LGRssiData( 5327): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5327): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5327): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5327): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5327): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4048): onReceive
D/AppUp4:CustFacade( 4048): Context : android.app.ReceiverRestrictedContext@427fa378
,D/AppUp4:CustFacade( 4048): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4048): isOpenOperator : true
,D/AppUp4:CustFacade( 4048): isPhone : true
,I/LicenseContentProvider( 4230): start selecting data
,D/SIMObserver( 4230): simInfo1
,I/AppUp4:EulaManager( 4048): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4048): begin check event
D/AppUp4:Utils( 4048): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4048): Event For Nothing, skip.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5376 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5376): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5376): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5376): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5376): BUILD Country: EU
,I/SystemConfig( 5376): BUILD Operator: OPEN
I/ActivityManager(  964): Killing 4491:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5393 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,I/SystemConfig( 5376): systemFeature RCS result false
,D/SystemConfig( 5376): refreshRcsSupport() :false
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 4926:com.lge.sync/1000 (adj 15): empty #17
,D/HyLog   ( 5393): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5393): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5393): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 4970:com.lge.qremote/u0a96 (adj 15): empty #17
,I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5410 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5410): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5410): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5410): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5410): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5410): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5410): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5410): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5410): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5410): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5410): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5410): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5410): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5410): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5410): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5410): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 308 ms] updated apps [took 308 ms] 
,I/dalvikvm( 5410): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5410): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 5410): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5410): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5410): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5410): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@4289a480 on behalf of 5410
,I/dalvikvm( 5410): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5410): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5410): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5410): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5410): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5410): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5410): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5410): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1961): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 5410): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  964): Killing 5014:com.lge.email/u0a24 (adj 15): empty #17
,I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43285690 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5410): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5410): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5410): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5410): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5410): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false,
,W/Finsky  ( 5410): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5410): Total arena pages for JIT: 11
,I/dalvikvm( 5410): Total arena pages for JIT: 12
,I/dalvikvm( 5410): Total arena pages for JIT: 13
,I/dalvikvm( 5410): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5410): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5410): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5410): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5410): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 5327): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935373668394583; DSPS: 13796849; Offset: 1454934952621977347
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935380052, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935380055, nextTick: 59976, mDrawingTime: 1
,D/Finsky  ( 5410): [450] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935393669125973; DSPS: 14452233; Offset: 1454934952621976315
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935413673073970; DSPS: 15107722; Offset: 1454934952621987545
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935433673498067; DSPS: 15763096; Offset: 1454934952621984396
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935440074, nextTick: 59955, mDrawingTime: 3
D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935440075, nextTick: 59956, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935453673959977; DSPS: 16418471; Offset: 1454934952621988542
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935473680992768; DSPS: 17074062; Offset: 1454934952621971772
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935493681858284; DSPS: 17729450; Offset: 1454934952621982796
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935500050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935500053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935513682317583; DSPS: 18384825; Offset: 1454934952621984332
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935533682768628; DSPS: 19040200; Offset: 1454934952621977613
,D/wpa_supplicant( 2022): wlan0: BSS: Remove id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2022): wlan0: BSS: Remove id 7 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2022): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:37:b7:9d:3e:73]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935553687495759; DSPS: 19695715; Offset: 1454934952621974519
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935560045, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935560052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935573688403416; DSPS: 20351104; Offset: 1454934952621997166
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935593689304933; DSPS: 21006494; Offset: 1454934952621983156
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935613689752116; DSPS: 21661869; Offset: 1454934952621972575
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935620041, nextTick: 59977, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935620052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935633692578887; DSPS: 22317321; Offset: 1454934952621991729
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935653693034035; DSPS: 22972696; Offset: 1454934952621989114
,D/dalvikvm( 1552): GC_EXPLICIT freed 1445K, 28% free 18006K/24832K, paused 7ms+6ms, total 62ms
,I/GLSUser ( 1552): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1552): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1552): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1552): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1552): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1552): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x433ab7f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1552): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1552): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1552): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1552): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1552): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1552): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 5410): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5410): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5410): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5410): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5410): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5410): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5410): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5410): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5410): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5410): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935673693484871; DSPS: 23628071; Offset: 1454934952621982186
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935680044, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935680054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935693694417074; DSPS: 24283462; Offset: 1454934952621968344
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935713695312579; DSPS: 24938851; Offset: 1454934952621978839
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935733695759803; DSPS: 25594226; Offset: 1454934952621968300
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935740031, nextTick: 59996, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935740053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935753696213288; DSPS: 26249600; Offset: 1454934952621994538
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935773702295473; DSPS: 26905160; Offset: 1454934952621973208
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935793703183739; DSPS: 27560549; Offset: 1454934952621976464
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935800035, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935800039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935813703627336; DSPS: 28215923; Offset: 1454934952621992815
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935833707360795; DSPS: 28871406; Offset: 1454934952621972612
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935853708288116; DSPS: 29526796; Offset: 1454934952621984406
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935860039, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935860053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935873709683463; DSPS: 30182202; Offset: 1454934952621975944
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935893711689798; DSPS: 30837628; Offset: 1454934952621968119
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935913712586437; DSPS: 31493017; Offset: 1454934952621979748
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935920031, nextTick: 59986, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935920054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935933714046829; DSPS: 32148425; Offset: 1454934952621975296
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935953715404362; DSPS: 32803829; Offset: 1454934952621990056
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935973715843378; DSPS: 33459203; Offset: 1454934952622001826
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935980030, nextTick: 59992, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454935980054, nextTick: 59978, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED,
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454935993717310365; DSPS: 34114612; Offset: 1454934952621973451
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936013718661207; DSPS: 34770016; Offset: 1454934952621981520
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936033719527388; DSPS: 35425405; Offset: 1454934952621962691
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936040049, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936040052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936053721491016; DSPS: 36080829; Offset: 1454934952621973194
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936073722960477; DSPS: 36736237; Offset: 1454934952621977811
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936093723384580; DSPS: 37391611; Offset: 1454934952621974668
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936100049, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936100053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936113724777103; DSPS: 38047017; Offset: 1454934952621963383
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936133726154867; DSPS: 38702422; Offset: 1454934952621967856
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936153727003180; DSPS: 39357809; Offset: 1454934952621992194
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936160041, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936160052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936173728482565; DSPS: 40013218; Offset: 1454934952621976218
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936193729847179; DSPS: 40668623; Offset: 1454934952621967541
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936213730290146; DSPS: 41323997; Offset: 1454934952621983262
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936220042, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1454936220054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1454936233732317707; DSPS: 41979424; Offset: 1454934952621966145
,TIME-OUT KILL (timeout was 1200000ms)
```
