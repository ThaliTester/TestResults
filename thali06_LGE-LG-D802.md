#### Test 50388019385b4d9_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1870): Using Auth Proxy for data requests.
E/DataScheduler( 1870): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1870): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1870): fetch service done; releasing wakelock
I/ConfigFetchService( 1870): stopping self
W/GAV2    ( 3893): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  959): Killing 3441:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1870): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1870): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  959): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/ActivityManager(  959): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3942 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3942): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:AppBoxApplication( 3942): AppBoxApplication onCreate()
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:AbstractIntentService( 3942): onCreate
D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+19ms, total 90ms
D/AppUp4  ( 3942): config : false
D/AppUp4:AbstractEnvInfo( 3942): Config no : EnvRealInfo
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 16ms
I/ActivityManager(  959): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3975 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/AppUp4:AutoProfileManager( 3942): db mvno version : 9
E/AppUp4:AutoProfileManager( 3942): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/HyLog   ( 3975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3975): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3975): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3942): config : false
D/AppUp4:AbstractServerEnvInfo( 3942): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3942): onCreate()
D/AppUp4:AppBoxCommonService( 3942): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3942): Factory mode : 0
I/AppUp4:NetworkUtils( 3942): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3942): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3942): onDestroy()
I/ActivityManager(  959): Killing 3488:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  959): Killing 3464:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 1 tasks}
I/ConversationSkinProvider( 3975): skin provider oncreate
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}
E/[MMS]   ( 3975): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3975): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3975): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3975): MmsSettings: Matching Xml Data file name = 2131034168
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  959): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 3953): 
D/AndroidRuntime( 3953): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3953): CheckJNI is OFF
D/[MMS]   ( 3975): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3975): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3975): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3975): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3975): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3975): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3975): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3975): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3975): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3975): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   online_album = [0]
D/dalvikvm( 3953): Trying to load lib libjavacore.so 0x0
D/[MMS]   ( 3975): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3975): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3975): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
D/dalvikvm( 3953): Added shared lib libjavacore.so 0x0
I/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3975): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3975): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
D/dalvikvm( 3953): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3953): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3953): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/[MMS]   ( 3975): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/LGDrmService( 3975): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b6f674a8
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
D/dalvikvm( 3953): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b6f674c0
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 3975): isDrmV1 =true
V/DrmWrapper( 3975): isDrmV2 =false
V/MmsConfig( 3975): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3975): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3975): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3975): [init]CMAS features are initialized for US country. Returning.
V/Contact ( 3975): Contact init()_Create new insatnce
I/MessagingNotification( 3975): registerLEDObserver
I/MessagingNotification( 3975): registerLEDObserver REGISTER
V/TelephonyAutoProfiling(  959): [getValue] FEATURE key : vzw_roaming_state, value : null
V/MmsConfig( 3975): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/LocationManagerService(  959): getProviders()=[passive, gps]
D/LocationManagerService(  959): request 43584e90 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  959): provider request: passive ProviderRequest[ON interval=0]
I/LOG_TAG ( 3975): registerContactDBChangeObserver
D/CountryDetector(  959): The first listener is added
E/ActivityThread( 3975): Failed to find provider info for com.lge.ims.provider.uc
V/SmsReceiverService( 3975): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3975): [loadRssi] File not exist 
V/LGRssiData( 3975): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3975): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3975): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3975): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3975): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3975): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3975): [getValue] FEATURE key : vzw_roaming_state, value : null
E/memtrack( 3953): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3953): failed to load memtrack module: -2
D/AndroidRuntime( 3953): Calling main entry com.android.commands.am.Am
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3953
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
V/ActivityManager(  959): Moving to PAUSING: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  959): GC_FOR_ALLOC freed 767K, 12% free 27569K/31276K, paused 116ms, total 116ms
I/dalvikvm-heap(  959): Grow heap (frag case) to 29.919MB for 856096-byte allocation
D/dalvikvm(  959): GC_FOR_ALLOC freed 63K, 12% free 28350K/32116K, paused 97ms, total 105ms
I/dalvikvm-heap(  959): Grow heap (frag case) to 30.682MB for 856096-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  959): resumeTopActivityLocked: Pausing null
V/ActivityManager(  959): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  959): setFocusedStack: mFocusedStack=ActivityStack{42cf8cf8 stackId=1, 2 tasks}
D/UsbSettingsControl( 2576): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2576): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3580): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 3953): Shutting down VM
D/ActivityManager(  959): allPausedActivitiesComplete: r=ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  959): startService SlideAside
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  959): Moving to PAUSED: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 2 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Restarting ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3}
D/dalvikvm( 3953): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
I/SlideAside( 3580): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3580): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
I/ActivityManager(  959): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4025 uid=10312 gids={50312, 3003, 3001, 3002}
V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 4025): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4025): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4025): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4025): Binding Chromium to the background looper Looper (main, tid 1) {428994d8}
I/chromium( 4025): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4025): Initializing chromium process, renderers=0
W/chromium( 4025): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4025): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4025): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4025): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4025): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4025): Remote Branch: 
I/Adreno-EGL( 4025): Local Patches: 
I/Adreno-EGL( 4025): Reconstruct Branch: 
I/dalvikvm( 4025): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4025): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4025): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4025): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4025): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4025): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4025): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4025): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4025): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4025): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4025): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4025): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4025): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4025): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4025): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/BaseRuntimeLoader( 4025): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4025): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4025): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4025): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4025): Enabling debug mode 0
W/AwContents( 4025): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  959): IME STATUS OFF
W/AwContents( 4025): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  959): Displayed com.example.hello/.MainActivity: +477ms
I/ActivityManager( 4025): Timeline: Activity_idle id: android.os.BinderProxy@4289abb0 time:40655
I/chromium( 4025): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 4025): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 4025): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4025): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x4289f8b0
D/dalvikvm( 4025): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x4289f8b0
D/jxcore_app_log( 4025): JniHelper::setJavaVM(0x4184f808), pthread_self() = 1626620720
D/JX-Cordova( 4025): jxcore cordova android initializing
I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3} time:40919
D/ActivityManager(  959): no-history finish of ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  959): Finishing activity token=Token{431b2630 ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2576): [AUTORUN] onStop()
V/ActivityManager(  959): Moving to FINISHING: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  959): Moving to STOPPING: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  959): Moving to STOPPED: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4025): Initializing JXcore engine
W/jxcore-log( 4025): JXcore engine is ready
W/jxcore-log( 4025): Starting JXcore engine
,W/jxcore-log( 4025): Platform android
W/jxcore-log( 4025): 
,W/jxcore-log( 4025): Process ARCH arm
W/jxcore-log( 4025): 
,I/jxcore-log( 4025): JXcore Cordova bridge is ready!
I/jxcore-log( 4025): 
,W/jxcore-log( 4025): JXcore engine is started
,I/chromium( 4025): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4025): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/ActivityManager(  959): Waited long enough for: ServiceRecord{430bffc8 u0 com.lge.slideaside/.MainService}
,E/jxcore-log( 4025): >> LGE-LG-D802
E/jxcore-log( 4025): 
,I/jxcore-log( 4025): Total memory 1943035904
I/jxcore-log( 4025): 
I/jxcore-log( 4025): Free memory 459821056
I/jxcore-log( 4025): 
I/jxcore-log( 4025): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): userPath [ 'www' ]
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): Size 1080 1776
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): Screen Brightness 255
I/jxcore-log( 4025): 
,E/jxcore-log( 4025): Dummy Error Log.
E/jxcore-log( 4025): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  289): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4025): getBuffer is called!!!!
I/jxcore-log( 4025): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1821): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:22:0
,D/WeatherService( 1821): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1821): 2 : SDK version : 19
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / false
,D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.easyhome / false
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1821): 2 : TimeTick Receiver Unregister
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450189320032, nextTick: 60001, mDrawingTime: 0
,D/WeatherService( 1821): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:22:0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450189320060, nextTick: 59972, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3893): Thread[GAThread,5,main]: No campaign data found.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1870): Done disabling old GoogleServicesFramework version
,I/ConfigService( 1527): onDestroy
,I/ActivityManager(  959): Killing 3426:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 2 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  959): Message: 20
,D/BluetoothManagerService(  959): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43144850:true
,D/BluetoothManagerService(  959): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  959): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  959): Message: 2
,D/WifiService(  959): New client listening to asynchronous messages
,D/WifiService(  959): setWifiEnabled: false pid=4025, uid=10312
,E/WifiService(  959): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  959): setWifiEnabled startWifiDelaySendMsg true
,I/jxcore-log( 4025): ****TEST TOOK:  5074  ms ****
I/jxcore-log( 4025): 
,I/jxcore-log( 4025): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4025): 
,D/AndroidRuntime( 4089): 
D/AndroidRuntime( 4089): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4089): CheckJNI is OFF
,D/dalvikvm( 4089): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4089): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4089): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4089): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4089): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4089): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/memtrack( 4089): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4089): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 4089): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  959): Force stopping com.example.hello appid=10312 user=-1: uninstall pkg
,I/ActivityManager(  959): Killing 4025:com.example.hello/u0a312 (adj 0): stop com.example.hello
,W/ActivityManager(  959): Force removing ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{42ceb4f0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  959):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cf8cf8 stackId=1, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  959): moveHomeStack:
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,I/WindowState(  959): WIN DEATH: Window{43293b20 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  959): Client connection lost with reason: 4
,W/PackageSettings(  959): Skipping PackageSetting{42d51cb0 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  959): Moving to RESUMED: ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  959): resumeTopActivityLocked: Resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  959): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  959): Moving to DESTROYING: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2576): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  959): Force stopping com.example.hello appid=10312 user=0: pkg removed
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,V/UsbSettings( 2576): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2576): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2576): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/InputReader(  959): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "sms"
,E/SlideAside( 3580): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,D/AppUp4:Utils( 3703): [getPackageName] uri : package:com.example.hello
,D/AppUp4  ( 3703): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3580): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  959): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4107 uid=10090 gids={50090}
,I/AppUp4  ( 3703):  isExcludedPackage  packagename = com.example.hello
,D/AppUp4  ( 3703):  isExcludedPackage TRUE : com.example.hello
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1445): getIsInUseVoLTE : false
I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  959):   Scheme: "smsto"
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/System.err( 2628): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
W/System.err( 2628): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2628): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2628): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2628): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2628): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2628): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2628): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2628): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2628): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 2628): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2628): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2628): 	at dalvik.system.NativeStart.main(Native Method)
,D/dalvikvm( 2643): GC_EXPLICIT freed 4924K, 27% free 18223K/24832K, paused 2ms+3ms, total 82ms
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/HyLog   ( 4107): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4107): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4107): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "mms"
V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.459137 Y: -0.398514 Z: 9.761490 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459137 .y:-0.398514 .z:9.761490
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/[BNRAppListMgrReceiver]( 3414): android.intent.action.PACKAGE_REMOVED : com.example.hello
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/LockScreenSettings( 4107): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "mmsto"
,D/dalvikvm(  959): GC_EXPLICIT freed 950K, 12% free 29286K/32948K, paused 4ms+11ms, total 127ms
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/ActivityManager(  959): Moving to DESTROYED: ActivityRecord{42b17a50 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
,I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "sms"
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  959): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  959): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  959): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  959): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  959): hal_process_report_ind: X: -0.442184 Y: -0.386749 Z: 9.759155 
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442184 .y:-0.386749 .z:9.759155
D/qcom_sensors_hal(  959): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  959): hal_wait_for_response: timeout=0
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "smsto"
D/administrator(  959): Handling package changes for user 0
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "mms"
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  959):   Action: "android.intent.action.SENDTO"
I/PackageManager(  959):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  959):   Scheme: "mmsto"
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/VoicemailCleanupService( 1732): Cleaning up data for package: com.example.hello
I/PackageManager(  959): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/Binder  ( 1302): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1302): java.lang.NullPointerException
W/Binder  ( 1302): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1302): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1302): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1302): 	at dalvik.system.NativeStart.run(Native Method)
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/InputMethodManagerService(  959): IME STATUS OFF
W/InputMethodManagerService(  959): Got RemoteException sending setActive(false) notification to pid 4025 uid 10312
,I/PackageChangeReceiver( 3872): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1140): createShortcutInfo...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1140): handleShortcutListChanged...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/PackageIntentReceiver( 2576): Not supported Hotkey customization function 
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
,D/HideNavigationAppsReceiver( 2576): Receive package name : com.example.hello
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/HideNavigationAppsReceiver( 2576): Delete mPackageMame : com.example.hello
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
,D/dalvikvm(  959): GC_EXPLICIT freed 471K, 12% free 29280K/32948K, paused 3ms+9ms, total 129ms
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): handleShortcutListChanged...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/ActivityManager(  959): Killing 3373:com.google.android.music:main/u0a107 (adj 15): empty #17
I/IcingCorporaProvider( 2643): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/AndroidRuntime( 4089): Shutting down VM
,D/dalvikvm( 4089): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+1ms, total 2ms
I/InteractionManagerConfigurator(  959): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  959): com.example.hello isn't inclued in dragdropPackageList
F/ActivityManager(  959): Service ServiceRecord{432dd260 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43210f98 3373:com.google.android.music:main/u0a107} not same as in map: null
D/BackupManagerService(  959): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  959): removePackageParticipantsLocked: uid=10312 #1
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,F/ActivityManager(  959): Service ServiceRecord{4329d7a8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43210f98 3373:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  959): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4137 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiController(  959): battery changed pluggedType: 2
,D/dalvikvm( 1487): GC_CONCURRENT freed 5518K, 9% free 60859K/66608K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/HyLog   ( 4137): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4137): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4137): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6535K, 13% free 68776K/78504K, paused 36ms, total 39ms
,W/ContextImpl( 4137): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/IcingCorporaProvider( 2643): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/dalvikvm( 3785): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3785): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3785): VFY: replacing opcode 0x6e at 0x0013
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,E/NetworkScheduler.SchedulerReceiver( 1527): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1527): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/PackageBroadcastService( 1870): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/ChimeraCfgMgr( 1870): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1870): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1870): Clearing selected account for com.example.hello
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/ActivityManager(  959): Killing 3513:com.google.android.talk/u0a77 (adj 15): empty #17
,D/WeatherAncestor( 1821): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:22:4
D/ChimeraCfgMgr( 1870): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1870): Module APK com.google.android.play.games already loaded
,D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/LocationSettingsChecker( 1870): Removing dialog suppression flag for package com.example.hello
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1821): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1821): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
D/WeatherService( 1821): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1821): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:22:4
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1821): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1821): 2 : Map key string is -2
,I/ActivityManager(  959): Delaying start of: ServiceRecord{43478710 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
D/PackageIntentReceiver( 2576): Not supported Hotkey customization function 
D/lim     ( 1821): 2 : time = 15:22
I/WeatherReflect( 1821): Model Name : LG-D802
D/WeatherTheme( 1821): 2 : Different view - status_min_formatted : 21 != 22
D/WeatherTheme( 1821): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1821): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1821): 2 : Fixed theme : optimus
D/WeatherTheme( 1821): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/ActivityManager(  959): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4166 uid=10065 gids={50065, 1028, 4002}
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/HyLog   ( 4166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4166): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/ConfigService( 1527): onCreate
I/ConfigFetchService( 1870): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/Icing   ( 1870): doRemovePackageData com.example.hello
,W/BaseAppContext( 1870): Using Auth Proxy for data requests.
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/PeopleContactsSync( 1870): CP2 sync disabled
,W/BaseAppContext( 1870): Using Auth Proxy for data requests.
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/Documents( 4166): Loading roots for com.android.externalstorage.documents
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1870): GC_CONCURRENT freed 1570K, 25% free 18708K/24832K, paused 3ms+3ms, total 54ms
,D/dalvikvm( 1870): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 1870): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 1870): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 1870): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/GOOGLEHELP_CompatibleDatabase( 1870): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1870): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1870): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1870): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  959): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4185 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  959): Timeline: Activity_windows_visible id: ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1} time:47752
,D/GOOGLEHELP_CompatibleDatabase( 1870): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1870): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/dalvikvm( 1527): GC_EXPLICIT freed 921K, 29% free 17843K/24832K, paused 1ms+27ms, total 77ms
,D/GOOGLEHELP_CompatibleDatabase( 1870): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 4883K, 9% free 61756K/67308K, paused 18ms, total 18ms
D/HyLog   ( 4185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4185): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  959): Killing 2138:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  959): Killing 3844:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/GOOGLEHELP_CompatibleDatabase( 1870): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1870): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
D/GOOGLEHELP_CompatibleDatabase( 1870): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1870): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1870): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1870): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/ExternalStorage( 4185): After updating volumes, found 1 active roots
,D/Documents( 4166): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4166): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  959): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4200 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  959): Killing 3942:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/HyLog   ( 4200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4200): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4200): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4289e560 time:47854
,I/ActivityManager(  959): Delaying start of: ServiceRecord{43661540 u0 com.android.providers.downloads/.DownloadService}
,E/SQLiteDatabase( 1870): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1870): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1870): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1870): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1870): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
,W/dalvikvm( 1870): threadid=27: thread exiting with uncaught exception (group=0x41860e48)
,E/SQLiteDatabase( 4200): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4200): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4200): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4200): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4200): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4200): failed to open database external.db
E/LGMediaProvider( 4200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4200): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4200): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4200): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4200): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4200): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4200): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4200): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4200): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1870): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 1870): Process: com.google.android.gms, PID: 1870
E/AndroidRuntime( 1870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 187,0): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 1870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 1870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 1870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1870): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/AndroidRuntime( 1870): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/AndroidRuntime( 1870): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/AndroidRuntime( 1870): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
E/SQLiteDatabase( 4200): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4200): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4200): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4200): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4200): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4200): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4200): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4200): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4200): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4200): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4200): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4200): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4200): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4200): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4200): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4200): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4200): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4200): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4200): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4200): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4200): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4200): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4200): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4200): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4200): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4200): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4200): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4200): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4200): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4200): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4200): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4200): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4200): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4200): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4200): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4200): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4200): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4200): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4200): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4200): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4200): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4200): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4200): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4200): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4200): 	... 12 more
I/Process ( 4200): Sending signal. PID: 4200 SIG: 9
E/DropBoxManagerService(  959): Can't write: system_app_crash
E/DropBoxManagerService(  959): java.io.FileNotFoundException: /data/system/dropbox/drop92.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  959): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  959): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  959): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  959): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  959): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  959): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  959): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  959): 	... 5 more
I/ActivityManager(  959): Process android.process.media (pid 4200) has died.
I/ActivityManager(  959): Start proc android.process.media for restart android.process.media: pid=4215 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,D/ActivityManager(  959): resumeTopActivityLocked: Top activity resumed ActivityRecord{430c9fb8 u0 com.lge.launcher2/.Launcher t1}
D/HyLog   ( 4215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4215): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=40 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=64
E/qdoverlay(  267): data msmfb_data offset=0 memid=38 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  267): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=40 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=64
E/qdoverlay(  267): data msmfb_data offset=0 memid=38 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  267): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/SQLiteDatabase( 4215): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4215): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4215): 	at dalvik.system.NativeStart.main(Native Method)
,E/LGMediaProvider( 4215): failed to open database external.db
E/LGMediaProvider( 4215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4215): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4215): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4215): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4215): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4215): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4215): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4215): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4215): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4215): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4215): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4215): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4215): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4215): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4215): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4215): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4215): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4215): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4215): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,W/System.err( 4215): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4215): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4215): 	at android.os.Looper.loop(Looper.java:136)
,W/System.err( 4215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4215): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4215): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 4215): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4215): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,W/System.err( 4215): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4215): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4215): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4215): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4215): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
,W/System.err( 4215): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4215): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4215): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4215): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
,W/System.err( 4215): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4215): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4215): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4215): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4215): 	... 12 more
,I/Process ( 4215): Sending signal. PID: 4215 SIG: 9
,I/ActivityManager(  959): Process android.process.media (pid 4215) has died.
,I/ActivityManager(  959): Start proc android.process.media for restart android.process.media: pid=4228 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  959): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c78360 stackId=0, 1 tasks}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 1256K, 6% free 25434K/26868K, paused 2ms+2ms, total 26ms
,E/qdoverlay(  267): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  267): Ctrl failed to init fbnum=0
E/qdoverlay(  267): Ctrl failed to init dpy=0
,E/qdoverlay(  267): GenericPipe failed to init ctrl
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  267): == Bad OVInfo is:  mdp_overlay z=1 fg=0 alpha=73 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=384 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=960 h=377
E/qdoverlay(  267): dst_rect mdp_rect x=93 y=750 w=894 h=351
E/qdoverlay(  267): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  267): Ctrl commit failed set overlay
E/qdhwcomposer(  267): configureNonSplit: commit failed for low res panel
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  267): == Bad OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  267): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  267): Ctrl commit failed set overlay
E/qdhwcomposer(  267): configure: configMdp failed for dpy 0
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  267): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  267): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  267): Ctrl commit failed set overlay
E/qdhwcomposer(  267): configure: configMdp failed for dpy 0
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  267): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  267): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888

```
