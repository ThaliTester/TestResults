#### Test 503880194bce128_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/EulaProviderUpdateObserver( 2841): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2841): uri : package:com.example.hello
D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1847): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1847): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ConfigFetchService( 1847): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1847): launchTask
W/dalvikvm( 1847): VFY: unable to find class referenced in signature (Landroid/net/Network;)
--------- beginning of /dev/log/system
I/ActivityManager(  967): Waited long enough for: ServiceRecord{4327dee8 u0 com.google.android.gms/.config.ConfigFetchService}
V/ConfigFetchTask( 1847): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Ut3v9W67qRVaAnbxvgFWNNlnY_eCpsKjPXFUPCSYP05LYCGkunXoJur4qjVk7o8b6U-isrh_LHZY4aaOEGcIfJru0QkEQPsxjwP6rawnDZXqCUtJy5MmVTcJKm2huDFzfq9xBRoCmolaHirU9jOFrIXLPonQHs9E9nBhH25fLsTzYQNt6mSUrybyjPMFMv9MkdL8liNXdyyBNMa6R0flR1U4FkFTb5PVZwTyvO8Bzd9yYOVic
D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1847): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1847): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1847): Failed to find package metadata for com.example.hello
D/Vision  ( 1847): No vision deps
I/GoogleURLConnFactory( 1847): Using platform SSLCertificateSocketFactory
W/GAV2    ( 3734): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  967): Killing 3316:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 1 tasks}
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}
I/PeopleContactsSync( 1847): CP2 sync disabled
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
I/dalvikvm( 1847): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1847): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1847): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
W/BaseAppContext( 1847): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/DataScheduler( 1847): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1847): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1847): fetch service done; releasing wakelock
I/ConfigFetchService( 1847): stopping self
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1847): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1847): GC_CONCURRENT freed 1676K, 26% free 18436K/24832K, paused 3ms+4ms, total 39ms
D/dalvikvm( 1847): WAIT_FOR_CONCURRENT_GC blocked 10ms
I/Icing   ( 1847): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1847): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1847): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 305 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/ActivityManager(  967): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3790 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/ActivityManager(  967): Killing 3333:com.android.providers.calendar/u0a16 (adj 15): empty #17
D/HyLog   ( 3790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3790): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConversationSkinProvider( 3790): skin provider oncreate
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/[MMS]   ( 3790): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
W/BaseRuntimeLoader( 3790): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3790): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3790): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3790): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3790): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3790): MmsSettings: Matching Xml Data file name = 2131034168
D/AndroidRuntime( 3787): 
D/AndroidRuntime( 3787): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3787): CheckJNI is OFF
D/[MMS]   ( 3790): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3790): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3790): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3790): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3790): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3790): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3790): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3790): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3790): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3790): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3790): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3790): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3790): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3790): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
D/dalvikvm( 3787): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3787): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3787): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3787): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3787): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/[MMS]   ( 3790): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/ActivityManager(  967): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3817 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
I/LGDrmService( 3790): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b8ce66e8
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
D/HyLog   ( 3817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3817): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3817): I : /data/font/config/sfconfig.dat, No such file or directory (2)
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
D/dalvikvm( 3787): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b8ce6700
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
D/AppUp4:AppBoxApplication( 3817): AppBoxApplication onCreate()
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
D/AppUp4:AbstractIntentService( 3817): onCreate
D/AppUp4  ( 3817): config : false
D/AppUp4:AbstractEnvInfo( 3817): Config no : EnvRealInfo
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
I/DrmWrapper( 3790): isDrmV1 =true
V/DrmWrapper( 3790): isDrmV2 =false
V/MmsConfig( 3790): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3790): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3790): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/AppUp4:AutoProfileManager( 3817): db mvno version : 9
D/CmasFeatures( 3790): [init]CMAS features are initialized for US country. Returning.
E/AppUp4:AutoProfileManager( 3817): what happen...? prepareValid DB... can't do anything...
V/Contact ( 3790): Contact init()_Create new insatnce
W/BaseRuntimeLoader( 3817): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3817): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3817): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3817): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3817): config : false
D/AppUp4:AbstractServerEnvInfo( 3817): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3817): onCreate()
D/AppUp4:AppBoxCommonService( 3817): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3817): Factory mode : 0
I/AppUp4:NetworkUtils( 3817): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3817): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3817): onDestroy()
I/ActivityManager(  967): Killing 3298:com.android.calendar/u0a15 (adj 15): empty #17
I/MessagingNotification( 3790): registerLEDObserver
I/MessagingNotification( 3790): registerLEDObserver REGISTER
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
V/MmsConfig( 3790): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/CountryDetector(  967): The first listener is added
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}
I/LOG_TAG ( 3790): registerContactDBChangeObserver
E/ActivityThread( 3790): Failed to find provider info for com.lge.ims.provider.uc
V/SmsReceiverService( 3790): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3790): [loadRssi] File not exist 
V/LGRssiData( 3790): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3790): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3790): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3790): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3790): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3790): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3790): [getValue] FEATURE key : vzw_roaming_state, value : null
E/memtrack( 3787): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3787): failed to load memtrack module: -2
D/AndroidRuntime( 3787): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3787
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 2 tasks}
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (361 us)
D/dalvikvm(  967): GC_FOR_ALLOC freed 984K, 12% free 27203K/30880K, paused 64ms, total 64ms
I/dalvikvm-heap(  967): Grow heap (frag case) to 29.561MB for 856096-byte allocation
D/dalvikvm(  967): GC_FOR_ALLOC freed 41K, 12% free 28002K/31720K, paused 66ms, total 66ms
I/dalvikvm-heap(  967): Grow heap (frag case) to 30.341MB for 856096-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{432a74f8 stackId=1, 2 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2507): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2507): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3}
D/AndroidRuntime( 3787): Shutting down VM
D/dalvikvm( 3787): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3408): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  967): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3858 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3408): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3408): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 3858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3858): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3858): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3858): Binding Chromium to the background looper Looper (main, tid 1) {428dee50}
I/chromium( 3858): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3858): Initializing chromium process, renderers=0
W/chromium( 3858): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3858): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3858): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3858): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3858): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3858): Remote Branch: 
I/Adreno-EGL( 3858): Local Patches: 
I/Adreno-EGL( 3858): Reconstruct Branch: 
I/dalvikvm( 3858): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3858): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3858): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3858): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3858): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3858): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3858): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3858): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3858): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3858): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3858): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3858): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3858): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3858): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3858): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3858): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3858): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3858): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 3858): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3858): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3858): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3858): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OpenGLRenderer( 3858): Enabling debug mode 0
W/AwContents( 3858): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 3858): Timeline: Activity_idle id: android.os.BinderProxy@428e0528 time:40469
I/ActivityManager(  967): Displayed com.example.hello/.MainActivity: +374ms
I/chromium( 3858): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3858): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3858): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3858): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428e45e8
D/dalvikvm( 3858): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428e45e8
D/jxcore_app_log( 3858): JniHelper::setJavaVM(0x417c5808), pthread_self() = 1634278920
D/JX-Cordova( 3858): jxcore cordova android initializing
W/jxcore-log( 3858): Initializing JXcore engine
W/jxcore-log( 3858): JXcore engine is ready
W/jxcore-log( 3858): Starting JXcore engine
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3} time:40867
D/ActivityManager(  967): no-history finish of ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{429f8a78 ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2507): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
W/jxcore-log( 3858): Platform android
W/jxcore-log( 3858): 
W/jxcore-log( 3858): Process ARCH arm
W/jxcore-log( 3858): 
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/jxcore-log( 3858): JXcore Cordova bridge is ready!
I/jxcore-log( 3858): 
W/jxcore-log( 3858): JXcore engine is started
I/chromium( 3858): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 3858): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
E/jxcore-log( 3858): >> LGE-LG-D802
E/jxcore-log( 3858): 
I/jxcore-log( 3858): Total memory 1943035904
I/jxcore-log( 3858): 
I/jxcore-log( 3858): Free memory 468848640
I/jxcore-log( 3858): 
I/jxcore-log( 3858): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3858): 
I/jxcore-log( 3858): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3858): 
I/jxcore-log( 3858): userPath [ 'www' ]
I/jxcore-log( 3858): 
I/jxcore-log( 3858): Size 1080 1776
I/jxcore-log( 3858): 
I/jxcore-log( 3858): Screen Brightness 255
I/jxcore-log( 3858): 
E/jxcore-log( 3858): Dummy Error Log.
E/jxcore-log( 3858): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 305 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  967): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 305 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/jxcore-log( 3858): getBuffer is called!!!!
I/jxcore-log( 3858): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 305 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Waited long enough for: ServiceRecord{432358b0 u0 com.lge.slideaside/.MainService}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 3356:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 305 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/GAV2    ( 3734): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1847): Done disabling old GoogleServicesFramework version
,I/ConfigService( 1547): onDestroy
,I/ActivityManager(  967): Killing 3245:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  967): Service ServiceRecord{4330e798 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432a1078 3245:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  967): Service ServiceRecord{43208cd8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432a1078 3245:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e22818:true
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  967): Message: 2
D/WifiService(  967): New client listening to asynchronous messages
,D/WifiService(  967): setWifiEnabled: false pid=3858, uid=10311
,E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
I/jxcore-log( 3858): ****TEST TOOK:  5040  ms ****
I/jxcore-log( 3858): 
I/jxcore-log( 3858): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3858): 
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AndroidRuntime( 3942): 
D/AndroidRuntime( 3942): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3942): CheckJNI is OFF
,D/dalvikvm( 3942): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3942): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3942): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3942): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3942): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3942): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 3942): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3942): failed to load memtrack module: -2
,D/AndroidRuntime( 3942): Calling main entry com.android.commands.pm.Pm
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 3858:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  967): Force removing ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{432792f0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{432a74f8 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
D/WifiService(  967): Client connection lost with reason: 4
I/WindowState(  967): WIN DEATH: Window{430eea68 u0 com.example.hello/com.example.hello.MainActivity}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2507): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2507): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2507): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2507): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{431811e0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,W/PackageSettings(  967): Skipping PackageSetting{42d9dde8 com.test.thalitest/10304} due to missing metadata
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
I/ActivityManager(  967): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3408): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3408): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,W/System.err( 2563): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 2563): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2563): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2563): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2563): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2563): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2563): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2563): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2563): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 2563): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2563): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2563): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2563): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3960 uid=10090 gids={50090}
W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
D/AppUp4:Utils( 3536): [getPackageName] uri : package:com.example.hello
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+5ms, total 19ms
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
D/AppUp4  ( 3536): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3536):  isExcludedPackage  packagename = com.example.hello
D/HyLog   ( 3960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3960): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3960): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,I/PackageManager(  967):   Scheme: "sms"
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,I/LockScreenSettings( 3960): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/AppUp4  ( 3536):  isExcludedPackage TRUE : com.example.hello
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 1175K, 11% free 28897K/32464K, paused 2ms+9ms, total 153ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 149ms
,D/[BNRAppListMgrReceiver]( 3286): android.intent.action.PACKAGE_REMOVED : com.example.hello
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,D/dalvikvm( 2575): GC_EXPLICIT freed 3646K, 29% free 17873K/24832K, paused 1ms+6ms, total 171ms
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
,D/administrator(  967): Handling package changes for user 0
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
D/VoicemailCleanupService( 1747): Cleaning up data for package: com.example.hello
I/PackageChangeReceiver( 3710): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
D/PackageIntentReceiver( 2507): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2507): Receive package name : com.example.hello
D/HideNavigationAppsReceiver( 2507): Delete mPackageMame : com.example.hello
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/IcingCorporaProvider( 2575): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/ActivityManager(  967): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3989 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  967): com.example.hello isn't inclued in dragdropPackageList
,D/dalvikvm( 1488): GC_CONCURRENT freed 5399K, 9% free 61083K/66672K, paused 1ms+3ms, total 24ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 19ms
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10311 #1
,W/ContextImpl( 3989): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/dalvikvm( 3618): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 3618): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3618): VFY: replacing opcode 0x6e at 0x0013
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/KeyguardModel( 1141): handleShortcutListChanged...
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
E/NetworkScheduler.SchedulerReceiver( 1547): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1547): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/ActivityManager(  967): Killing 2090:android.process.media/u0a23 (adj 15): empty #17
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1847): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1847): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/IcingCorporaProvider( 2575): UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
,D/dalvikvm(  967): GC_EXPLICIT freed 451K, 11% free 29007K/32464K, paused 2ms+13ms, total 228ms
,D/AccountUtils( 1847): Clearing selected account for com.example.hello
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 5827K, 12% free 69721K/78472K, paused 27ms, total 27ms
,D/ChimeraCfgMgr( 1847): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1847): Module APK com.google.android.play.games already loaded
,D/PackageIntentReceiver( 2507): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.575241 Y: -0.423325 Z: 9.722107 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.575241 .y:-0.423325 .z:9.722107
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/LocationSettingsChecker( 1847): Removing dialog suppression flag for package com.example.hello
I/ActivityManager(  967): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4018 uid=10065 gids={50065, 1028, 4002}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/ActivityManager(  967): Delaying start of: ServiceRecord{433d1180 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/HyLog   ( 4018): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4018): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4018): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,D/AndroidRuntime( 3942): Shutting down VM
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/dalvikvm( 3942): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+1ms, total 3ms
,I/ConfigService( 1547): onCreate
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
,I/ConfigFetchService( 1847): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
D/GOOGLEHELP_CompatibleDatabase( 1847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1847): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.574371 Y: -0.410309 Z: 9.710190 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.574371 .y:-0.410309 .z:9.710190
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/GOOGLEHELP_CompatibleDatabase( 1847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/KeyguardModel( 1141): handleShortcutListChanged...
,I/Icing   ( 1847): doRemovePackageData com.example.hello
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/PeopleContactsSync( 1847): CP2 sync disabled
,D/GOOGLEHELP_CompatibleDatabase( 1847): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,W/BaseAppContext( 1847): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1847): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/Documents( 4018): Loading roots for com.android.externalstorage.documents
D/GOOGLEHELP_CompatibleDatabase( 1847): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1847): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1847): Using Auth Proxy for data requests.
I/ActivityManager(  967): Killing 3160:com.google.android.talk/u0a77 (adj 15): empty #17
,D/WeatherAncestor( 1819): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:17:18
,D/UpdateThreadPoolManager( 1819): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1819): 2 : quick cover state : opened : 0
,D/WeatherService( 1819): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1819): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1819): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1819): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1819): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:17:18
,D/WeatherService( 1819): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1819): 2 : quick cover state : opened : 0
I/ActivityManager(  967): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4036 uid=10005 gids={50005, 1028, 1015, 1023}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
D/Weather.Utils( 1819): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1819): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1819): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1819): 2 : requestRefreshAppWidget, isUpdateStart : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  967): Killing 3686:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/UpdateThreadPoolManager( 1819): 2 : This is isUpdating : false
D/WeatherService( 1819): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1819): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1819): 2 : Map key string is -2
D/lim     ( 1819): 2 : time = 15:17
I/WeatherReflect( 1819): Model Name : LG-D802
D/WeatherTheme( 1819): 2 : Different view - status_min_formatted : 16 != 17
D/WeatherTheme( 1819): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1819): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1819): 2 : Fixed theme : optimus
D/WeatherTheme( 1819): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@428db098 time:47465
,D/WeatherQuickCover( 1819): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1819): 2 : Utils getTopActivity com.lge.launcher2 / true
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
D/HyLog   ( 4036): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4036): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4036): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1} time:47470
D/WeatherService( 1819): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 307 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/WifiController(  967): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 306 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/ExternalStorage( 4036): After updating volumes, found 1 active roots
,D/Documents( 4018): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/dalvikvm( 1155): GC_CONCURRENT freed 1259K, 6% free 25434K/26872K, paused 1ms+1ms, total 16ms
,D/Documents( 4018): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4049 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  967): Killing 3817:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/HyLog   ( 4049): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4049): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4049): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ca2668 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d09020 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Delaying start of: ServiceRecord{43350da0 u0 com.android.providers.downloads/.DownloadService}
,D/Documents( 4018): Loading roots for com.android.providers.media.documents
,D/Documents( 4018): Loading roots for com.google.android.apps.docs.storage
,W/DriveInitializer( 1847): Awaiting to be initialized
,W/DriveInitializer( 1847): Background init thread started
,D/Documents( 4018): Update found 7 roots in 266ms
,D/Documents( 4018): Loading roots for com.android.externalstorage.documents
D/Documents( 4018): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4018): Used cached roots for com.android.providers.media.documents
D/Documents( 4018): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4018): Update found 7 roots in 6ms
,E/SQLiteLog( 1847): (3850) statement aborts at 184: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 1847): Failed to delete from FileContent112
E/DocListDatabase( 1847): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1847): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1847): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/DocListDatabase( 1847): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 1847): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1847): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/DocListDatabase( 1847): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1847): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1847): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1847): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1847): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1847): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1847): 	at java.lang.Thread.run(Thread.java:841)
,W/dalvikvm( 1847): threadid=38: thread exiting with uncaught exception (group=0x4189de48)
E/AndroidRuntime( 1847): FATAL EXCEPTION: pool-12-thread-1
E/AndroidRuntime( 1847): Process: com.google.android.gms, PID: 1847
E/AndroidRuntime( 1847): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1847): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1847): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1847): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1847): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1847): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1847): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1847): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 1847): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 1847): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 1847): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1847): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1847): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  967): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
E/SQLiteLog( 1847): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1847): disk I/O error (code 3850)
E/DriveAsyncService( 1847): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1847): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1847): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1847): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1847): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1847): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1847): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1847): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1847): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1847): 	at java.lang.Thread.run(Thread.java:841)
,W/DriveInitializer( 1847): Background init thread ended
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
,E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
,E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
,E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=39 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
