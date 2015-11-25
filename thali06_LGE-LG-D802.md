#### Test 503880196dc97cd_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1944): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1944): launchTask
W/dalvikvm( 1944): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1944): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1944): Failed to find package metadata for com.example.hello
D/Vision  ( 1944): No vision deps
V/ConfigFetchTask( 1944): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Ut3v9W67qRVaAnbxvgFWNNlnY_eCpsKjPXFUPCSYP05LYCGkunXoJur4qjVk7o8b6U-isrh_LHZY4aaOEGcIfJru0QkEQPsxjwP6rawnDZXqCUtJy5MmVTcJKm2huDFzfq9xBRoCmolaHirU9jOFrIXLPonQHs9E9nBhH25fLsTzYQNt6mSUrybyjPMFMv9MkdL8liNXdyyBNMa6R0flR1U4FkFTb5PVZwTyvO8Bzd9yYOVic
I/GoogleURLConnFactory( 1944): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1944): CP2 sync disabled
I/dalvikvm( 1944): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1944): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1944): VFY: replacing opcode 0x6e at 0x000e
D/dalvikvm( 1535): GC_EXPLICIT freed 864K, 29% free 17795K/24836K, paused 2ms+5ms, total 35ms
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
E/DataScheduler( 1944): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1944): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1944): fetch service done; releasing wakelock
I/ConfigFetchService( 1944): stopping self
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/GAV2    ( 3844): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): Killing 3385:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1944): GC_CONCURRENT freed 1615K, 26% free 18442K/24836K, paused 2ms+4ms, total 38ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1944): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1944): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1944): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3905 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/HyLog   ( 3905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3905): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3917 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
I/ActivityManager(  963): Killing 3410:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HyLog   ( 3917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3917): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 3917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:AppBoxApplication( 3917): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3917): onCreate
I/ConversationSkinProvider( 3905): skin provider oncreate
D/AppUp4  ( 3917): config : false
D/AppUp4:AbstractEnvInfo( 3917): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3917): db mvno version : 9
E/AppUp4:AutoProfileManager( 3917): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3917): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3917): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3917): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3917): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3917): config : false
D/AppUp4:AbstractServerEnvInfo( 3917): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3917): onCreate()
D/AppUp4:AppBoxCommonService( 3917): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3917): Factory mode : 0
E/[MMS]   ( 3905): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
W/BaseRuntimeLoader( 3905): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3905): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3905): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3905): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/AppUp4:NetworkUtils( 3917): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3917): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3917): onDestroy()
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3905): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3905): MmsSettings: Matching Xml Data file name = 2131034168
I/ActivityManager(  963): Killing 3431:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}
D/[MMS]   ( 3905): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3905): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3905): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3905): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3905): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3905): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3905): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3905): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3905): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3905): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3905): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3905): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3905): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3905): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
I/[MMS]   ( 3905): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/LGDrmService( 3905): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  274): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  274): qmi_init:  Created client handle b85439d8
E/Diag_Lib(  274): qmi_client [274] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  274): Sending signal ...... to read cmd data 
E/Diag_Lib(  274): qmi error code.........:0
E/Diag_Lib(  274): qmi sys error code.........:0
D/DRM_Adap(  274): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  274): Setting the api flag to : 1
E/Diag_Lib(  274): qmi_client [274] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  274):  API Flag .............. 1 
E/Diag_Lib(  274):  Message ID ............... 37 
E/Diag_Lib(  274): qmi_service_release called, user_handle=20200
E/Diag_Lib(  274): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  274): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  274): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  274): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  274): qmi_client [274] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  274): Sending signal ...... to read cmd data 
E/Diag_Lib(  274): qmi error code.........:0
E/Diag_Lib(  274): qmi sys error code.........:0
D/DRM_Adap(  274): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  274): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  274): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  274): qmi_init:  Created client handle b85439f0
E/Diag_Lib(  274): qmi_client [274] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  274): Sending signal ...... to read cmd data 
E/Diag_Lib(  274): qmi error code.........:0
E/Diag_Lib(  274): qmi sys error code.........:0
D/DRM_Adap(  274): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  274): Setting the api flag to : 1
E/Diag_Lib(  274): qmi_client [274] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  274):  API Flag .............. 1 
E/Diag_Lib(  274):  Message ID ............... 37 
E/Diag_Lib(  274): qmi_service_release called, user_handle=20200
E/Diag_Lib(  274): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  274): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  274): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  274): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  274): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  274): qmi_client [274] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  274): qmi_client [274] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  274): Sending signal ...... to read cmd data 
E/Diag_Lib(  274): qmi error code.........:0
E/Diag_Lib(  274): qmi sys error code.........:0
D/DRM_Adap(  274): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  274): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 3905): isDrmV1 =true
V/DrmWrapper( 3905): isDrmV2 =false
V/MmsConfig( 3905): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3905): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3905): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3905): [init]CMAS features are initialized for US country. Returning.
V/Contact ( 3905): Contact init()_Create new insatnce
I/MessagingNotification( 3905): registerLEDObserver
I/MessagingNotification( 3905): registerLEDObserver REGISTER
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/MmsConfig( 3905): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
I/LOG_TAG ( 3905): registerContactDBChangeObserver
D/CountryDetector(  963): The first listener is added
E/ActivityThread( 3905): Failed to find provider info for com.lge.ims.provider.uc
V/SmsReceiverService( 3905): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3905): [loadRssi] File not exist 
V/LGRssiData( 3905): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3905): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3905): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3905): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3905): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3905): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3905): [getValue] FEATURE key : vzw_roaming_state, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3975): 
D/AndroidRuntime( 3975): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3975): CheckJNI is OFF
D/dalvikvm( 3975): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3975): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3975): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3975): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3975): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3975): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3975): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3975): failed to load memtrack module: -2
D/AndroidRuntime( 3975): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3975
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (107 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  963): GC_FOR_ALLOC freed 579K, 12% free 27213K/30784K, paused 64ms, total 66ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 29.575MB for 856096-byte allocation
D/dalvikvm(  963): GC_FOR_ALLOC freed 128K, 12% free 27922K/31624K, paused 64ms, total 64ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 30.267MB for 856096-byte allocation
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{436e93c8 stackId=1, 2 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/UsbSettingsControl( 2517): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2517): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 3975): Shutting down VM
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3}
D/dalvikvm( 3975): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 4ms
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3989 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3479): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/SlideAside( 3479): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3479): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3989): Binding Chromium to the background looper Looper (main, tid 1) {42dd0c70}
I/chromium( 3989): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3989): Initializing chromium process, renderers=0
W/chromium( 3989): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3989): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3989): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3989): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3989): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3989): Remote Branch: 
I/Adreno-EGL( 3989): Local Patches: 
I/Adreno-EGL( 3989): Reconstruct Branch: 
I/dalvikvm( 3989): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3989): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3989): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3989): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3989): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3989): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3989): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3989): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3989): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3989): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3989): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3989): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3989): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3989): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3989): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/OpenGLRenderer( 3989): Enabling debug mode 0
,W/AwContents( 3989): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +434ms
I/ActivityManager( 3989): Timeline: Activity_idle id: android.os.BinderProxy@42dd2438 time:41552
,I/chromium( 3989): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3989): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  963): Waited long enough for: ServiceRecord{436d5888 u0 com.lge.slideaside/.MainService}
,D/JsMessageQueue( 3989): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3989): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42dd64f8
,D/dalvikvm( 3989): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42dd64f8
,D/jxcore_app_log( 3989): JniHelper::setJavaVM(0x41d7d808), pthread_self() = 1634887008
,D/JX-Cordova( 3989): jxcore cordova android initializing
,W/jxcore-log( 3989): Initializing JXcore engine
,W/jxcore-log( 3989): JXcore engine is ready
,W/jxcore-log( 3989): Starting JXcore engine
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3} time:41884
D/ActivityManager(  963): no-history finish of ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{43877f78 ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2517): [AUTORUN] onStop()
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3989): Platform android
W/jxcore-log( 3989): 
,W/jxcore-log( 3989): Process ARCH arm
W/jxcore-log( 3989): 
,I/jxcore-log( 3989): JXcore Cordova bridge is ready!
I/jxcore-log( 3989): 
,W/jxcore-log( 3989): JXcore engine is started
,I/chromium( 3989): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3989): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 3989): >> LGE-LG-D802
E/jxcore-log( 3989): 
,I/jxcore-log( 3989): Total memory 1943035904
I/jxcore-log( 3989): 
I/jxcore-log( 3989): Free memory 474013696
I/jxcore-log( 3989): 
I/jxcore-log( 3989): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): userPath [ 'www' ]
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): Size 1080 1776
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): Screen Brightness 255
I/jxcore-log( 3989): 
,E/jxcore-log( 3989): Dummy Error Log.
E/jxcore-log( 3989): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 3989): getBuffer is called!!!!
I/jxcore-log( 3989): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinService( 1944): Done disabling old GoogleServicesFramework version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3844): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1535): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  963): Killing 3367:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4322d8a0:true
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  963): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  963): Message: 2
D/WifiService(  963): New client listening to asynchronous messages
,D/WifiService(  963): setWifiEnabled: false pid=3989, uid=10311
,E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3989): ****TEST TOOK:  5039  ms ****
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3989): 
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.559097 Y: -0.414062 Z: 9.734055 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.559097 .y:-0.414062 .z:9.734055
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.548996 Y: -0.411774 Z: 9.725311 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.548996 .y:-0.411774 .z:9.725311
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AndroidRuntime( 4050): 
D/AndroidRuntime( 4050): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4050): CheckJNI is OFF
,D/dalvikvm( 4050): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4050): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4050): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4050): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4050): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4050): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 4050): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4050): failed to load memtrack module: -2
,D/AndroidRuntime( 4050): Calling main entry com.android.commands.pm.Pm
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 3989:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  963): Force removing ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{435d57c0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  963):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{436e93c8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
,I/WindowState(  963): WIN DEATH: Window{436425e0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  963): Client connection lost with reason: 4
,W/PackageSettings(  963): Skipping PackageSetting{4328ce98 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
,D/UsbSettings( 2517): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,V/UsbSettings( 2517): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,D/KeyguardModel( 1143): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1450): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
D/AppUp4:Utils( 3667): [getPackageName] uri : package:com.example.hello
,D/AppUp4  ( 3667): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
E/SlideAside( 3479): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/UsbSettings( 2517): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
,W/System.err( 2575): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,V/UsbSettings( 2517): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/AppUp4  ( 3667):  isExcludedPackage  packagename = com.example.hello
,I/SlideAside( 3479): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,W/System.err( 2575): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/System.err( 2575): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2575): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2575): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2575): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2575): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2575): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2575): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2575): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2575): 	at dalvik.system.NativeStart.main(Native Method)
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/GeofencerStateMachine( 1425): Ignoring removeGeofence because network location is disabled.
,D/AppUp4  ( 3667):  isExcludedPackage TRUE : com.example.hello
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
,D/dalvikvm( 2590): GC_EXPLICIT freed 3725K, 28% free 17915K/24836K, paused 9ms+2ms, total 115ms
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  963): GC_EXPLICIT freed 882K, 12% free 28870K/32464K, paused 3ms+7ms, total 133ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/[BNRAppListMgrReceiver]( 3351): android.intent.action.PACKAGE_REMOVED : com.example.hello
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43877e10 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  963): Handling package changes for user 0
D/KeyguardModel( 1143): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4082 uid=10090 gids={50090}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/PackageChangeReceiver( 3825): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24836K, paused 1ms+1ms, total 18ms
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/VoicemailCleanupService( 1823): Cleaning up data for package: com.example.hello
D/HyLog   ( 4082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4082): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/LockScreenSettings( 4082): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 15ms
,D/KeyguardModel( 1143): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1143): createShortcutInfo...
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+1ms, total 16ms
,D/KeyguardModel( 1143): handleShortcutListChanged...
,D/KeyguardModel( 1143): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1143): createShortcutInfo...
,D/KeyguardModel( 1143): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1143): createShortcutInfo...
,D/KeyguardModel( 1143): handleShortcutListChanged...
,D/PackageIntentReceiver( 2517): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2517): Receive package name : com.example.hello
,D/HideNavigationAppsReceiver( 2517): Delete mPackageMame : com.example.hello
I/ActivityManager(  963): Killing 3313:com.google.android.music:main/u0a107 (adj 15): empty #17
,D/dalvikvm( 1490): GC_CONCURRENT freed 5381K, 9% free 61076K/66648K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 22ms
F/ActivityManager(  963): Service ServiceRecord{437b5de0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43843a58 3313:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  963): Service ServiceRecord{437a6d30 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43843a58 3313:com.google.android.music:main/u0a107} not same as in map: null
D/BackupManagerService(  963): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/InteractionManagerConfigurator(  963): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  963): com.example.hello isn't inclued in dragdropPackageList
V/BackupManagerService(  963): removePackageParticipantsLocked: uid=10311 #1
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,D/WifiController(  963): battery changed pluggedType: 2
I/IcingCorporaProvider( 2590): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm(  963): GC_EXPLICIT freed 578K, 12% free 28861K/32464K, paused 3ms+14ms, total 196ms
I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4099 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4099): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4099): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4099): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,W/ContextImpl( 4099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/dalvikvm( 3743): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3743): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3743): VFY: replacing opcode 0x6e at 0x0013
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 298 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 299 plugged : true isCharging : false
,I/ActivityManager(  963): Killing 3213:com.google.android.talk/u0a77 (adj 15): empty #17
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/AndroidRuntime( 4050): Shutting down VM
,D/dalvikvm( 4050): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/IcingCorporaProvider( 2590): UpdateCorporaTask done [took 99 ms] updated apps [took 98 ms] 
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
E/NetworkScheduler.SchedulerReceiver( 1535): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1535): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1944): Clearing selected account for com.example.hello
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,D/WeatherAncestor( 1892): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:11:54
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
,D/UpdateThreadPoolManager( 1892): 2 : This is isUpdating : false
,I/LocationSettingsChecker( 1944): Removing dialog suppression flag for package com.example.hello
,D/WeatherQuickCover( 1892): 2 : quick cover state : opened : 0
,D/WeatherService( 1892): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1892): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1892): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1892): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherAncestor( 1892): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:11:54
,D/WeatherService( 1892): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/PackageIntentReceiver( 2517): Not supported Hotkey customization function 
,D/WeatherQuickCover( 1892): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/Weather.Utils( 1892): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1892): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1892): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1892): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1892): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/ActivityManager(  963): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4128 uid=10065 gids={50065, 1028, 4002}
I/ActivityManager(  963): Delaying start of: ServiceRecord{43825e68 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/UpdateThreadPoolManager( 1892): 2 : This is isUpdating : false
D/WeatherService( 1892): 2 : requestRefreshAppWidget, isUpdating : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/WeatherAncestor( 1892): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1892): 2 : Map key string is -2
D/lim     ( 1892): 2 : time = 15:11
I/WeatherReflect( 1892): Model Name : LG-D802
D/WeatherTheme( 1892): 2 : exactly same view!
D/WeatherTheme( 1892): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherQuickCover( 1892): 2 : quick cover state : opened : 0
D/HyLog   ( 4128): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
D/HyLog   ( 4128): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4128): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Weather.Utils( 1892): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1892): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1892): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1535): onCreate
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ConfigFetchService( 1944): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/GOOGLEHELP_CompatibleDatabase( 1944): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1944): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1944): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1944): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/GOOGLEHELP_CompatibleDatabase( 1944): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1944): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 300 plugged : true isCharging : false
D/GOOGLEHELP_CompatibleDatabase( 1944): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/GOOGLEHELP_CompatibleDatabase( 1944): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1944): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/BaseAppContext( 1944): Using Auth Proxy for data requests.
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1} time:48534
,D/GOOGLEHELP_CompatibleDatabase( 1944): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1944): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1944): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1944): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/Documents( 4128): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 5012K, 9% free 61683K/67444K, paused 19ms, total 19ms
,I/ActivityManager(  963): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4144 uid=10005 gids={50005, 1028, 1015, 1023}
,I/Icing   ( 1944): doRemovePackageData com.example.hello
I/ActivityManager(  963): Killing 2091:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  963): Killing 3797:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/PeopleContactsSync( 1944): CP2 sync disabled
,D/HyLog   ( 4144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4144): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
D/ExternalStorage( 4144): After updating volumes, found 1 active roots
D/Documents( 4128): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4128): Loading roots for com.android.providers.downloads.documents
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@42dccec0 time:48636
I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4158 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4158): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4158): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): Killing 3917:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{432027f0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{435eb9d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Delaying start of: ServiceRecord{4393d300 u0 com.android.providers.downloads/.DownloadService}
,D/Documents( 4128): Loading roots for com.android.providers.media.documents
,D/Documents( 4128): Loading roots for com.google.android.apps.docs.storage
,W/DriveInitializer( 1944): Background init thread started
,W/DriveInitializer( 1944): Awaiting to be initialized
,E/SQLiteLog( 1944): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,E/DocListDatabase( 1944): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1944): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1944): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1944): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/DocListDatabase( 1944): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 1944): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1944): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/DocListDatabase( 1944): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1944): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1944): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 1944): Background init thread ended
W/dalvikvm( 1944): threadid=25: thread exiting with uncaught exception (group=0x41d8ee48)
,E/SQLiteLog( 1944): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/Documents( 4128): Update found 7 roots in 219ms
,E/DriveAsyncService( 1944): disk I/O error (code 3850)
E/DriveAsyncService( 1944): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1944): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1944): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1944): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1944): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1944): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1944): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1944): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 1944): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1944): Process: com.google.android.gms, PID: 1944
E/AndroidRuntime( 1944): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1944): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1944): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
E/AndroidRuntime( 1944): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 1944): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1944): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
E/AndroidRuntime( 1944): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1944): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 1944): 	at com.google.android.gms.drive.r.run(SourceFile:69)
D/Documents( 4128): Loading roots for com.android.externalstorage.documents
E/DropBoxManagerService(  963): Can't write: system_app_crash
E/DropBoxManagerService(  963): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  963): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  963): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  963): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  963): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  963): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  963): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  963): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  963): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  963): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  963): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  963): 	... 5 more
D/Documents( 4128): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4128): Used cached roots for com.android.providers.media.documents
D/Documents( 4128): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4128): Update found 7 roots in 21ms
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
,E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=29 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
,E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
,E/qdoverlay(  267): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
,E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=32 id=0 flags=0x0 priv=0
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
E/qdoverlay(  267): == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=8
E/qdoverlay(  267): data msmfb_data offset=0 memid=26 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for FBUpdate
E/qdhwcomposer(  267): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
