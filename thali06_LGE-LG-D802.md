#### Test 50242285e132180_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
--------- beginning of /dev/log/main
D/EulaProviderUpdateObserver( 2915): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2915): uri : package:com.example.hello
I/ActivityManager(  963): Killing 3405:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1849): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}
I/ActivityManager(  963): Waited long enough for: ServiceRecord{43039940 u0 com.google.android.gms/.config.ConfigFetchService}
I/ConfigFetchService( 1849): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1849): launchTask
W/dalvikvm( 1849): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1849): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WlbpCximdkN0ZiolhpAA5F9NalmSWRM_DZR2upo1tV96y_Gm-nsh3YSwE0F9g-DsMB65hFwBQGt1h2I8BPIG0fhZfThaAjkR3c3XAAziUstCADB6pvuKxG69atSgib7j0eYQK2Ug4sl5H0vTzZEBBEEAbD8ifOlz_B38iK_uAb_2uQrKswlkTTaWO7zVm9qLcCH3bw
I/GoogleURLConnFactory( 1849): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1849): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1849): Failed to find package metadata for com.example.hello
D/Vision  ( 1849): No vision deps
I/PeopleContactsSync( 1849): CP2 sync disabled
I/dalvikvm( 1849): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1849): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1849): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
E/DataScheduler( 1849): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1849): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1849): fetch service done; releasing wakelock
I/ConfigFetchService( 1849): stopping self
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
I/Icing   ( 1849): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
D/Icing   ( 1849): Loaded CLD2 Version V2.0 - 20141016
D/dalvikvm( 1849): GC_CONCURRENT freed 1603K, 26% free 18473K/24832K, paused 3ms+4ms, total 37ms
I/Icing   ( 1849): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/ActivityManager(  963): Killing 3423:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  963): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3908 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}
D/HyLog   ( 3908): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3908): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3908): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ConversationSkinProvider( 3908): skin provider oncreate
E/[MMS]   ( 3908): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
W/BaseRuntimeLoader( 3908): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3908): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3908): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3908): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3908): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3908): MmsSettings: Matching Xml Data file name = 2131034168
D/[MMS]   ( 3908): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3908): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3908): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3908): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3908): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3908): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3908): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3908): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3908): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3908): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3908): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3908): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3908): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3908): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
I/[MMS]   ( 3908): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/LGDrmService( 3908): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b87e49d8
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
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b87e49f0
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
I/DrmWrapper( 3908): isDrmV1 =true
V/DrmWrapper( 3908): isDrmV2 =false
V/MmsConfig( 3908): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3908): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3908): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3908): [init]CMAS features are initialized for US country. Returning.
V/Contact ( 3908): Contact init()_Create new insatnce
I/MessagingNotification( 3908): registerLEDObserver
I/MessagingNotification( 3908): registerLEDObserver REGISTER
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
D/LocationManagerService(  963): getProviders()=[passive, gps]
V/MmsConfig( 3908): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/LocationManagerService(  963): request 4313a6d0 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  963): The first listener is added
E/ActivityThread( 3908): Failed to find provider info for com.lge.ims.provider.uc
I/LOG_TAG ( 3908): registerContactDBChangeObserver
V/SmsReceiverService( 3908): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/SmsReceiverService( 3908): onStart: #2 mResultCode: -1 = Activity.RESULT_OK
V/SmsReceiverService( 3908): onStart: #3 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3908): [loadRssi] File not exist 
V/LGRssiData( 3908): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3908): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3908): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3908): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3908): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3908): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3908): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3908): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3908): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3908): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3908): [getValue] FEATURE key : vzw_roaming_state, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3942 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3942): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:AppBoxApplication( 3942): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3942): onCreate
D/AppUp4  ( 3942): config : false
D/AppUp4:AbstractEnvInfo( 3942): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3942): db mvno version : 9
E/AppUp4:AutoProfileManager( 3942): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3942): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
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
W/GAV2    ( 3848): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/GAV2    ( 3848): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  963): Killing 3387:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/AndroidRuntime( 3961): 
D/AndroidRuntime( 3961): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3961): CheckJNI is OFF
D/dalvikvm( 3961): Trying to load lib libjavacore.so 0x0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 3961): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3961): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3961): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3961): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3961): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3961): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3961): failed to load memtrack module: -2
D/AndroidRuntime( 3961): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3961
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (133 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  963): GC_FOR_ALLOC freed 708K, 12% free 27384K/31040K, paused 71ms, total 71ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 29.739MB for 856096-byte allocation
D/dalvikvm(  963): GC_FOR_ALLOC freed 40K, 12% free 28181K/31880K, paused 64ms, total 64ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 30.516MB for 856096-byte allocation
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{4311e028 stackId=1, 2 tasks}
D/AndroidRuntime( 3961): Shutting down VM
D/UsbSettingsControl( 2551): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2551): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3504): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 3961): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  963): startService SlideAside
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3989 uid=10311 gids={50311, 3003, 3001, 3002}
I/SlideAside( 3504): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3504): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3989): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3989): Binding Chromium to the background looper Looper (main, tid 1) {427f0d78}
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
W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3989): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 3989): Enabling debug mode 0
,W/AwContents( 3989): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  963): IME STATUS OFF
,W/AwContents( 3989): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +408ms
,I/ActivityManager( 3989): Timeline: Activity_idle id: android.os.BinderProxy@427f2450 time:40823
,I/chromium( 3989): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3989): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  963): Waited long enough for: ServiceRecord{430e4340 u0 com.lge.slideaside/.MainService}
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/JsMessageQueue( 3989): Set native->JS mode to OnlineEventsBridgeMode
,D/WeatherService( 1820): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:12:0
D/WeatherService( 1820): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1820): 2 : SDK version : 19
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.easyhome / false
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1820): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1820): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:12:0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449501120032, nextTick: 59999, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449501120033, nextTick: 60000, mDrawingTime: 0
,D/dalvikvm( 3989): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x427f6510
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/dalvikvm( 3989): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x427f6510
D/jxcore_app_log( 3989): JniHelper::setJavaVM(0x416b4838), pthread_self() = 1633974704
D/JX-Cordova( 3989): jxcore cordova android initializing
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,W/jxcore-log( 3989): Initializing JXcore engine
,W/jxcore-log( 3989): JXcore engine is ready
,W/jxcore-log( 3989): Starting JXcore engine
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ActivityManager(  963): no-history finish of ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3} time:41179
V/ActivityManager(  963): Finishing activity token=Token{431fb3e8 ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,D/UsbSettings( 2551): [AUTORUN] onStop()
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3989): Platform android
W/jxcore-log( 3989): 
,W/jxcore-log( 3989): Process ARCH arm
W/jxcore-log( 3989): 
,I/jxcore-log( 3989): JXcore Cordova bridge is ready!
I/jxcore-log( 3989): 
,W/jxcore-log( 3989): JXcore engine is started
,I/chromium( 3989): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 3989): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/jxcore-log( 3989): >> LGE-LG-D802
E/jxcore-log( 3989): 
,I/jxcore-log( 3989): Total memory 1943035904
I/jxcore-log( 3989): 
I/jxcore-log( 3989): Free memory 466624512
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
E/jxcore-log( 3989): Dummy Error Log.
E/jxcore-log( 3989): 
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 3989): getBuffer is called!!!!
I/jxcore-log( 3989): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/GAV2    ( 3848): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1849): Done disabling old GoogleServicesFramework version
,I/ConfigService( 1545): onDestroy
,I/ActivityManager(  963): Killing 3442:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431ebfb0:true
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  963): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  963): Message: 2
,D/WifiService(  963): New client listening to asynchronous messages
,D/WifiService(  963): setWifiEnabled: false pid=3989, uid=10311
,E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3989): ****TEST TOOK:  5093  ms ****
I/jxcore-log( 3989): 
,I/jxcore-log( 3989): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3989): 
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AndroidRuntime( 4057): 
D/AndroidRuntime( 4057): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4057): CheckJNI is OFF
,D/dalvikvm( 4057): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4057): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4057): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4057): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4057): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4057): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 4057): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4057): failed to load memtrack module: -2
,D/AndroidRuntime( 4057): Calling main entry com.android.commands.pm.Pm
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 3989:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  963): Force removing ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43027c98 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  963):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4311e028 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1485): [Launcher.java:4947:onStart()]onStart
,D/UsbSettings( 2551): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2551): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2551): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2551): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43127c08 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,D/WifiService(  963): Client connection lost with reason: 4
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,I/WindowState(  963): WIN DEATH: Window{42ffd920 u0 com.example.hello/com.example.hello.MainActivity}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  963): Skipping PackageSetting{42c69a38 com.test.thalitest/10304} due to missing metadata
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.463608 Y: -0.386765 Z: 9.763550 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463608 .y:-0.386765 .z:9.763550
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/[LGHome]EVENT( 1485): [Launcher.java:717:onResume()]onResume
I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 2604): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,E/SlideAside( 3504): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3504): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,W/System.err( 2604): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2604): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2604): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2604): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2604): 	at android.os.Handler.dispatchMessage(Handler.java:95)
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "sms"
W/System.err( 2604): 	at android.os.Looper.loop(Looper.java:136)
,W/System.err( 2604): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2604): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2604): 	at java.lang.reflect.Method.invoke(Method.java:515)
D/AppUp4:Utils( 3665): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3665): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3665):  isExcludedPackage  packagename = com.example.hello
W/System.err( 2604): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2604): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2604): 	at dalvik.system.NativeStart.main(Native Method)
,I/[LGHome]LGActivityUtil( 1485): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/AppUp4  ( 3665):  isExcludedPackage TRUE : com.example.hello
,D/dalvikvm( 2620): GC_EXPLICIT freed 3969K, 27% free 18151K/24832K, paused 2ms+4ms, total 38ms
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451523 Y: -0.397568 Z: 9.771713 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451523 .y:-0.397568 .z:9.771713
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4088 uid=10090 gids={50090}
,I/[LGHome]EVENT( 1485): [Launcher.java:868:onResume()]onResume end
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/[BNRAppListMgrReceiver]( 3375): android.intent.action.PACKAGE_REMOVED : com.example.hello
D/HyLog   ( 4088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4088): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1485): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
,I/LockScreenSettings( 4088): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/InputMethodManagerService(  963): IME STATUS OFF
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/Binder  ( 1336): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1336): java.lang.NullPointerException
W/Binder  ( 1336): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1336): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1336): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1336): 	at dalvik.system.NativeStart.run(Native Method)
D/dalvikvm(  963): GC_EXPLICIT freed 1166K, 11% free 29154K/32720K, paused 3ms+14ms, total 131ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 123ms
W/InputMethodManagerService(  963): Got RemoteException sending setActive(false) notification to pid 3989 uid 10311
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/VoicemailCleanupService( 1762): Cleaning up data for package: com.example.hello
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
D/administrator(  963): Handling package changes for user 0
I/PackageChangeReceiver( 3830): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1140): createShortcutInfo...
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/KeyguardModel( 1140): handleShortcutListChanged...
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
,D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1140): createShortcutInfo...
,D/PackageIntentReceiver( 2551): Not supported Hotkey customization function 
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1140): createShortcutInfo...
,D/HideNavigationAppsReceiver( 2551): Receive package name : com.example.hello
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1140): createShortcutInfo...
,D/HideNavigationAppsReceiver( 2551): Delete mPackageMame : com.example.hello
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/KeyguardModel( 1140): handleShortcutListChanged...
,I/IcingCorporaProvider( 2620): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  963): Killing 3338:com.google.android.music:main/u0a107 (adj 15): empty #17
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4105 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,F/ActivityManager(  963): Service ServiceRecord{432746d0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{431f7778 3338:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  963): Service ServiceRecord{43269fa8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{431f7778 3338:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,D/BackupManagerService(  963): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  963): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  963): com.example.hello isn't inclued in dragdropPackageList
V/BackupManagerService(  963): removePackageParticipantsLocked: uid=10311 #1
,D/dalvikvm( 1485): GC_CONCURRENT freed 5281K, 9% free 61064K/66540K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 1485): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/HyLog   ( 4105): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4105): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4105): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6657K, 13% free 69048K/78588K, paused 28ms, total 28ms
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/dalvikvm( 3741): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3741): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3741): VFY: replacing opcode 0x6e at 0x0013
,I/ActivityManager(  963): Killing 3021:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,E/NetworkScheduler.SchedulerReceiver( 1545): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1545): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,D/dalvikvm(  963): GC_EXPLICIT freed 619K, 11% free 29174K/32720K, paused 2ms+11ms, total 248ms
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1485): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/IcingCorporaProvider( 2620): UpdateCorporaTask done [took 164 ms] updated apps [took 164 ms] 
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/AndroidRuntime( 4057): Shutting down VM
,D/dalvikvm( 4057): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 1ms
,D/PackageBroadcastService( 1849): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1849): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/PackageIntentReceiver( 2551): Not supported Hotkey customization function 
,D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/ActivityManager(  963): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4133 uid=10065 gids={50065, 1028, 4002}
I/LocationSettingsChecker( 1849): Removing dialog suppression flag for package com.example.hello
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/ActivityManager(  963): Delaying start of: ServiceRecord{43237780 u0 com.google.android.gms/.wearable.service.WearableControlService}
,D/HyLog   ( 4133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4133): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4133): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/ConfigService( 1545): onCreate
,I/ConfigFetchService( 1849): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/Icing   ( 1849): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1849): CP2 sync disabled
I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,W/BaseAppContext( 1849): Using Auth Proxy for data requests.
,D/GOOGLEHELP_CompatibleDatabase( 1849): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/Documents( 4133): Loading roots for com.android.externalstorage.documents
,D/GOOGLEHELP_CompatibleDatabase( 1849): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1849): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1849): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1849): Using Auth Proxy for data requests.
,I/ActivityManager(  963): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4152 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  963): Killing 3806:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/GOOGLEHELP_CompatibleDatabase( 1849): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1849): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1849): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  963): Killing 3942:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/WeatherAncestor( 1820): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:12:6
D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
,D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1820): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1820): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
D/WeatherService( 1820): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1820): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:12:6
D/WeatherService( 1820): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / true
D/GOOGLEHELP_CompatibleDatabase( 1849): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1849): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/GOOGLEHELP_CompatibleDatabase( 1849): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/WeatherService( 1820): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/GOOGLEHELP_CompatibleDatabase( 1849): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/HyLog   ( 4152): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4152): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4152): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GOOGLEHELP_CompatibleDatabase( 1849): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/UpdateThreadPoolManager( 1820): 2 : This is isUpdating : false
,D/WeatherService( 1820): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1820): 2 : buildUpdate, appWidgetId: 1
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
D/GOOGLEHELP_CompatibleDatabase( 1849): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/WeatherReflect( 1820): 2 : Map key string is -2
D/lim     ( 1820): 2 : time = 16:12
D/dalvikvm( 1485): GC_FOR_ALLOC freed 5017K, 9% free 61755K/67636K, paused 18ms, total 18ms
I/WeatherReflect( 1820): Model Name : LG-D802
D/WeatherTheme( 1820): 2 : Different view - status_min_formatted : 11 != 12
D/WeatherTheme( 1820): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1820): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1820): 2 : Fixed theme : optimus
,D/WeatherTheme( 1820): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1820): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1820): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1820): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1820): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/ExternalStorage( 4152): After updating volumes, found 1 active roots
,D/Documents( 4133): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 4133): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1} time:47957
I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4164 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  963): Killing 1717:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,D/HyLog   ( 4164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b692e0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bb01c8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1485): Timeline: Activity_idle id: android.os.BinderProxy@427ed000 time:47992
,I/ActivityManager(  963): Delaying start of: ServiceRecord{43006198 u0 com.android.providers.downloads/.DownloadService}
,D/Documents( 4133): Loading roots for com.android.providers.media.documents
,D/Documents( 4133): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4133): Update found 7 roots in 215ms
,D/Documents( 4133): Loading roots for com.android.externalstorage.documents
,D/Documents( 4133): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4133): Used cached roots for com.android.providers.media.documents
D/Documents( 4133): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4133): Update found 7 roots in 8ms
,D/dalvikvm( 1545): GC_EXPLICIT freed 594K, 29% free 17809K/24832K, paused 1ms+3ms, total 25ms
W/DriveInitializer( 1849): Awaiting to be initialized
,W/DriveInitializer( 1849): Background init thread started
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  963): battery changed pluggedType: 2
D/dalvikvm( 1156): GC_CONCURRENT freed 1279K, 6% free 25434K/26892K, paused 2ms+1ms, total 16ms
,W/DriveInitializer( 1849): Background init thread ended
,E/SQLiteLog( 1849): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1849): disk I/O error (code 3850)
E/DriveAsyncService( 1849): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1849): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1849): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1849): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1849): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1849): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1849): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1849): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 1545): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1545): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1545): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1545): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1545): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteOpenHelper( 1545): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1545): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 1545): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1545): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1545): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1545): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1545): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1545): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1545): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 1545): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1545): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1545): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1545): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1545): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1545): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1545): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 1545): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1545): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1545): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1545): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1545): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1545): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1545): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1545): 	at java.lang.Thread.run(Thread.java:841)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
