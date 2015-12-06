#### Test 502422853393492_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/EulaProviderUpdateObserver( 2940): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 2940): uri : package:com.example.hello
D/PackageBroadcastService( 1873): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1873): Loading module APK com.google.android.play.games
--------- beginning of /dev/log/system
I/ActivityManager(  963): Waited long enough for: ServiceRecord{432863b8 u0 com.google.android.gms/.config.ConfigFetchService}
I/ConfigFetchService( 1873): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1873): launchTask
W/dalvikvm( 1873): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1873): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XhJi11ruHoH1fs35Xy1Uvwv3nuTjzL9IYS1Av-vDmvbXb4gbg6oDVv-00JFYsAEJpoP2poOdP1f1rrv3WVjRkn_E1Q1MFZGySbjLWjmwD0PAVMCN_d3BCvFKvgLUiZkWssEViz83jqUjW45an5zuE_zzZq0MUIWHUsAtDmN5MBfuHWs1pd6P0Abr6oSkxtkMZgK3yz
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1873): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1873): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1873): Failed to find package metadata for com.example.hello
D/Vision  ( 1873): No vision deps
I/GoogleURLConnFactory( 1873): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1873): CP2 sync disabled
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
I/dalvikvm( 1873): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1873): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1873): VFY: replacing opcode 0x6e at 0x000e
E/DataScheduler( 1873): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1873): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1873): fetch service done; releasing wakelock
D/dalvikvm( 1538): GC_EXPLICIT freed 920K, 29% free 17810K/24832K, paused 4ms+7ms, total 41ms
I/ConfigFetchService( 1873): stopping self
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
W/GAV2    ( 3849): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  963): Killing 3427:com.lge.sizechangable.photoalbum/u0a95 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1873): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): Killing 3451:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1873): GC_CONCURRENT freed 1538K, 26% free 18428K/24832K, paused 4ms+5ms, total 88ms
I/Icing   ( 1873): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1873): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1873): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/ActivityManager(  963): Start proc com.lge.appbox.client:AppBoxCommonService for service com.lge.appbox.client/com.lge.appbox.service.AppBoxCommonService: pid=3902 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/HyLog   ( 3902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3902): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AppUp4:AppBoxApplication( 3902): AppBoxApplication onCreate()
D/AppUp4:AbstractIntentService( 3902): onCreate
D/AppUp4  ( 3902): config : false
D/AppUp4:AbstractEnvInfo( 3902): Config no : EnvRealInfo
D/AppUp4:AutoProfileManager( 3902): db mvno version : 9
E/AppUp4:AutoProfileManager( 3902): what happen...? prepareValid DB... can't do anything...
W/BaseRuntimeLoader( 3902): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3902): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3902): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3902): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/AppUp4  ( 3902): config : false
D/AppUp4:AbstractServerEnvInfo( 3902): Config no : EnvRealInfo
D/AppUp4:AppBoxCommonService( 3902): onCreate()
D/AppUp4:AppBoxCommonService( 3902): onHandleIntent begin.
D/AppUp4:AppBoxCommonService( 3902): Factory mode : 0
I/AppUp4:NetworkUtils( 3902): Active NetworkInfo : null
D/AppUp4:AppBoxCommonService( 3902): Skip invalid intent of hidden update popup .
D/AppUp4:AppBoxCommonService( 3902): onDestroy()
I/ActivityManager(  963): Start proc com.android.mms for service com.android.mms/.transaction.SmsReceiverService: pid=3916 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
I/ActivityManager(  963): Killing 3470:com.google.android.gm/u0a68 (adj 15): empty #17
D/HyLog   ( 3916): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3916): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3916): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}
I/ConversationSkinProvider( 3916): skin provider oncreate
E/[MMS]   ( 3916): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
W/BaseRuntimeLoader( 3916): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3916): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3916): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3916): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 3916): MmsSettings: loadxmlstring=open_eu_mms_config
D/[MMS]   ( 3916): MmsSettings: Matching Xml Data file name = 2131034168
D/[MMS]   ( 3916): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 3916): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 3916): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 3916): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 3916): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 3916): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 3916): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 3916): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 3916): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 3916): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 3916): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 3916): MmsSettings: [LGE]   message_counters_key = [0]
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
I/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 3916): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
D/MmsConfig( 3916): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
I/[MMS]   ( 3916): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
I/LGDrmService( 3916): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  274): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  274): qmi_init:  Created client handle b87baf58
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
E/Diag_Lib(  274): qmi_init:  Created client handle b87baf70
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
I/DrmWrapper( 3916): isDrmV1 =true
V/DrmWrapper( 3916): isDrmV2 =false
V/MmsConfig( 3916): [isMmsEnabledWhenDataDisabled]value=1
V/MmsConfigStaticVar( 3916): [setMmsEnabledWhenDataDisabled]enabled=true
V/MmsConfigStaticVar( 3916): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
D/CmasFeatures( 3916): [init]CMAS features are initialized for US country. Returning.
V/Contact ( 3916): Contact init()_Create new insatnce
I/MessagingNotification( 3916): registerLEDObserver
I/MessagingNotification( 3916): registerLEDObserver REGISTER
V/MmsConfig( 3916): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
D/CountryDetector(  963): The first listener is added
I/LOG_TAG ( 3916): registerContactDBChangeObserver
D/LocationManagerService(  963): getProviders()=[passive, gps]
D/LocationManagerService(  963): request 4355f580 passive Request[POWER_NONE passive fastest=0] from android(1000)
E/ActivityThread( 3916): Failed to find provider info for com.lge.ims.provider.uc
D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
V/SmsReceiverService( 3916): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
V/LGRssiData( 3916): [loadRssi] File not exist 
V/LGRssiData( 3916): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 3916): [loadFeatureFromXml] *** start feature loading from xml
V/TelephonyAutoProfiling( 3916): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 3916): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 3916): [getValue] FEATURE key : vzw_roaming_state, value : null
D/SmsReceiverService( 3916): [LGE] ACTION_SERVICE_STATE_CHANGED received
V/TelephonyAutoProfiling( 3916): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 3945): 
D/AndroidRuntime( 3945): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3945): CheckJNI is OFF
D/dalvikvm( 3945): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3945): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3945): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3945): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3945): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3945): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 3945): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3945): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 3945): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3945
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (112 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  963): GC_FOR_ALLOC freed 871K, 12% free 27026K/30624K, paused 66ms, total 66ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 29.388MB for 856096-byte allocation
D/dalvikvm(  963): GC_FOR_ALLOC freed 93K, 12% free 27770K/31464K, paused 70ms, total 70ms
I/dalvikvm-heap(  963): Grow heap (frag case) to 30.115MB for 856096-byte allocation
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{43077d78 stackId=1, 2 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  963): startService SlideAside
D/UsbSettingsControl( 2568): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2568): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 3945): Shutting down VM
I/SlideAside( 3517): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3}
D/dalvikvm( 3945): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 5ms
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3967 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/SlideAside( 3517): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3517): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
D/HyLog   ( 3967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 3967): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 3967): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 3967): Binding Chromium to the background looper Looper (main, tid 1) {4284cd68}
I/chromium( 3967): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 3967): Initializing chromium process, renderers=0
W/chromium( 3967): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 3967): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3967): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 3967): Build Date: 01/20/14 Mon
I/Adreno-EGL( 3967): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 3967): Remote Branch: 
I/Adreno-EGL( 3967): Local Patches: 
I/Adreno-EGL( 3967): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/dalvikvm( 3967): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3967): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3967): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3967): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3967): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3967): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3967): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3967): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3967): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3967): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3967): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3967): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3967): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3967): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3967): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3967): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3967): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3967): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3967): CordovaWebView is running on device made by: LGE
D/dalvikvm( 3967): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 3967): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3967): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 3967): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 3967): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/OpenGLRenderer( 3967): Enabling debug mode 0
,W/AwContents( 3967): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  963): IME STATUS OFF
,W/AwContents( 3967): nativeOnDraw failed; clearing to background color.
,I/ActivityManager( 3967): Timeline: Activity_idle id: android.os.BinderProxy@4284e440 time:41238
,I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +504ms
,I/chromium( 3967): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3967): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3967): Set native->JS mode to OnlineEventsBridgeMode
,D/ActivityManager(  963): no-history finish of ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}
,V/ActivityManager(  963): Finishing activity token=Token{431e3578 ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3}
,D/UsbSettings( 2568): [AUTORUN] onStop()
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3} time:41508
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,I/chromium( 3967): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/dalvikvm( 3967): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428525f0
,D/dalvikvm( 3967): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x428525f0
D/jxcore_app_log( 3967): JniHelper::setJavaVM(0x41710838), pthread_self() = 1632125624
,D/JX-Cordova( 3967): jxcore cordova android initializing
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/chromium( 3967): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/ActivityManager(  963): Waited long enough for: ServiceRecord{431b28d8 u0 com.lge.slideaside/.MainService}
,W/jxcore-log( 3967): Initializing JXcore engine
,W/jxcore-log( 3967): JXcore engine is ready
,W/jxcore-log( 3967): Starting JXcore engine
,W/jxcore-log( 3967): Platform android
W/jxcore-log( 3967): 
,W/jxcore-log( 3967): Process ARCH arm
W/jxcore-log( 3967): 
,I/jxcore-log( 3967): JXcore Cordova bridge is ready!
I/jxcore-log( 3967): 
,W/jxcore-log( 3967): JXcore engine is started
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/jxcore-log( 3967): >> LGE-LG-D802
E/jxcore-log( 3967): 
,I/jxcore-log( 3967): Total memory 1943035904
I/jxcore-log( 3967): 
I/jxcore-log( 3967): Free memory 475762688
I/jxcore-log( 3967): 
I/jxcore-log( 3967): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3967): 
,I/jxcore-log( 3967): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3967): 
I/jxcore-log( 3967): userPath [ 'www' ]
I/jxcore-log( 3967): 
I/jxcore-log( 3967): Size 1080 1776
I/jxcore-log( 3967): 
I/jxcore-log( 3967): Screen Brightness 255
I/jxcore-log( 3967): 
E/jxcore-log( 3967): Dummy Error Log.
E/jxcore-log( 3967): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 3967): getBuffer is called!!!!
I/jxcore-log( 3967): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1809): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:0:0
D/WeatherService( 1809): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1809): 2 : SDK version : 19
,D/WeatherQuickCover( 1809): 2 : quick cover state : opened : 0
D/Weather.Utils( 1809): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1809): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1809): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1809): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1809): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:0:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449414000037, nextTick: 59996, mDrawingTime: 0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1449414000037, nextTick: 59995, mDrawingTime: 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 3849): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinService( 1873): Done disabling old GoogleServicesFramework version
,I/ConfigService( 1538): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/ActivityManager(  963): Killing 3410:com.android.calendar/u0a15 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b88770:true
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  963): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  963): Message: 2
,D/WifiService(  963): New client listening to asynchronous messages
,D/WifiService(  963): setWifiEnabled: false pid=3967, uid=10311
,E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
,I/jxcore-log( 3967): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 3967): 
,I/jxcore-log( 3967): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3967): 
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.442917 Y: -0.395462 Z: 9.761978 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442917 .y:-0.395462 .z:9.761978
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.459946 Y: -0.389008 Z: 9.754395 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459946 .y:-0.389008 .z:9.754395
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/AndroidRuntime( 4056): 
D/AndroidRuntime( 4056): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4056): CheckJNI is OFF
,D/dalvikvm( 4056): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4056): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4056): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4056): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4056): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4056): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,E/memtrack( 4056): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4056): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 4056): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 3967:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  963): Force removing ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43221fa8 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  963):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43077d78 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,I/WindowState(  963): WIN DEATH: Window{43098080 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  963): Client connection lost with reason: 4
,I/dalvikvm(  963): Total arena pages for JIT: 15
,W/PackageSettings(  963): Skipping PackageSetting{42cb9110 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
,D/UsbSettings( 2568): [AUTORUN] onDestroy() : getDefaultFunction =boot
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,D/dalvikvm( 2641): GC_EXPLICIT freed 3725K, 28% free 17914K/24832K, paused 1ms+2ms, total 28ms
,V/UsbSettings( 2568): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2568): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2568): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 2626): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 2626): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2626): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2626): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2626): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2626): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 2626): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2626): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2626): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 2626): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2626): 	at dalvik.system.NativeStart.main(Native Method)
,W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:Utils( 3643): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3643): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3643):  isExcludedPackage  packagename = com.example.hello
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
E/SlideAside( 3517): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3517): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4082 uid=10090 gids={50090}
D/AppUp4  ( 3643):  isExcludedPackage TRUE : com.example.hello
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed 42K, 34% free 16472K/24832K, paused 1ms+3ms, total 19ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/dalvikvm(  963): GC_EXPLICIT freed 933K, 12% free 28680K/32304K, paused 3ms+7ms, total 95ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/[BNRAppListMgrReceiver]( 3398): android.intent.action.PACKAGE_REMOVED : com.example.hello
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43086fd8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,D/HyLog   ( 4082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4082): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
D/administrator(  963): Handling package changes for user 0
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/LockScreenSettings( 4082): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/VoicemailCleanupService( 1722): Cleaning up data for package: com.example.hello
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputMethodManagerService(  963): IME STATUS OFF
,W/Binder  ( 1299): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1299): java.lang.NullPointerException
W/Binder  ( 1299): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1299): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1299): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1299): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageChangeReceiver( 3826): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/InputMethodManagerService(  963): Got RemoteException sending setActive(false) notification to pid 3967 uid 10311
,D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
,D/dalvikvm(  963): GC_EXPLICIT freed 523K, 12% free 28713K/32304K, paused 3ms+13ms, total 137ms
I/InteractionManagerConfigurator(  963): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  963): com.example.hello isn't inclued in dragdropPackageList
,D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
,D/PackageIntentReceiver( 2568): Not supported Hotkey customization function 
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
,D/HideNavigationAppsReceiver( 2568): Receive package name : com.example.hello
D/BackupManagerService(  963): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  963): removePackageParticipantsLocked: uid=10311 #1
D/HideNavigationAppsReceiver( 2568): Delete mPackageMame : com.example.hello
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
I/IcingCorporaProvider( 2641): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/KeyguardModel( 1141): handleShortcutListChanged...
,D/AndroidRuntime( 4056): Shutting down VM
I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4103 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  963): Killing 3357:com.google.android.music:main/u0a107 (adj 15): empty #17
D/dalvikvm( 4056): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 1ms
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,F/ActivityManager(  963): Service ServiceRecord{431b9b80 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432b3b48 3357:com.google.android.music:main/u0a107} not same as in map: null
D/HyLog   ( 4103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4103): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1141): GC_FOR_ALLOC freed 5695K, 12% free 69580K/78324K, paused 22ms, total 22ms
W/ContextImpl( 4103): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,F/ActivityManager(  963): Service ServiceRecord{43079c98 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432b3b48 3357:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,I/dalvikvm( 3718): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3718): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3718): VFY: replacing opcode 0x6e at 0x0013
D/dalvikvm( 1489): GC_CONCURRENT freed 5273K, 9% free 61082K/66536K, paused 4ms+3ms, total 33ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
E/NetworkScheduler.SchedulerReceiver( 1538): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1538): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  963): Killing 3261:com.google.android.talk/u0a77 (adj 15): empty #17
,D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/IcingCorporaProvider( 2641): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1873): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/ChimeraModuleLdr( 1873): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1873): Clearing selected account for com.example.hello
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
D/PackageIntentReceiver( 2568): Not supported Hotkey customization function 
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
D/ChimeraCfgMgr( 1873): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1873): Module APK com.google.android.play.games already loaded
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/ActivityManager(  963): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4130 uid=10065 gids={50065, 1028, 4002}
D/KeyguardModel( 1141): handleShortcutListChanged...
I/LocationSettingsChecker( 1873): Removing dialog suppression flag for package com.example.hello
E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
D/HyLog   ( 4130): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4130): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4130): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/ActivityManager(  963): Delaying start of: ServiceRecord{431de128 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/ConfigService( 1538): onCreate
,I/ConfigFetchService( 1873): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,W/BaseAppContext( 1873): Using Auth Proxy for data requests.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/GOOGLEHELP_CompatibleDatabase( 1873): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1873): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1873): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1873): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/Documents( 4130): Loading roots for com.android.externalstorage.documents
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
D/GOOGLEHELP_CompatibleDatabase( 1873): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1873): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,I/ActivityManager(  963): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4150 uid=10005 gids={50005, 1028, 1015, 1023}
D/GOOGLEHELP_CompatibleDatabase( 1873): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
W/BaseAppContext( 1873): Using Auth Proxy for data requests.
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,D/GOOGLEHELP_CompatibleDatabase( 1873): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1873): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/HyLog   ( 4150): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4150): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4150): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GOOGLEHELP_CompatibleDatabase( 1873): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1873): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1873): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1873): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/WeatherAncestor( 1809): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:0:5
I/ActivityManager(  963): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  963): Killing 3798:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/ExternalStorage( 4150): After updating volumes, found 1 active roots
,D/Documents( 4130): Updating roots due to change at content://com.android.externalstorage.documents/root
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
D/UpdateThreadPoolManager( 1809): 2 : This is isUpdating : false
,D/Documents( 4130): Loading roots for com.android.providers.downloads.documents
,D/WeatherQuickCover( 1809): 2 : quick cover state : opened : 0
,D/WeatherService( 1809): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1809): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1809): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1809): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1809): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1809): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:0:5
,D/WeatherService( 1809): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1809): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/Weather.Utils( 1809): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1809): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1809): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1809): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1809): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1809): 2 : This is isUpdating : false
D/WeatherService( 1809): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1809): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1809): 2 : Map key string is -2
,D/lim     ( 1809): 2 : time = 16:00
I/WeatherReflect( 1809): Model Name : LG-D802
D/WeatherTheme( 1809): 2 : Different view - status_hour_formatted : 15 != 16
,D/WeatherTheme( 1809): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1809): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1809): 2 : Fixed theme : optimus
,D/WeatherTheme( 1809): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4165 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/WeatherQuickCover( 1809): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1809): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1809): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1809): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  963): Killing 3902:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4165): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4165): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
,I/Icing   ( 1873): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1873): CP2 sync disabled
I/ActivityManager(  963): Delaying start of: ServiceRecord{4315f480 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1} time:48520
,E/SQLiteDatabase( 1873): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
,W/dalvikvm( 1873): threadid=25: thread exiting with uncaught exception (group=0x4180be48)
E/AndroidRuntime( 1873): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 1873): Process: com.google.android.gms, PID: 1873
E/AndroidRuntime( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 1873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/AndroidRuntime( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/AndroidRuntime( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/AndroidRuntime( 1873): 	at com.google.android.gms.drive.database.o.run(SourceFile:726)
,E/SQLiteDatabase( 4165): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4165): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4165): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4165): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4165): 	at dalvik.system.NativeStart.main(Native Method)
E/LGMediaProvider( 4165): failed to open database external.db
E/LGMediaProvider( 4165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGMediaProvider( 4165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/LGMediaProvider( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/LGMediaProvider( 4165): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:458)
E/LGMediaProvider( 4165): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6662)
E/LGMediaProvider( 4165): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/LGMediaProvider( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/LGMediaProvider( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/LGMediaProvider( 4165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LGMediaProvider( 4165): 	at android.os.Looper.loop(Looper.java:136)
E/LGMediaProvider( 4165): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/LGMediaProvider( 4165): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LGMediaProvider( 4165): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LGMediaProvider( 4165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/LGMediaProvider( 4165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/LGMediaProvider( 4165): 	at dalvik.system.NativeStart.main(Native Method)
E/DropBoxManagerService(  963): Can't write: system_app_crash
E/DropBoxManagerService(  963): java.io.FileNotFoundException: /data/system/dropbox/drop92.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4165): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteDatabase( 4165): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteDatabase( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 4165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4165): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4165): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 4165): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4165): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 4165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 4165): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4165): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 4165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4165): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
E/SQLiteOpenHelper( 4165): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
E/SQLiteOpenHelper( 4165): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
E/SQLiteOpenHelper( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 4165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4165): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4165): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 4165): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4165): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 4165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 4165): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4165): (14) cannot open file at line 29423 of [f5b5a13f73]
E/SQLiteLog( 4165): (14) os_unix.c:29423: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4165): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
W/System.err( 4165): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4877)
W/System.err( 4165): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4461)
W/System.err( 4165): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4398)
W/System.err( 4165): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
W/System.err( 4165): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
W/System.err( 4165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4165): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 4165): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 4165): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4165): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4165): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 4165): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 4165): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 4165): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4165): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4165): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:601)
W/System.err( 4165): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:790)
W/System.err( 4165): 	at ,android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4165): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4165): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4165): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:963)
W/System.err( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4165): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4165): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2712)
W/System.err( 4165): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:6671)
W/System.err( 4165): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:691)
W/System.err( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
W/System.err( 4165): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
W/System.err( 4165): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4874)
W/System.err( 4165): 	... 12 more
I/Process ( 4165): Sending signal. PID: 4165 SIG: 9
I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42848f58 time:48569
,I/ActivityManager(  963): Process android.process.media (pid 4165) has died.
I/ActivityManager(  963): Start proc android.process.media for restart android.process.media: pid=4182 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ace948 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/HyLog   ( 4182): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4182): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4182): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=34 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=64
E/qdoverlay(  267): data msmfb_data offset=0 memid=73 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  267): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,W/DriveInitializer( 1873): Awaiting to be initialized
,W/DriveInitializer( 1873): Background init thread started
,E/SQLiteDatabase( 1873): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,E/DocListDatabase( 1873): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/DocListDatabase( 1873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/DocListDatabase( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DocListDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 1873): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,E/SQLiteDatabase( 1873): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 1873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/SQLiteDatabase( 1873): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1873): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1873): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1873): 	at java.lang.Thread.run(Thread.java:841)
W/DriveInitializer( 1873): Background init thread ended
E/DriveAsyncService( 1873): not an error (code 0): Could not open the database in read/write mode.
E/DriveAsyncService( 1873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/DriveAsyncService( 1873): 	at android.app.ContextImpl.openOrCr,eateDatabase(ContextImpl.java:1033)
E/DriveAsyncService( 1873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DriveAsyncService( 1873): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:226)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.m.b(SourceFile:711)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.m.a(SourceFile:705)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.k.a(SourceFile:242)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1873): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1873): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1873): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1873): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1873): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 1873): threadid=38: thread exiting with uncaught exception (group=0x4180be48)
,I/Process ( 1873): Sending signal. PID: 1873 SIG: 9
,I/ActivityManager(  963): Process com.google.android.gms (pid 1873) has died.
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
,I/ConfigService( 1538): onDestroy
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10998ms
W/ActivityManager(  963): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba06c0 stackId=0, 1 tasks}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/qdoverlay(  267): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  267): Ctrl failed to init fbnum=0
E/qdoverlay(  267): Ctrl failed to init dpy=0
E/qdoverlay(  267): GenericPipe failed to init ctrl
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  267): == Bad OVInfo is:  mdp_overlay z=1 fg=0 alpha=77 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=384 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=960 h=377
E/qdoverlay(  267): dst_rect mdp_rect x=92 y=750 w=896 h=351
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
E/qdoverlay(  267): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  267): src msmfb_img w=1152 h=160 format=13 MDP_RGBA_8888
E/qdoverlay(  267): src_rect mdp_rect x=0 y=0 w=1080 h=144
E/qdoverlay(  267): dst_rect mdp_rect x=0 y=1776 w=1080 h=144
E/qdoverlay(  267): Ctrl commit failed set overlay
E/qdhwcomposer(  267): configure: configMdp failed for dpy 0
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl close error in unset
E/qdoverlay(  267): GenericPipe failed to close ctrl
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl close error in unset
E,/qdoverlay(  267): GenericPipe failed to close ctrl
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  267): MdpCtrl close error in unset

```
