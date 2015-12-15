#### Test 50388019385b4d9_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/Mms/MmsApp( 5293): [start]    onCreate() consume time = 0.0
D/Mms/TelephonyPermission( 5293): start operation mode monitor
D/ResourcesManager( 5293): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager( 5293): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 5293): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5293): isDefault true
D/Mms/MmsApp( 5293): onCreate() com.android.mms
W/System.err( 5276): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
W/System.err( 5276): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 5276): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 5276): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 5276): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 5276): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 5276): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 5276): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 5276): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 5276): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 5276): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 5276): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 5276): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 5276): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 5276): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5276): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5276): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5276): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5276): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5276): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5276): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/Mms/MmsConfig( 5293): [start]    MmsConfig.init() consume time = 50.18125
W/System.err( 5276): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/Mms/MmsConfig( 5293): before partial update
I/SL_DEBUG( 5276): isLoggable:: isProductShip = 1
E/ActivityThread( 5293): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
I/SL_DEBUG( 5276): isLoggable:: SL_DEBUG_EXIST = false
D/Mms/MmsConfig( 5293): Load Resize quality : 80
D/EasySignUpManager( 5293): serviceId : 1, features : -1
D/Mms/MmsConfig( 5293): setFreeMessageEnabled, free message policy(getSupportedFeatures) is = -1
I/SLinkClient( 5233): queryDevices : cursor.getCount() = [ 0 ]
D/TP/MmsSmsProvider( 1475): query,matched:2117, calling pid = 5293
D/SLinkClient( 5233): onStorageUpdated(), uri = [ slink://slink ]
D/TP/MmsSmsProvider( 1475): match 2117:Elapsed time : 1.105 ms
,E/ActivityThread( 5293): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 5293): serviceId : 3, features : -1
D/Mms/MmsConfig( 5293): Shop agent feature value :-1
D/Mms/MmsConfig( 5293):  enable multiwindow = true
E/Mms/MessageUtils( 5293): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5293): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5293): [end]    init() consume time = 58.3175
D/Mms/MmsApp( 5293): [start]    initCountryIso consume time = 0.138073
D/CountryDetector(  807): The first listener is added
I/SLinkClient( 5233): SlinkBackgroundJob: slink wake up ok!
D/Mms/MmsApp( 5293): [end]    initCountryIso consume time = 5.903177
D/Mms/Contact( 5293): [start]    init() consume time = 0.546406
D/TP/MmsSmsProvider( 1475): query,matched:13, calling pid = 5293
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_list_thumbnail.pkm
D/TP/MmsSmsProvider( 1475): match 13:Elapsed time : 0.823 ms
D/Mms/Contact( 5293): [end]    init consume time = 10.612031
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5276): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/Mms/DraftCache( 5293): [start]    rebuildCache consume time = 3.347605
D/TP/MmsSmsProvider( 1475): query,matched:12, calling pid = 5293
D/Mms/Conversation( 5293): [start]    init() consume time = 2.733541
D/TP/MmsSmsProvider( 1475): match 12:Elapsed time : 1.106 ms
D/TP/MmsSmsProvider( 1475): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1475): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/Mms/DraftCache( 5293): [end]    rebuildCache consume time = 4.068125
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1475): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1475): need read changed broadcast:false
D/Mms/Conversation( 5293): [end]    init consume time = 9.236927
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5276): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/Mms/TelephonyUtils( 5293): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager( 5293): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5293): auto download without roaming -> true
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/Mms/TelephonyUtils( 5293): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5293): getSubId from simSlot 1, return Value = -1000
D/Mms/DownloadManager( 5293): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5293): auto download without roaming -> true
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5293): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5293): mAutoDownload ------> true
D/Mms/MessagingNotification( 5293): [start]    init() consume time = 12.617656
D/Mms/MessagingNotification( 5293): [end]    init consume time = 2.537761
V/Transcoder( 5276): Transcoder(0xaf407830)::constructor
V/Transcoder( 5276): addObitRecipient
V/TMI-JNI ( 5276): Mobile Transcoder JNI version 1.6.0/20131120/4.4
D/Mms/SpamFilter( 5293): [start]    SpamFilter fill() begin consume time = 9.019636
D/TP/MmsSmsProvider( 1475): query,matched:400, calling pid = 5293
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/Mms/SpamFilter( 5293): [end]    SpamFilter fill() finished consume time = 4.704218
D/Mms/ComposeMessageFragment( 5293): [start]    fillCache consume time = 6.275209
D/Mms/ComposeMessageFragment( 5293): fillCache, easy = false
D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_add.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template_left.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_recieved_check_msg.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_read_check_msg.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
D/AbsListView( 5293): Get MotionRecognitionManager
D/MotionRecognitionService(  807):  ssp status : true
D/Mms/ComposeMessageFragment( 5293): [end]    fillCache consume time = 114.816979
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_contact_picture.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/sms_msg_bt.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw_2.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_bubble_icon_locked.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate1.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate2.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate3.png
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_translator_normal.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_press.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_focus.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_disable.pkm
V/BitmapFactory( 5293): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_normal.pkm
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 5334): 
D/AndroidRuntime( 5334): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5334): CheckJNI is OFF
D/AndroidRuntime( 5334): setted country_code = Germany
D/AndroidRuntime( 5334): setted countryiso_code = DE
D/AndroidRuntime( 5334): setted sales_code = DBT
D/AndroidRuntime( 5334): readGMSProperty: start
D/AndroidRuntime( 5334): readGMSProperty: already setted!!
D/AndroidRuntime( 5334): readGMSProperty: end
D/AndroidRuntime( 5334): addProductProperty: start
D/Mms/BubbleViewCache( 5293): fillCache bubble = 8
D/Mms/Synchronizer( 5293): [start]    doSync consume time = 226.985521
D/TP/MmsSmsProvider( 1475): query,matched:0, calling pid = 5293
V/TP/MmsSmsProvider( 1475): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1475): match 0:Elapsed time : 1.111 ms
D/TP/MmsSmsProvider( 1475): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1475): syncDBData start
V/TP/MmsSmsProvider( 1475): syncDBData sms end
V/TP/MmsSmsProvider( 1475): syncDBData mms end
V/TP/MmsSmsProvider( 1475): syncDBData end
D/Mms/Synchronizer( 5293): [end]    doSync consume time = 6.499687
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
E/AffinityControl( 5334): AffinityControl: registerfunction enter
D/Mms/MessagingNotification( 5293): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1475): query,matched:26, calling pid = 5293
D/TP/SmsProvider( 1475): match 26:Elapsed time : 0.909 ms
D/TP/MmsSmsProvider( 1475): query,matched:6, calling pid = 5293
D/TP/MmsSmsProvider( 1475): match 6:Elapsed time : 1.005 ms
D/AndroidRuntime( 5334): Calling main entry com.android.commands.am.Am
I/Mms/ReservationManager( 5293): ReservationManager()
I/Mms/ReservationManager( 5293): resetAfterConnected()
D/TP/MmsSmsProvider( 1475): query,matched:7, calling pid = 5293
D/TP/MmsSmsProvider( 1475): match 7:Elapsed time : 1.665 ms
I/Mms/ReservationManager( 5293): getReservedSendMessageCount(): retMessageCount=0
E/PersonaManagerService(  807): inState():  stateMachine is null !!
V/ApplicationPolicy(  807): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  807): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  807): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  807): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 807  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  807): mDVFSHelper.acquire()
D/FocusedStackFrame(  807): Set to : 0
D/Launcher.HomeView( 1481): onPause
D/AndroidRuntime( 5334): Shutting down VM
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Zygote  ( 5352): MountEmulatedStorage()
E/Zygote  ( 5352): v2
I/libpersona( 5352): KNOX_SDCARD checking this for 10025
I/libpersona( 5352): KNOX_SDCARD not a persona
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
I/ActivityManager(  807): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5352 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SELinux ( 5352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5352): TimaSignature is unavailable
D/ActivityThread( 5352): Added TimaKeyStore provider
E/Zygote  ( 5367): MountEmulatedStorage()
E/Zygote  ( 5367): v2
I/libpersona( 5367): KNOX_SDCARD checking this for 10375
I/libpersona( 5367): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  807): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5367 uid=10375 gids={50375, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5367): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3474): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 11 sec
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/LockPatternUtilsCache( 1168): value : false
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/Launcher.HomeView( 1481): onStop
D/TimaKeyStoreProvider( 5367): TimaSignature is unavailable
D/ResourcesManager( 5352): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
D/ActivityThread( 5367): Added TimaKeyStore provider
I/MicrophoneInputStream( 1562): mic_close gfk@3cc8d465
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  807): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
W/ResourcesManager( 5352): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  807): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget pause on instance = 1
V/AudioPolicyManager(  289): stopInput() input 26
V/AudioPolicyManager(  289): releaseInput() 26
V/AudioPolicyManager(  289): closeInput(26)
D/accuweather( 2140): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2140): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2140): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/HotwordRecognitionRnr( 1562): Hotword detection finished
V/audio_hw_primary(  289): in_standby: enter
D/Launcher( 1481): onTrimMemory. Level: 20
I/HotwordRecognitionRnr( 1562): Stopping hotword detection.
D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2140): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2140): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/SurfaceWidgetView( 1481): destroyHardwareResources():760730616
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 5367): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/audio_hw_primary(  289): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  289): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  289): disable_audio_route: reset mixer path: audio-record
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): disable_audio_route: exit
V/audio_hw_primary(  289): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  289): ++++ audio_route_update_mixer ==============
D/audio_route(  289): Setting mixer control: DEC2 Volume
D/audio_route(  289): Setting mixer control: value: 0
D/audio_route(  289): Setting mixer control: SLIM TX7 MUX, value: 0
D/SurfaceWidgetView( 1481): destroyHardwareResources():760730616
D/audio_route(  289): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  289): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/audio_route(  289): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  289): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  289): stop_input_stream: exit: status(0)
V/audio_hw_primary(  289): in_standby: exit:  status(0)
V/audio_hw_primary(  289): adev_close_input_stream
V/audio_hw_primary(  289): in_standby: enter
V/audio_hw_primary(  289): in_standby: exit:  status(0)
E/audio_hw_primary(  289): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  289): releaseInput() exit
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Mms/Omacp( 5293): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Mms/MmsApp( 5293): [end]    onCreate() consume time = 311.901771
D/Mms/PerformanceUtils( 5293): link cahcing start
D/Mms/DownloadManager( 5293): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager( 5293): roaming ------> false, mSimSlot = 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  807): Killing 4231:com.google.android.talk/u0a117 (adj 15): bgCount ##41
D/Mms/TelephonyUtils( 5293): getSubId from simSlot 0, return Value = -1
I/ActivityManager(  807): Killing 4033:com.google.android.gm/u0a114 (adj 15): bgCount ##42
D/Mms/DownloadManager( 5293): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5293): auto download without roaming -> true
D/Mms/DownloadManager( 5293): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5293): mAutoDownload ------> true
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Zygote  ( 5385): MountEmulatedStorage()
E/Zygote  ( 5385): v2
I/libpersona( 5385): KNOX_SDCARD checking this for 1000
I/libpersona( 5385): KNOX_SDCARD not a persona
I/ActivityManager(  807): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5385 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  314): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 290us total 15.250ms
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/Mms/PerformanceUtils( 5293): link cahcing done
E/SMD     (  282): DCD ON
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 7.974ms
W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.540ms
I/SELinux ( 5385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SELinux ( 5385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5385): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WebViewFactory( 5367): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5367): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PackageManager(  807): [MSG] SEND_PENDING_BROADCAST
I/LibraryLoader( 5367): Loading: webviewchromium
I/LibraryLoader( 5367): Time to load native libraries: 2 ms (timestamps 663-665)
D/ResourcesManager(  807): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/LibraryLoader( 5367): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/TimaKeyStoreProvider( 5385): TimaSignature is unavailable
D/ActivityThread( 5385): Added TimaKeyStore provider
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/InputReader(  807): Reconfiguring input devices.  changes=0x00000010
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/InputReader(  807): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 1481): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1168): value : false
W/libprocessgroup(  807): failed to open /acct/uid_10114/pid_4033/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/BitmapFactory( 1481): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/libprocessgroup(  807): failed to open /acct/uid_10117/pid_4231/cgroup.procs: No such file or directory
V/WebViewChromiumFactoryProvider( 5367): Binding Chromium to main looper Looper (main, tid 1) {13497dc}
I/LibraryLoader( 5367): Expected native library version number "",actual native library version number ""
I/chromium( 5367): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/RegisteredServicesCache( 1469): empty dynamic service
I/BrowserStartupController( 5367): Initializing chromium process, renderers=0
W/art     ( 5367): Attempt to remove local handle scope entry from IRT, ignoring
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 5385): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/chromium( 5367): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/chromium( 5367): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/chromium( 5367): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5367): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/RegisteredServicesCache( 1469): empty dynamic service
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/BluetoothAdapter( 5367): 433184997: getState() :  mService = null. Returning STATE_OFF
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Books/Books.apk
I/Adreno-EGL( 5367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5367): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5367): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5367): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5367): Remote Branch: 
I/Adreno-EGL( 5367): Local Patches: 
I/Adreno-EGL( 5367): Reconstruct Branch: 
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/PopupuiReceiver( 5385): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/BackupManagerService(  807): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/art     (  807): Explicit concurrent mark sweep GC freed 30556(1899KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.815ms total 133.227ms
D/SecContentProvider2(  807): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  807): mCursor = null
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/SecContentProvider2(  807): uri = -1 selection = getSealedState
D/SecContentProvider2(  807): mCursor = null
I/PopupuiReceiver_KNOX( 5385): getSealedState : true
D/SecContentProvider2(  807): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  807): mCursor = null
D/SecContentProvider2(  807): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/PopupuiReceiver_KNOX( 5385): getSealedHideNotificationMessages : 1
D/LockPatternUtilsCache( 1168): value : false
D/SecContentProvider2(  807): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2(  807): mCursor = null
D/SecContentProvider2(  807): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 5385): getCheckCoverPopupState : true
W/ContextImpl( 5385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:407 android.app.ActivityThread.handleReceiver:2945 
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/PopupuiReceiver( 5385): Action cable connected ! on - 
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/Zygote  ( 5419): MountEmulatedStorage()
E/Zygote  ( 5419): v2
I/libpersona( 5419): KNOX_SDCARD checking this for 10172
I/libpersona( 5419): KNOX_SDCARD not a persona
I/ActivityManager(  807): Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=5419 uid=10172 gids={50172, 9997, 3001, 3002} abi=armeabi-v7a
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/SELinux ( 5419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/chromium( 5367): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SELinux ( 5419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PopupuiReceiver( 5385): PopupuiService.java: dismissUSBCDetacheddDialog() unReigister
W/ContextImpl( 5385): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 com.sec.android.app.popupuireceiver.PopupuiService.dismissUSBCDetacheddDialog:130 com.sec.android.app.popupuireceiver.PopupuiService.onStartCommand:103 
W/chromium( 5367): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ContextImpl( 5385): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 android.app.ActivityThread.handleStopService:3289 android.app.ActivityThread.access$2300:172 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/art     ( 5367): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/AwContents( 5367): onDetachedFromWindow called when already detached. Ignoring
D/PowerManagerService(  807): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
I/ActivityManager(  807): Killing 4194:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/PowerManagerService(  807): [s] DisplayPowerCallbacks : onStateChanged()
D/TimaKeyStoreProvider( 5419): TimaSignature is unavailable
D/ActivityThread( 5419): Added TimaKeyStore provider
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
D/lights  (  807): lcd : 1 +
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SystemWebViewEngine( 5367): CordovaWebView is running on device made by: samsung
D/lights  (  807): lcd : 1 -
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
W/art     ( 5367): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5367): Attempt to remove local handle scope entry from IRT, ignoring
D/ResourcesManager( 5419): creating new AssetManager and set to /system/app/SmartcardManager/SmartcardManager.apk
W/ResourcesManager( 5419): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SecContentProvider2(  807): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  807): mCursor = null
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  807): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  807): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  807): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Activity( 5367): performCreate Call secproduct feature valuefalse
D/Activity( 5367): performCreate Call debug elastic valuetrue
I/BackupManagerService(  807): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/BackupManagerService(  807): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  807): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@12ba0eb1
D/OpenGLRenderer( 5367): Render dirty regions requested: true
E/SmartCardContentProvider( 5419): onCreate
W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_4194/cgroup.procs: No such file or directory
D/ActivityManager(  807): post active user change for 0
D/KnoxTimeoutHandler(  807): postActiveUserChange for user 0
I/SmartCardBroadcastReceiver( 5419): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 5419): Broadcast received for locktype changed 
D/KnoxTimeoutHandler(  807): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  807): Killing 4248:com.sec.chaton/u0a86 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/CscFactoryReceiver( 1475): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1475): Media DB Scanner finished.
D/CscFactoryReceiver( 1475): start service to Set Ringtone
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/ActivityManager(  807): Waited long enough for: ServiceRecord{359431a7 u0 com.sec.android.service.sm/.service.SecurityManagerService}
I/SurfaceFlinger(  249): id=13 createSurf (1080x1920),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/CscFactoryReceiver( 1475): start service to Set Notification
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/CscFactoryReceiver( 1475): start service to Set Alarmtone
D/CscUpdateService( 1475): onStart
E/CscUpdateService( 1475): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1475): only ringtone update
D/CscUpdateService( 1475): onStart
E/CscUpdateService( 1475): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1475): only notification update
E/CscParser( 1475): update(): xml file exist
D/CscUpdateService( 1475): onStart
E/CscUpdateService( 1475): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1475): only alarmtone update
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/OpenGLRenderer( 5367): Initialized EGL, version 1.4
I/OpenGLRenderer( 5367): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 5367): Enabling debug mode 0
E/CscParser( 1475): update(): xml file exist
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/CscParser( 1475): update(): xml file exist
E/Zygote  ( 5452): MountEmulatedStorage()
E/Zygote  ( 5452): v2
I/libpersona( 5452): KNOX_SDCARD checking this for 10007
I/libpersona( 5452): KNOX_SDCARD not a persona
W/CSCSettings( 1475): Setting Ringtones (type) : 1
D/CscParser( 1475): RingTone: null
W/CSCSettings( 1475): 1. Tag_Str: null
I/ActivityManager(  807): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5452 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
W/CSCSettings( 1475): Setting Ringtones (type) : 4
D/CscParser( 1475): AlarmTone: null
W/CSCSettings( 1475): 1. Tag_Str: null
I/SystemBroadcastReceiver( 5160): [#DCM#] Calling notifyListeners. 
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
W/CSCSettings( 1475): Setting Ringtones (type) : 2
D/CscParser( 1475): MessageTone: null
W/CSCSettings( 1475): 1. Tag_Str: null
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  807): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  807): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/ActivityManager(  807): Waited long enough for: ServiceRecord{2d30e9fd u0 com.samsung.android.providers.context/.ContextService}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/SELinux ( 5452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/StorageController( 5160): [#DCM#]  state through storage volume =  mounted
I/StorageController( 5160): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
I/StorageController( 5160): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 5160): [#DCM#]  state through storage volume =  unmounted
I/StorageController( 5160): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
I/StorageController( 5160): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
,I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
,I/StorageController( 5160): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
,I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
I/StorageController( 5160): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
,I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/StorageController( 5160): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/TimaKeyStoreProvider( 5452): TimaSignature is unavailable
,I/StorageController( 5160): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 5160): [#DCM#]  state through storage volume =  removed
D/ActivityThread( 5452): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  807): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/StorageController( 5160): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 5160): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController( 5160): [#DCM#] getSDCardSubSystemEntry Rebooted ?
I/StorageController( 5160): [#DCM#] Sending intent for OS Upgrade for Phone contents 
I/DCMUtilities( 5160): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SystemUtils( 5160): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SystemUtils( 5160): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities( 5160): [#DCM#] OSUpgrade not required 
W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
,D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/ActivityManager(  807): Displayed com.example.hello/.MainActivity: +962ms
,D/CustomFrequencyManagerService(  807): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 807  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  807): mDVFSHelper.release()
I/Timeline(  807): Timeline: Activity_windows_visible id: ActivityRecord{228eebe8 u0 com.example.hello/.MainActivity t11} time:41333
D/CustomFrequencyManagerService(  807): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 807  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Timeline( 5367): Timeline: Activity_idle id: android.os.BinderProxy@1c3bb00c time:41338
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/libprocessgroup(  807): failed to open /acct/uid_10086/pid_4248/cgroup.procs: No such file or directory
,D/ResourcesManager( 5452): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Adreno-ES20( 5367): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5367): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/AndroidProtocolHandler( 5367): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 5367): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/DBG_DM  ( 3474): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 12 sec
,V/GmsNetworkLocationProvi( 1552): DISABLE
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GCoreNlp( 1552): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ThumbnailProvider( 5452): ThumbnailProvider onCreate()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/JsMessageQueue( 5367): Set native->JS mode to OnlineEventsBridgeMode
,D/LocationProviderProxy(  807): applying state to connected service
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LocationProviderProxy(  807): applying state to connected service
I/DocumentBroadcastReceiver( 5452): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/BroadcastProcessorService( 5452): [START] processBroadcastIntent ...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/GalleryCacheReady( 5233): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5233): handleMeidaScanFinish()
,D/FaceInterface( 5233): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5233): query fail: 
,W/LocalSuggestAlbumData( 5233): query fail: 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/BroadcastProcessorService( 5452): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/FaceInterface( 5233): startFaceScan() : waiting 5 sec
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
,I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SystemInfo( 5452): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5452): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5452): [START] DocumentService startDocumentService
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/DocumentService( 5452): DocumentService onCreate ... service
,D/GalleryCacheReady( 5233): Receive : home resume
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5452): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/Mms/UIEventReceiver( 5293): ui event
,W/ContextImpl( 5452): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,W/BroadcastQueue(  807): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5481): MountEmulatedStorage()
I/libpersona( 5481): KNOX_SDCARD checking this for 10094
E/Zygote  ( 5481): v2
I/libpersona( 5481): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5481 uid=10094 gids={50094, 9997} abi=armeabi-v7a
,E/SystemInfo( 5452): [SIOP LEVEL] : 0
,I/SELinux ( 5481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/chromium( 5367): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5367): 
,I/SELinux ( 5481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5481): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService(  807): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 807  tag : ACTIVITY_RESUME_BOOSTER@10
,I/DocumentService( 5452): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/TimaKeyStoreProvider( 5481): TimaSignature is unavailable
,D/ActivityThread( 5481): Added TimaKeyStore provider
,W/ContextImpl( 5452): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/jxcore_app_log( 5367): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360643456
,D/JX-Cordova( 5367): jxcore cordova android initializing
,I/ActivityManager(  807): Waited long enough for: ServiceRecord{1cdffbec u0 com.android.settings/.wifi.WifiCredService}
,D/ResourcesManager( 5481): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
,W/ResourcesManager( 5481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/File    ( 5452): fail readDirectory() errno=13
E/File    ( 5452): fail readDirectory() errno=13
,I/SystemInfo( 5452): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5452): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5452): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :99
,E/DocumentService( 5452): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5452): [INDEX] Total time taken for each file :0
,I/DocumentService( 5452): DocumentService onDestroy start
,I/DocumentService( 5452): DocumentService onDestroy end
,I/DocumentService( 5452): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5452): InterruptedException: null
,I/SystemInfo( 5452): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5452): DocumentService cleanupEverything end
I/Process ( 5452): Sending signal. PID: 5452 SIG: 9
,D/ResourcesManager( 4301): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,V/AlarmManager(  807): waitForAlarm result :4
,E/Zygote  ( 5502): MountEmulatedStorage()
E/Zygote  ( 5502): v2
I/libpersona( 5502): KNOX_SDCARD checking this for 10103
I/libpersona( 5502): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5502 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,E/lowmemorykiller(  246): Error writing /proc/5452/oom_score_adj; errno=22
,I/ActivityManager(  807): Killing 2504:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/ActivityManager(  807): Process com.samsung.indexservice (pid 5452)(adj 13) has died(56,635)
,W/jxcore-log( 5367): Initializing JXcore engine
W/jxcore-log( 5367): JXcore engine is ready
,W/jxcore-log( 5367): Starting JXcore engine
,I/SELinux ( 5502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5502): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5502): TimaSignature is unavailable
,D/ActivityThread( 5502): Added TimaKeyStore provider
,D/BatteryService(  807): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  807): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  807): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  807):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  807): Plugged
,I/MotionRecognitionService(  807): setPowerConnected  = true
,E/auditd  ( 2169): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  807): Got Modify Event and sending Denial Intent foraudit.log
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ResourcesManager( 5502): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,W/ResourcesManager( 5502): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5502): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/SecurityLogAgent:SEDenialService(  807): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  807): failed to open /acct/uid_10099/pid_2504/cgroup.procs: No such file or directory
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5518): MountEmulatedStorage()
E/Zygote  ( 5518): v2
I/libpersona( 5518): KNOX_SDCARD checking this for 10113
I/libpersona( 5518): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=5518 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/jxcore-log( 5367): Platform android
W/jxcore-log( 5367): 
W/jxcore-log( 5367): Process ARCH arm
W/jxcore-log( 5367): 
,I/SELinux ( 5518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5518): TimaSignature is unavailable
,D/ActivityThread( 5518): Added TimaKeyStore provider
,D/ResourcesManager( 5518): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
,I/MediaStoreImporter( 5122): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  807): Killing 4214:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/jxcore-log( 5367): JXcore Cordova bridge is ready!
I/jxcore-log( 5367): 
,W/jxcore-log( 5367): JXcore engine is started
,I/ActivityManager(  807): Waited long enough for: ServiceRecord{39685916 u0 com.android.settings/.wifi.hs20.Hs20UtilityService}
,E/jxcore-log( 5367): >> samsung-SM-G900F
E/jxcore-log( 5367): 
,I/jxcore-log( 5367): Total memory 1787449344
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): Free memory 73740288
I/jxcore-log( 5367): 
I/jxcore-log( 5367): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5367): 
I/jxcore-log( 5367): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): Size 1080 1920
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): Screen Brightness 134
I/jxcore-log( 5367): 
,E/jxcore-log( 5367): Dummy Error Log.
E/jxcore-log( 5367): 
,W/GeoLookout( 5518): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,I/GeoLookout( 5518): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,W/libprocessgroup(  807): failed to open /acct/uid_10033/pid_4214/cgroup.procs: No such file or directory
,D/SettingsProvider(  807): name = safetycare_geolookout_registering
D/SettingsProvider(  807): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  807): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  807): selectionArgs: false
D/SettingsProvider(  807): selectionArgs: 10113
D/SecContentProvider(  807): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  807): ret = -1
,D/GeoLookout( 5518): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,V/TaskCloserActivity( 5089): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/ActivityManager(  807): Killing 4319:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
,I/HomeSyncInstallReceiver( 1469): This pkg do not need BT addr. Do nothing
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5538): MountEmulatedStorage()
I/libpersona( 5538): KNOX_SDCARD checking this for 10015
E/Zygote  ( 5538): v2
I/libpersona( 5538): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5538 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  807): failed to open /acct/uid_10091/pid_4319/cgroup.procs: No such file or directory
,I/SELinux ( 5538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5538): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5538): TimaSignature is unavailable
,D/ActivityThread( 5538): Added TimaKeyStore provider
,D/ResourcesManager( 5538): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5556): MountEmulatedStorage()
I/libpersona( 5556): KNOX_SDCARD checking this for 10016
E/Zygote  ( 5556): v2
I/libpersona( 5556): KNOX_SDCARD not a persona
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/ActivityManager(  807): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5556 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5556): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  807): Killing 4342:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/ActivityManager(  807): Killing 4380:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5556): TimaSignature is unavailable
,D/ActivityThread( 5556): Added TimaKeyStore provider
,D/ResourcesManager( 5556): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
,W/ResourcesManager( 5556): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5556): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/GroupCast_FileTools( 5556): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 5556): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,W/System.err( 5556): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5556): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5556): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5556): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5556): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5556): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5556): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5556): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5556): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5556): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5556): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5556): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5556): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_4380/cgroup.procs: No such file or directory
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_4342/cgroup.procs: No such file or directory
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5571): MountEmulatedStorage()
E/Zygote  ( 5571): v2
I/libpersona( 5571): KNOX_SDCARD checking this for 1000
I/libpersona( 5571): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 4411:com.zalando.samsung.provider/u0a192 (adj 15): bgCount ##41
,I/SELinux ( 5571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  807): failed to open /acct/uid_10192/pid_4411/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5571): TimaSignature is unavailable
D/ActivityThread( 5571): Added TimaKeyStore provider
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
D/ResourcesManager( 5571): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/DBG_DM  ( 3474): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 13 sec
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/PCWCLIENTTRACE_LOG( 5571): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5571): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5571): new DMDBOpenHelper instance
I/DBG_DM  ( 3474): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3474): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
E/DBG_DM  ( 3474): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
,I/Process ( 3630): Sending signal. PID: 3630 SIG: 9
,I/DBG_DM  ( 3474): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
,I/PCWCLIENTTRACE_PushUtil( 5571): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5571): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5571): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5571): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5586): MountEmulatedStorage()
E/Zygote  ( 5586): v2
I/libpersona( 5586): KNOX_SDCARD checking this for 10034
I/libpersona( 5586): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5586 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 4427:com.LocalFota/u0a120 (adj 15): bgCount ##41
,I/SELinux ( 5586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  807): Process com.sec.android.app.sysscope (pid 3630)(adj 0) has died(75,645)
,I/SELinux ( 5586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  807): failed to open /acct/uid_10120/pid_4427/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5586): TimaSignature is unavailable
,D/ActivityThread( 5586): Added TimaKeyStore provider
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 5586): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5586): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
,D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
W/ResourcesManager( 5586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5586): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5586): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/jxcore-log( 5367): getBuffer is called!!!!
I/jxcore-log( 5367): 
,W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5586): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 5586): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SA      ( 4993): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4993): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 4993): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10375 extra.user_handle.:0 ]
,I/ActivityManager(  807): Killing 4471:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/Mms/FreeMessageReceiver( 5293): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5608): MountEmulatedStorage()
E/Zygote  ( 5608): v2
I/libpersona( 5608): KNOX_SDCARD checking this for 10051
I/libpersona( 5608): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5608 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/Mms/FreeMessageReceiverService( 5293): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5293): onHandleIntent: ACTION_PACKAGE_ADDED
,I/SELinux ( 5608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5608): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5608): TimaSignature is unavailable
,D/ActivityThread( 5608): Added TimaKeyStore provider
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_4471/cgroup.procs: No such file or directory
,D/ResourcesManager( 5608): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 5608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/MyFiles ( 5608): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/TactileAssist(  807): enable value -1
I/TactileAssist(  807): internal enable value -1
I/TactileAssist(  807): intensity value -1
I/TactileAssist(  807): saveAppList value true
,I/TactileAssist(  807): List of disabled apps :
I/TactileAssist(  807): de.zalando.mobile
,E/installd(  292): system dir 0 : /system/app/
E/installd(  292): system dir 1 : /system/priv-app/
E/installd(  292): system dir 2 : /vendor/app/
E/installd(  292): system dir 3 : /oem/app/
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/Zygote  ( 5635): MountEmulatedStorage()
E/Zygote  ( 5635): v2
,I/libpersona( 5635): KNOX_SDCARD checking this for 10058
I/libpersona( 5635): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5635 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 12.390ms
,I/SELinux ( 5635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5635): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 268us total 7.907ms
,D/PackageManager(  807): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 7.997ms
,D/TimaKeyStoreProvider( 5635): TimaSignature is unavailable
,D/ActivityThread( 5635): Added TimaKeyStore provider
,D/ResourcesManager( 5635): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 5635): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5635): onReceive() it will make start service
,D/Compatibility( 5635): onHandleIntent()
,D/Compatibility( 5635): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10375, android.intent.extra.user_handle=0}]
,D/Compatibility( 5635): found: 2
,D/Compatibility( 5635): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5635): skipping ResolveInfo{1b1620b0 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5635): considering ResolveInfo{3e81bb29 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5635): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5635): enabling receiver ResolveInfo{ef95eae com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5635): enabling receiver ResolveInfo{39a844f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5635): enabling receiver ResolveInfo{13497dc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5635): enabling receiver ResolveInfo{19d1e0e5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 1562): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5635): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 5655): MountEmulatedStorage()
E/Zygote  ( 5655): v2
I/libpersona( 5655): KNOX_SDCARD checking this for 1000
I/libpersona( 5655): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5655 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5655): TimaSignature is unavailable
,D/ActivityThread( 5655): Added TimaKeyStore provider
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5655): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/ResourcesManager( 1979): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ContextImpl( 5655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5673): MountEmulatedStorage()
,E/Zygote  ( 5673): v2
I/libpersona( 5673): KNOX_SDCARD checking this for 10086
I/libpersona( 5673): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5673 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  807): Killing 4497:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
E/SELinux ( 5673): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5673): TimaSignature is unavailable
D/ActivityThread( 5673): Added TimaKeyStore provider
,D/ResourcesManager( 5673): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  807): failed to open /acct/uid_10138/pid_4497/cgroup.procs: No such file or directory
,D/PushModule( 5673): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 5673): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 5673): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/ChatON  ( 5673): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 5673): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  807): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 5673): [1][a] ChatONV isn't installed.
,D/ChatON  ( 5673): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 1562): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/UpdateIcingCorporaServi( 1562): UpdateCorporaTask done [took 330 ms] updated apps [took 330 ms] 
,E/Zygote  ( 5694): MountEmulatedStorage()
E/Zygote  ( 5694): v2
I/libpersona( 5694): KNOX_SDCARD checking this for 10098
I/libpersona( 5694): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5694 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 4524:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
,I/SELinux ( 5694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5694): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  807): failed to open /acct/uid_10143/pid_4524/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5694): TimaSignature is unavailable
,D/ActivityThread( 5694): Added TimaKeyStore provider
,I/DBG_DM  ( 3474): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 14 sec
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3474): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3474): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager( 5694): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/DBG_DM  ( 3474): [llIlIIIIlllIlllllIll(232/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 3474): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
,E/Watchdog(  807): !@Sync 1
,D/SettingsProvider(  807): name = audio_safe_volume_state
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/DocsApplication( 5694): Installing DEX configuration.
,D/DexInstaller( 5694): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5694): Provided clientMode=RELEASE, packageInfo=PackageInfo{3b641bf3 com.google.android.apps.docs}
,D/TAG     ( 5694): onCreate()
,D/CrossAppStateProvider( 5694): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/SMD     (  282): DCD ON
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,W/GAV2    ( 5694): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5723): MountEmulatedStorage()
I/libpersona( 5723): KNOX_SDCARD checking this for 10099
E/Zygote  ( 5723): v2
I/libpersona( 5723): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5723 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/SELinux ( 5723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5723): TimaSignature is unavailable
,D/ActivityThread( 5723): Added TimaKeyStore provider
,D/ResourcesManager( 5723): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 5723): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/[CarMode]( 5723): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5723): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5723): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,I/FaceInterface( 5233): startFaceScan() : going on
,D/FaceInterface( 5233): startFaceScan() is called.
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  807): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5741 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/Zygote  ( 5741): MountEmulatedStorage()
E/Zygote  ( 5741): v2
I/libpersona( 5741): KNOX_SDCARD checking this for 10033
I/libpersona( 5741): KNOX_SDCARD not a persona
,I/SELinux ( 5741): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5741): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5741): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  807): Explicit concurrent mark sweep GC freed 48488(2MB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.184ms total 102.076ms
,D/TimaKeyStoreProvider( 5741): TimaSignature is unavailable
,D/ActivityThread( 5741): Added TimaKeyStore provider
,D/ContentApp( 1225): startScan() is called.
,D/FaceValue( 1225): mSleepTime: 800
D/FaceValue( 1225): mMaxThreadNum: 2
,D/ContentApp( 1225): startScan() is end.
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1225): isNeedToRestore : start
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
,D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5741): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 5741): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 5694): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  807): Killing 4566:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/System.out( 5741): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5741): Inside WakeupProvider
,E/DatabaseUtils( 5741): Writing exception to parcel
E/DatabaseUtils( 5741): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5741): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5741): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5741): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5741): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5741): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5741): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5741): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5723): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 5741): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,W/System.err( 5723): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5723): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5723): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5723): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5723): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5723): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5723): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5723): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5723): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5723): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5723): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5723): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5723): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5723): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5723): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5723): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5723): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5723): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5723): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/libprocessgroup(  807): failed to open /acct/uid_10012/pid_4566/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 5741): 710266197: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 5741): 710266197: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5741): 710266197: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5741): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,E/DatabaseUtils( 5741): Writing exception to parcel
E/DatabaseUtils( 5741): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5741): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5741): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5741): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5741): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5741): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5741): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5741): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5741): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 5723): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 5723): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5723): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5723): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5723): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5723): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5723): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5723): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 5723): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 5723): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 5723): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 5723): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5723): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5723): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5723): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5723): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5723): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5723): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5723): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 5723): [DLApplication]-Init Called!:false
,E/[CarMode]( 5723): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 5723): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5723): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5723): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5723): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5723): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5723): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5723): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5723): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5723): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5723): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5723): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5723): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5723): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5723): ### com.android.internal.os.ZygoteInit::main(1194)
,I/MessageDataHandler( 5723): initialize
,D/[CarModeFW]( 5723): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5723): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 5723): CDH-buildContactCacheWireFrame : cur len =0
,D/BluetoothAdapter( 5723): 443977683: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5723): 443977683: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5723): DrivingManager-initialize...
,D/[CarModeFW]( 5723): CDH-ContactDataHandler initiazlieCaches time : 14
D/[CarModeFW]( 5723): CDH-initiazlieCaches : end sync
,I/SensorService(  807): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  807): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  807): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 5741): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5741): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/MediaPlayer( 5723): Need to enable context aware info
V/MediaPlayer-JNI( 5723): native_setup
V/MediaPlayer( 5723): constructor
,V/MediaPlayer( 5723): setListener
E/MediaPlayer-JNI( 5723): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 5723): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5723): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5723): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1450189280154
,D/[CarMode]( 5723): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1450189280154
D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1450189280155
D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1450189280155
,D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1450189280155
D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1450189280155
,I/[CarMode]( 5723): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/TP/SmsProvider( 1475): query,matched:2, calling pid = 5723
,D/TP/SmsProvider( 1475): match 2:Elapsed time : 0.753 ms
,E/[CarMode]( 5723): [DLApplication]-Init End!:true
,D/[CarModeFW]( 5723): CDH-buildContactCacheWireFrame : cur len =0
D/TP/SmsProvider( 1475): query,matched:2, calling pid = 5723
,D/TP/SmsProvider( 1475): match 2:Elapsed time : 0.787 ms
D/[CarModeFW]( 5723): RecommendHandler-selection = type = '3'
,D/MessageDataHandler( 5723):  getInboxList smsCursor : 11
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5787): MountEmulatedStorage()
E/Zygote  ( 5787): v2
I/libpersona( 5787): KNOX_SDCARD checking this for 10003
I/libpersona( 5787): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5787 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5793): MountEmulatedStorage()
E/Zygote  ( 5793): v2
I/libpersona( 5793): KNOX_SDCARD checking this for 10020
I/libpersona( 5793): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5793 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 5787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SELinux ( 5793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/SELinux ( 5787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 5723): CDH-buildContactCacheWireFrame : cur len =0
,I/SELinux ( 5793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/[CarMode]( 5723): [DLApplication]-GooglePlayServices SUCCESS.
E/SELinux ( 5793): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1475): Query uri=content://mms/inbox, match=2, calling pid = 5723
,D/TP/MmsProvider( 1475): Query uri=content://mms, match=0, calling pid = 5723
,D/MessageDataHandler( 5723):  getInboxList mmsCursor : 88
,D/[CarModeFW]( 5723): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5723): RecommendHandler-selection = type = '3'
,E/[CarMode]( 5723): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/MessageDataHandler( 5723):  getInboxList mms,sms cursor join : 6
,I/UpdateManagerReceiver( 5723): Intent : android.intent.action.PACKAGE_ADDEDTue Dec 15 15:21:20 GMT+01:00 2015
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,I/MessageDataHandler( 5723): getUnreadMessageCount :0
D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 118
,E/Zygote  ( 5817): MountEmulatedStorage()
E/Zygote  ( 5817): v2
I/ActivityManager(  807): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5817 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 5817): KNOX_SDCARD checking this for 1000
I/libpersona( 5817): KNOX_SDCARD not a persona
,I/SELinux ( 5817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 5787): TimaSignature is unavailable
D/ActivityThread( 5787): Added TimaKeyStore provider
I/ActivityManager(  807): Killing 4444:com.android.vending/u0a30 (adj 15): bgCount ##41
,I/SELinux ( 5817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/TP/MmsSmsProvider( 1475): query,matched:0, calling pid = 5723
V/TP/MmsSmsProvider( 1475): getSimpleConversations entered.
D/TimaKeyStoreProvider( 5793): TimaSignature is unavailable
D/ActivityThread( 5793): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1475): match 0:Elapsed time : 2.163 ms
,E/SELinux ( 5817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1475): query,matched:13, calling pid = 5723
,D/TP/MmsSmsProvider( 1475): match 13:Elapsed time : 0.797 ms
,D/ResourcesManager( 5787): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 5, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5793): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarModeFW]( 5723): PushMessageService-onCreate
,I/ActivityManager(  807): Killing 4913:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,I/ActivityManager(  807): Killing 4897:com.sec.android.soagent/u0a37 (adj 15): bgCount ##42
,I/ActivityManager(  807): Killing 4551:com.sec.android.service.health/u0a17 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 5817): TimaSignature is unavailable
D/ActivityThread( 5817): Added TimaKeyStore provider
,D/MessageDataHandler( 5723):  getInboxList address cursor : 30
,D/TP/MmsSmsProvider( 1475): query,matched:0, calling pid = 5723
V/TP/MmsSmsProvider( 1475): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1475): match 0:Elapsed time : 0.802 ms
,D/[CarModeFW]( 5723): PushMessageManager-onServiceConnected
D/[CarModeFW]( 5723): PushMessageService-registerPushMessageServiceListener
,D/MessageDataHandler( 5723):  getInboxList thread cursor : 5
,D/MessageDataHandler( 5723):  thread, addr result: 1
,I/[CarModeFW]( 5723): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 187
I/[CarModeFW]( 5723): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
,D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 188
,D/ResourcesManager( 5817): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/UserAnalysis.PlaceProvider( 5787): PlaceProvider onCreate()
,W/ContextImpl( 5817): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5817): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,E/FilterInstaller( 5817): There is no requred permission
,E/Zygote  ( 5836): MountEmulatedStorage()
,E/Zygote  ( 5836): v2
I/libpersona( 5836): KNOX_SDCARD checking this for 10112
I/libpersona( 5836): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5836 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 5787): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5787): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5787): Create SecureDbHelper
,I/SELinux ( 5836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  807): Killing 4927:com.android.email/u0a163 (adj 15): bgCount ##41
E/SELinux ( 5836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 5787): onCreate()
,I/SQLiteSecureOpenHelper( 5787): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 5787): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5787): Open Place.db in secure mode
,D/TimaKeyStoreProvider( 5836): TimaSignature is unavailable
,D/ActivityThread( 5836): Added TimaKeyStore provider
,D/ResourcesManager( 5836): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 333
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/[CarModeFW]( 5723): -[snowdeer] Rec : Missed Call : 328
,I/SQLiteSecureOpenHelper( 5787): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 5787): ...getDatabaseLocked(b,b,pwd)
,I/[CarModeFW]( 5723): -[snowdeer] Rec : Favorite : 6
,D/[CarModeFW]( 5723): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 5723): MyPlaceProvider-=============
,D/[CarModeFW]( 5723): MyPlaceProvider-=============
D/[CarModeFW]( 5723): MyPlaceProvider-=============
,D/[CarModeFW]( 5723): MyPlaceProvider-=============
D/[CarModeFW]( 5723): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 5723): MyPlaceProvider-==============
D/[CarModeFW]( 5723): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5723): MyPlaceProvider-==============
D/[CarModeFW]( 5723): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 5723): MyPlaceProvider-==============
D/[CarModeFW]( 5723): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 5723): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 352
,I/[CarModeFW]( 5723): -[snowdeer] Rec : CallLog : 10
,D/[CarMode]( 5723): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@cab5f295, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6532f367] LOCATIONS
,D/PackageIntentReceiver( 5836): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5836): Not GearManger package! 
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5853): MountEmulatedStorage()
E/Zygote  ( 5853): v2
I/libpersona( 5853): KNOX_SDCARD checking this for 10118
I/libpersona( 5853): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=5853 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 4669:com.android.providers.calendar/u0a46 (adj 13): bgCount ##41
,W/BulkCursor( 5723): Remote process exception when closing
,I/SELinux ( 5853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  807): Killing 5723:com.sec.android.automotive.drivelink/u0a99 (adj 13): depends on provider com.android.providers.calendar/.CalendarProvider2 in dying proc com.android.providers.calendar
E/SELinux ( 5853): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5853): TimaSignature is unavailable
,D/ActivityThread( 5853): Added TimaKeyStore provider
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_4913/cgroup.procs: No such file or directory
,W/libprocessgroup(  807): failed to open /acct/uid_10017/pid_4551/cgroup.procs: No such file or directory
W/libprocessgroup(  807): failed to open /acct/uid_10037/pid_4897/cgroup.procs: No such file or directory
W/libprocessgroup(  807): failed to open /acct/uid_10030/pid_4444/cgroup.procs: No such file or directory
,D/ResourcesManager( 5853): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 5853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  807): failed to open /acct/uid_10163/pid_4927/cgroup.procs: No such file or directory
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/MagazineService Version( 5853): Magazine-Administrator: 11
,D/MagazineService Version( 5853): Magazine-Provider: 14
,D/MagazineService Version( 5853): Magazine-Channel: 14
,W/libprocessgroup(  807): failed to open /acct/uid_10046/pid_4669/cgroup.procs: No such file or directory
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5868): MountEmulatedStorage()
E/Zygote  ( 5868): v2
I/libpersona( 5868): KNOX_SDCARD checking this for 10118
I/libpersona( 5868): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=5868 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 5853): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5853): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/art     (  314): Explicit concurrent mark sweep GC freed 8763(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 10.518ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 298us total 7.900ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.473ms
,I/SELinux ( 5868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  807): failed to open /acct/uid_10099/pid_5723/cgroup.procs: No such file or directory
,I/SELinux ( 5868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5868): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 5853): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 5879): MountEmulatedStorage()
,E/Zygote  ( 5879): v2
I/libpersona( 5879): KNOX_SDCARD checking this for 1000
I/libpersona( 5879): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5879 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 5853): [onHandleIntent] Send broadcast to (com.example.hello).
,I/SELinux ( 5879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 5868): TimaSignature is unavailable
D/ActivityThread( 5868): Added TimaKeyStore provider
,I/SELinux ( 5879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 5868): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 5868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5879): TimaSignature is unavailable
,D/ActivityThread( 5879): Added TimaKeyStore provider
,D/ResourcesManager( 5879): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 5868): [onCreate]
,D/Headlines( 5868): Breath.onCreate
,D/HeadlinesCardManager( 5868): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5868): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 5868): CardProvider Library : 14
,W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/MagazineService::CardProviderContentProvider( 5853): insertProvider: provider already exists.: com.samsung.android.app.headlines
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/MagazineService::CardProviderContentProvider( 5853): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5868): registerCardProvider: provider already exists.
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5868): HeadlinesDataCenter ctor
D/Headlines( 5868): HeadlinesDataCenter. mLocale = en_US
,E/Zygote  ( 5900): MountEmulatedStorage()
E/Zygote  ( 5900): v2
I/libpersona( 5900): KNOX_SDCARD checking this for 1000
I/libpersona( 5900): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5900 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/HeadlinesChannelUtil( 5868): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 5868): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 5900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5900): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  807): Killing 5038:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5900): TimaSignature is unavailable
,D/ActivityThread( 5900): Added TimaKeyStore provider
,I/System.out( 5741): INFO:Resource not found:/Common.properties Using default values
,D/SSRM:m  (  807): SIOP:: AP = 470, PST = 430, CUR = 300
D/X       (  807): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1225):  LEVEL : 0
,I/SystemBroadcastReceiver( 5160): [#DCM#] [DCM_Performance] onReceive completed in time  173 microsec. 
,I/SystemBroadcastReceiver( 5160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5160): [#DCM#] onReceive action = EVENT_SIOP
,D/ResourcesManager( 5900): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  807): failed to open /acct/uid_10149/pid_5038/cgroup.procs: No such file or directory
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/AcmsPackageEventListener( 5900): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 5900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5928): MountEmulatedStorage()
E/Zygote  ( 5928): v2
I/libpersona( 5928): KNOX_SDCARD checking this for 10135
I/libpersona( 5928): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5928 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 4589:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/SELinux ( 5928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5928): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 5900): Enter Oncreate
D/AcmsServiceMonitor( 5900): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 5900): creating AcmsCore
D/AcmsCore( 5900): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5900): AcmsCore
,D/AcmsCore( 5900): init
,D/AcmsCore( 5900): Looper handler is not null
D/AcmsCore( 5900): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 5900): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5900): Incrementing - Counter value: 1
D/AcmsCore( 5900): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5900): onStartCommand
,D/AcmsService( 5900): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5900): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5900): Incrementing - Counter value: 2
D/AcmsService( 5900): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 5900): AcmsCertificateMngr
,D/AcmsRevocationMngr( 5900): AcmsRevocationMngr
,D/TimaKeyStoreProvider( 5928): TimaSignature is unavailable
D/ActivityThread( 5900): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ActivityThread( 5928): Added TimaKeyStore provider
,D/ResourcesManager( 5928): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/libprocessgroup(  807): failed to open /acct/uid_10150/pid_4589/cgroup.procs: No such file or directory
,W/ResourcesManager( 5928): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 5900): Inside handle Intent
,D/AcmsService( 5900): App added - package name: com.example.hello
D/AcmsCore( 5900): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5900): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5900): Incrementing - Counter value: 3
D/AcmsCore( 5900): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5900): Decremented Counter Value : handleStartIntent
,D/AcmsServiceMonitor( 5900): Decrementing - Counter value: 2
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
,D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/ActivityManager(  807): Waited long enough for: ServiceRecord{2e658c67 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,I/GLSActivity( 1662): [ac] getting account id
,E/Zygote  ( 5961): MountEmulatedStorage()
,E/Zygote  ( 5961): v2
I/libpersona( 5961): KNOX_SDCARD checking this for 10166
I/libpersona( 5961): KNOX_SDCARD not a persona
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/ActivityManager(  807): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=5961 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1662): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/TimaKeyStoreProvider( 5961): TimaSignature is unavailable
,D/ActivityThread( 5961): Added TimaKeyStore provider
,D/ResourcesManager( 5961): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 5961): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 5961): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5979): MountEmulatedStorage()
E/Zygote  ( 5979): v2
I/libpersona( 5979): KNOX_SDCARD checking this for 10170
I/libpersona( 5979): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5979 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 5979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5979): TimaSignature is unavailable
,D/ActivityThread( 5979): Added TimaKeyStore provider
,I/FaceInterface( 5233): startFaceScan() : going on
D/FaceInterface( 5233): startFaceScan() is called.
,D/ContentApp( 1225): startScan() is called.
,D/ContentApp( 1225): startScan() is end.
I/art     (  807): Explicit concurrent mark sweep GC freed 17476(1075KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.296ms total 99.056ms
,D/ContentApp( 1225): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1225): isNeedToRestore : start
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5979): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 5979): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5995): MountEmulatedStorage()
,E/Zygote  ( 5995): v2
I/libpersona( 5995): KNOX_SDCARD checking this for 10030
I/libpersona( 5995): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5995 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 5072:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,E/SMD     (  282): DCD ON
,I/SELinux ( 5995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5995): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5995): TimaSignature is unavailable
,D/ActivityThread( 5995): Added TimaKeyStore provider
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_5072/cgroup.procs: No such file or directory
,D/ResourcesManager( 5995): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,D/Finsky  ( 5995): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5995): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6031): MountEmulatedStorage()
E/Zygote  ( 6031): v2
I/libpersona( 6031): KNOX_SDCARD checking this for 10012
I/libpersona( 6031): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6031 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
,I/SELinux ( 6031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6031): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 5995): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5995): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6031): TimaSignature is unavailable
,D/ActivityThread( 6031): Added TimaKeyStore provider
,D/ResourcesManager( 6031): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6031): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6031): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  807): Killing 5105:com.sec.factory/1000 (adj 15): bgCount ##41
,D/Finsky  ( 5995): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5995): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5995): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 6031): VM with version 2.1.0 has multidex support
,I/MultiDex( 6031): install
I/MultiDex( 6031): VM has multidex support, MultiDex support library is disabled.
,D/BluetoothAdapter( 5367): disable()
,D/PowerManagerService(  807): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  807): Nap time (uid 1000)...
I/PowerManagerService(  807): !@[ps] Screen__Off(2) : 
D/PackageBroadcastService( 1979): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/PowerManagerService(  807): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  807): setDeviceInteractive: 0
D/Finsky  ( 5995): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/InputManager-JNI(  807): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/DisplayPowerController(  807): getFinalBrightness : 1 -> 1
D/InputManager-JNI(  807): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService(  807): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  807): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  807): SecHardwareInterface.setBatteryADC : false
E/BluetoothManagerService(  807): Bluetooth is already disabled. DO NOT disable again.
,D/InputManager-JNI(  807): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  807): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  807): 	.unregisterCallback : 1, client=
D/SContextService(  807): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@13f4374c, Service = Auto Rotation, used = 1
,D/PowerManagerService(  807): handleSandman : startDream()
,D/ChimeraCfgMgr( 1979): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/WifiService(  807): New client listening to asynchronous messages
,E/PowerManagerService(  807): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  807): Sleeping (uid 1000)...
,D/PowerManagerService(  807): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  807): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  807): [input device light] handleInputDeviceLightOff
,I/WifiManager( 5367): packageName : com.example.hello
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,W/libprocessgroup(  807): failed to open /acct/uid_1000/pid_5105/cgroup.procs: No such file or directory
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5518): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,V/JNIHelp ( 6031): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Adreno-EGL(  807): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  807): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  807): Build Date: 03/03/15 Tue
I/Adreno-EGL(  807): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  807): Remote Branch: 
I/Adreno-EGL(  807): Local Patches: 
I/Adreno-EGL(  807): Reconstruct Branch: 
,D/SecContentProvider(  807): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  807): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  807): mCursor = null
,I/ConfigFetchService( 1979): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/WifiService(  807): setWifiEnabled: false pid=5367, uid=10375
,E/WifiService(  807): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  807): name = wifi_on
,W/CAE     (  807): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,I/jxcore-log( 5367): ****TEST TOOK:  5090  ms ****
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5367): 
,I/ConfigFetchService( 1979): launchTask
V/CAE     (  807): stop(ContextProvider.java:149)
V/CAE     (  807): clear(AutoRotationRunner.java:182)
D/ChimeraCfgMgr( 1979): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ResourcesManager( 1979): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
V/CAE     (  807): disable(AutoRotationRunner.java:171)
I/CAE     (  807): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  807): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  296): sendContextData: -78, 7, 0, 0
,D/CAE     (  807): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  807): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/Vision  ( 1979): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,V/ConfigFetchTask( 1979): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X71eMVSEdY_-eGOmvNLvjJyq8W-UGUb2zqJB5sqeF_B3XHn8_EE_PMe0FHfcf4bm3LvZ3Rz1D512UPCxlC6dVkFvxmxyfinFShzU5qQsxUFJHCR76frCGKD80Td15gv3Qp9bztoppfZ65Cr0Xc7eVavZMm-o6XgOnt453xZaGQT__3igRkDOrVA5zQ_MxsP9rT-exQhLqPL8RwqNZwxq4Oj9vCzgo4fcbAolBp6cUEV4oS-Ew
,D/Vision  ( 1979): Failed to find package metadata for com.example.hello
,D/Vision  ( 1979): No vision deps
W/ActivityThread( 6031): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6031): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2714980f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6031): Installed default security provider GmsCore_OpenSSL
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6061): MountEmulatedStorage()
I/libpersona( 6061): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6061): v2
I/libpersona( 6061): KNOX_SDCARD not a persona
,I/GoogleURLConnFactory( 1979): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  807): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6061 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6061): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/CAE     (  807): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  807): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  807): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  807): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  807): removeSContextService() : service = Auto Rotation
D/SContextService(  807): ===== SContext Service List =====
D/SContextManager(  807):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3a4add69, service=Auto Rotation
,D/KeyguardViewMediator( 1168): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1168): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1168): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1168): notifyScreenOffLocked
,D/TimaKeyStoreProvider( 6061): TimaSignature is unavailable
,D/ActivityThread( 6061): Added TimaKeyStore provider
,D/DisplayPowerController(  807): ColorFade: onAnimationStart
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/KeyguardViewMediator( 1168): timeout : 5000
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
,D/lights  (  807): lcd : 0 +
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SQLiteSecureOpenHelper( 3302): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3302): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1168): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1168): handleNotifyScreenOff
,I/CAE     (  807): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  807): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  807): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  807): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  296): sendContextData: -76, 13, -47, 0
,D/lights  (  807): lcd : 0 -
,D/InputMethodManagerService(  807): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  807):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  807):  handler : SCREEN_ON end
,D/ResourcesManager( 6061): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/NotificationService(  807): ACTION_SCREEN_ON
D/LightsService(  807): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 807) 
,D/LightsService(  807): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  807): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  807): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=on
,V/voice   (  289): voice_set_parameters: enter: screen_state=on
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
I/WifiNative-HAL(  807): startHal
V/audio_hw_primary(  289): adev_set_parameters: exit
,E/wifi    (  807): getStaticLongField sWifiHalHandle 0x958df7fc
D/wifi    (  807): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x701502
I/WifiNative-HAL(  807): Could not start hal
,D/WifiStateMachine(  807): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  807): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  807): setSuspendOptimizations: 4 false
E/WifiStateMachine(  807): mSuspendOptNeedsDisabled 4
,I/SecExternalDisplayIntents_Java(  807): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  807): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  807): Bridge Server is not available
,D/PersonaManagerService(  807): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  807): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1469): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1469): call the applyRotuiing
,I/PeopleContactsSync( 1979): CP2 sync disabled
,D/AndroidRuntime( 6068): 
D/AndroidRuntime( 6068): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6068): CheckJNI is OFF
,D/AndroidRuntime( 6068): setted country_code = Germany
,D/AndroidRuntime( 6068): setted countryiso_code = DE
,D/AndroidRuntime( 6068): setted sales_code = DBT
,D/AndroidRuntime( 6068): readGMSProperty: start
D/AndroidRuntime( 6068): readGMSProperty: already setted!!
D/AndroidRuntime( 6068): readGMSProperty: end
D/AndroidRuntime( 6068): addProductProperty: start
,I/SamsungIME( 1853): getNextShiftState() cursorCapsMode : 0
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  807): mCallbacks.updateBrightness()
D/DisplayPowerController(  807): getFinalBrightness : 8 -> 0
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  807): !@ ColorFade entry
D/DisplayPowerController(  807): ColorFade: onAnimationEnd
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 2140): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2140): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/AutomaticBrightnessController(  807): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  807): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  807): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  807): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  807): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  807): unregisterListener ::   
,E/Sensors (  807): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  807): unregisterListener ::   
,D/DisplayPowerController(  807): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  807): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  807): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
V/ActivityManager(  807): Display changed displayId=0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SystemBroadcastReceiver( 5160): [#DCM#] [DCM_Performance] onReceive completed in time  1953 microsec. 
,I/SystemBroadcastReceiver( 5160): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 5160): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 5160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1979): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1979): (HTTPLog)-Static: isShipBuild true
I/System.out( 1979): (HTTPLog)-Thread-240-169904278: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/LightsService(  807): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 807) 
,E/AffinityControl( 6068): AffinityControl: registerfunction enter
,D/LightsService(  807): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  807): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SSRM:m  (  807): SIOP:: AP = 470, PST = 435, CUR = 300
,D/SensorManager(  807): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  807): turn on LED for charging
,D/AndroidRuntime( 6068): Calling main entry com.android.commands.pm.Pm
,W/ConfigFetchTask( 1979): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1979): fetch service done; releasing wakelock
,I/ConfigFetchService( 1979): stopping self
I/CAE     (  807): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  807): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  807): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  807): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  296): sendContextData: -76, 13, -46, 0
,I/CAE     (  807): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 21, 22,
,D/SensorHubManager(  807): SendSensorHubData: send data = -63, 14, 14, 21, 22
D/Sensorhubs(  296): sendContextData: -63, 14, 14, 21, 22
,D/PackageManager(  807): START PACKAGE DELETE: observer{45278467}
D/PackageManager(  807): pkg{<packageName>}
D/PackageManager(  807): user{0}
D/PackageManager(  807): caller{2000}
D/PackageManager(  807): flags{3}
D/PersonaManagerService(  807): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  807): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  807): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  807): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  807): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  807): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  807): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  807): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/MotionRecognitionService(  807):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  807):  handler : SCREEN_OFF end 
,I/WifiNative-HAL(  807): startHal
,E/wifi    (  807): getStaticLongField sWifiHalHandle 0x958df7fc
D/wifi    (  807): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x70140e
I/WifiNative-HAL(  807): Could not start hal
D/ApplicationPolicy(  807): getApplicationUninstallationEnabled
D/ApplicationPolicy(  807): getApplicationUninstallationEnabled :  enabled true
D/WifiStateMachine(  807): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  807): handleScreenStateChanged Exit: false
,D/NotificationService(  807): ACTION_SCREEN_OFF
D/LightsService(  807): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 807) 
,D/LightsService(  807): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
E/WifiStateMachine(  807): setSuspendOptimizations: 4 true
E/WifiStateMachine(  807): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  807): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  807): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  807): Bridge Server is not available
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/PackageManager(  807): !@killApplicatoin: 10375, uninstall pkg
,I/ActivityManager(  807): Force stopping com.example.hello appid=10375 user=-1: uninstall pkg
,I/ActivityManager(  807): Killing 5367:com.example.hello/u0a375 (adj 0): stop com.example.hello
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,I/ActivityManager(  807):   Force finishing activity ActivityRecord{228eebe8 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  807): Set to : 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
,D/WifiService(  807): Client connection lost with reason: 4
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  807): Excessive delay in setPowerMode(): 256ms
D/PowerManagerService(  807): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  807): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL(  807): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  807): Invalid hint ID.
I/QCOM PowerHAL(  807): Got set_interactive hint
,I/PowerManagerService(  807): [PWL] Off : 0s ago
,I/PowerManagerService(  807): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  807): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  807): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=807, ws=WorkSource{10117}) (elapsedTime=20652)
I/PowerManagerService(  807): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1979, ws=null) (elapsedTime=13066)
I/PowerManagerService(  807): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2813)
,I/PowerManagerService(  807): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2813)
I/PowerManagerService(  807): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  807): [PWL]     mDisplayReady : false
I/PowerManagerService(  807): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  807): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  807): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  807): [PWL] sb release: PowerManagerService.Display
,W/PackageSettings(  807): Skipping PackageSetting{179b233b com.test.thalitest/10367} due to missing metadata
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:87000 mC
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:87000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 87.0 degC
,I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 1
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6096): MountEmulatedStorage()
,E/Zygote  ( 6096): v2
I/libpersona( 6096): KNOX_SDCARD checking this for 10114
I/libpersona( 6096): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6096 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  807): Killing 5252:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,I/ActivityManager(  807): Force stopping com.example.hello appid=10375 user=0: pkg removed
,D/ResourcesManager(  807): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 6096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/SELinux ( 6096): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SamsungIME( 1853): mOCRHelper is null
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/InputReader(  807): Reconfiguring input devices.  changes=0x00000010
V/AlarmManager(  807): waitForAlarm result :4
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/Finsky  ( 5995): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/GeofencerStateMachine( 1552): Ignoring removeGeofence because network location is disabled.
,D/TimaKeyStoreProvider( 6096): TimaSignature is unavailable
,D/ActivityThread( 6096): Added TimaKeyStore provider
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/art     ( 4301): Explicit concurrent mark sweep GC freed 2981(167KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 1.215ms total 48.361ms
,D/SurfaceWidgetView( 1481): destroyHardwareResources():760730616
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  807): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  807): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/Launcher( 1481): onRestart, Launcher: 586323334
,D/ResourcesManager( 6096): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/Launcher( 1481): onStart, Launcher: 586323334
,D/Launcher.HomeView( 1481): onStart
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBarManagerService(  807): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  807): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager( 6031): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/SecContentProvider2(  807): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  807): mCursor = null
,E/LightSensor(  807): RED : 2, GREEN : 2, BLUE : 2, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/LightsService(  807): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  807): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  807): unregisterListener ::   
,D/lights  (  807): led_pattern : 1 +
,D/RegisteredServicesCache( 1469): empty dynamic service
,D/lights  (  807): led_pattern : 1 -
,D/LightsService(  807): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/libprocessgroup(  807): failed to open /acct/uid_10002/pid_5252/cgroup.procs: No such file or directory
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/InputMethodManagerService(  807): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  807): Got RemoteException sending setActive(false) notification to pid 5367 uid 10375
,W/ContextImpl(  807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/RCPManagerService(  807): PackageReceiver onReceive()
,I/HarmonyEASService(  807): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/Timeline(  807): Timeline: Activity_windows_visible id: ActivityRecord{2051296d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:48101
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/KnoxMUMContainerPolicy(  807): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  807): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  807): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  807): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  807): uID is 10375
V/EnterpriseBillingPolicy(  807): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  807): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  807): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  807): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  807): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  807): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  807): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  807): removeObsoleteFile: deleting file=11_task.xml
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/EnterpriseDeviceManagerService(  807): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  807): Admin package name: com.google.android.gms
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ResourcesManager( 6031): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Books/Books.apk
,D/PersonaManagerService(  807): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  807): MSG_ACTION_SCREEN_OFF called
,D/ActivityThread( 6096): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,D/ActivityThread( 6096): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/NfcService( 1469): call the applyRotuiing
,V/Finsky  ( 5995): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2140): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Finsky  ( 5995): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/art     (  807): Explicit concurrent mark sweep GC freed 38969(2MB) AllocSpace objects, 9(144KB) LOS objects, 30% free, 35MB/51MB, paused 4.587ms total 447.101ms
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  807): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 5160): [#DCM#] [DCM_Performance] onReceive completed in time  66 microsec. 
I/SystemBroadcastReceiver( 5160): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5160): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 5160): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ActivityManager(  807): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  807): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,D/PowerManagerService(  807): [PWL] sb release: PowerManagerService.Broadcasts
D/PackageManager(  807): delete codoeFile: 
D/SSRM:m  (  807): SIOP:: AP = 470, PST = 440, CUR = 300
I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 6096): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager(  807): result of delete: 1{45278467}
,W/ActivityManager(  807): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  807): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  807): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/AndroidRuntime( 6068): Shutting down VM
,I/Gmail   ( 6096): getAccountsCursor
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6096): Observing account changes for notifications
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  807): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/SSRM:a  (  807): DeviceInfo:: 000000000000
D/SSRM:a  (  807): SettingsAirViewInfo:: 000000000
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Gmail   ( 6096): Error finding the version of the Email provider.....
E/Gmail   ( 6096): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6096): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 6096): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 6096): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6096): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6096): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6096): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6096): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6096): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6096): getAccountsCursor
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/Finsky  ( 5995): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ResourcesManager(  807): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(  807): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 1979): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/SQLiteLog( 6096): (283) recovered 656 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/AcmsKeyStoreHelper( 5900):  getKeyStoreForApplication Enter
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  807): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  807): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SettingSearchManagerReceiver( 1475): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1475): addSearchInfoDB
D/UsbSettingsManager(  807): clearDefaults: com.example.hello
I/CrashAnrDetector(  807): onPackageRemoved : com.example.hello
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6148): MountEmulatedStorage()
,E/Zygote  ( 6148): v2
I/libpersona( 6148): KNOX_SDCARD checking this for 10168
I/libpersona( 6148): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6148 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,I/AcmsKeyStoreHelper( 5900): Key Store exist
I/AcmsKeyStoreHelper( 5900): Hence loading the keystore file
,E/File    ( 6096): fail readDirectory() errno=2
,I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/Gmail   ( 6096): notifyAccountChanged
,I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Gmail   ( 6096): getAccountsCursor
,I/Gmail   ( 6096): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6096): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6096): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
,D/ActivityThread( 6148): Added TimaKeyStore provider
,D/ResourcesManager( 6148): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,D/AcmsKeyStoreHelper( 5900):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5900): getKeyStoreForApplication success 
,I/Gmail   ( 6096): getAccountsCursor
D/AcmsCore( 5900): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5900): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5900): Decrementing - Counter value: 1
,D/AcmsCore( 5900): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5900): This is NOT a valid MirrorLink app
D/AcmsCore( 5900): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5900): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5900): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 5900): Counter value is 0: Stopping ACMS service
,E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.onCreate(SettingSearchProvider.java:187)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6148): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6148): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 6148): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6148): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6148): Couldn't open settingsearch.db for writing (will try read-only):
E/SQLiteOpenHelper( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteOpenHelper( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.onCreate(SettingSearchProvider.java:187)
E/SQLiteOpenHelper( 6148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteOpenHelper( 6148): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteOpenHelper( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6148): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6148): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteOpenHelper( 6148): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6148): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6148): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6148): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AcmsServiceMonitor( 5900): getSvcCounter - Counter value: 0
,D/AcmsService( 5900): Enter onDestroy
I/AcmsService( 5900): cleanUp(): inside service clean up
D/AcmsCore( 5900): AcmsCore: inside DeInit
D/AcmsCore( 5900): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5900): AcmsCertificateMngr: inside cleanup
,W/SQLiteOpenHelper( 6148): Opened settingsearch.db in read-only mode
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AcmsRevocationMngr( 5900): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 5900): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5900): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5900): getSvcCounter - Counter value: 0
E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/SQLiteDatabase( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 6148): Writing exception to parcel
E/DatabaseUtils( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/DatabaseUtils( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/DatabaseUtils( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/DatabaseUtils( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/DatabaseUtils( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/DatabaseUtils( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
,D/AcmsService( 5900): killing acms process
I/Process ( 5900): Sending signal. PID: 5900 SIG: 9
,I/SettingSearchManagerReceiver( 1475): putValues : exception = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 1475): 	at android.content.ContentProviderProxy.insert(ContentProviderNative.java:475)
W/System.err( 1475): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.putValues(SettingSearchManagerReceiver.java:71)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB_NetworkSettings(SettingSearchManagerReceiver.java:149)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB(SettingSearchManagerReceiver.java:89)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.onReceive(SettingSearchManagerReceiver.java:54)
W/System.err( 1475): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 1475): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 1475): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1475): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/SQLiteDatabase( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 6148): Writing exception to parcel
E/DatabaseUtils( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/DatabaseUtils( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/DatabaseUtils( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/DatabaseUtils( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/DatabaseUtils( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/DatabaseUtils( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
I/SettingSearchManagerReceiver( 1475): putValues : exception = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 1475): 	at android.content.ContentProviderProxy.insert(ContentProviderNative.java:475)
W/System.err( 1475): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.putValues(SettingSearchManagerReceiver.java:71)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB_NetworkSettings(SettingSearchManagerReceiver.java:162)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB(SettingSearchManagerReceiver.java:89)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.onReceive(SettingSearchManagerReceiver.java:54)
W/System.err( 1475): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 1475): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 1475): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1475): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/SQLiteDatabase( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 6148): Writing exception to parcel
E/DatabaseUtils( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/DatabaseUtils( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/DatabaseUtils( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/DatabaseUtils( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/DatabaseUtils( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/DatabaseUtils( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
I/SettingSearchManagerReceiver( 1475): putValues : exception = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 1475): 	at android.content.ContentProviderProxy.insert(ContentProviderNative.java:475)
W/System.err( 1475): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.putValues(SettingSearchManagerReceiver.java:71)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB_NetworkSettings(SettingSearchManagerReceiver.java:172)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB(SettingSearchManagerReceiver.java:89)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.onReceive(SettingSearchManagerReceiver.java:54)
W/System.err( 1475): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 1475): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 1475): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1475): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/SQLiteDatabase( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 6148): Writing exception to parcel
E/DatabaseUtils( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/DatabaseUtils( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/DatabaseUtils( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/DatabaseUtils( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/DatabaseUtils( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/DatabaseUtils( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
I/SettingSearchManagerReceiver( 1475): putValues : exception = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 1475): 	at android.content.ContentProviderProxy.insert(ContentProviderNative.java:475)
W/System.err( 1475): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.putValues(SettingSearchManagerReceiver.java:71)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB_NetworkSettings(SettingSearchManagerReceiver.java:189)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB(SettingSearchManagerReceiver.java:89)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.onReceive(SettingSearchManagerReceiver.java:54)
W/System.err( 1475): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 1475): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 1475): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1475): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteDatabase( 6148): Failed to open database '/data/user/0/com.sec.providers.settingsearch/databases/settingsearch.db'.
E/SQLiteDatabase( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/SQLiteDatabase( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/SQLiteDatabase( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
E/DatabaseUtils( 6148): Writing exception to parcel
E/DatabaseUtils( 6148): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/DatabaseUtils( 6148): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/DatabaseUtils( 6148): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 6148): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 6148): 	at com.sec.providers.settingsearch.SettingSearchProvider.insert(SettingSearchProvider.java:347)
E/DatabaseUtils( 6148): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/DatabaseUtils( 6148): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
E/DatabaseUtils( 6148): 	at android.os.Binder.execTransact(Binder.java:446)
I/SettingSearchManagerReceiver( 1475): putValues : exception = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
W/System.err( 1475): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 1475): 	at android.content.ContentProviderProxy.insert(ContentProviderNative.java:475)
W/System.err( 1475): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.putValues(SettingSearchManagerReceiver.java:71)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB_NetworkSettings(SettingSearchManagerReceiver.java:205)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.addSearchInfoDB(SettingSearchManagerReceiver.java:89)
W/System.err( 1475): 	at com.android.phone.SettingSearchManagerReceiver.onReceive(SettingSearchManagerReceiver.java:54)
W/System.err( 1475): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 1475): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 1475): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 1475): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SettingSearchManagerReceiver( 1475): endInsert
I/ActivityManager(  807): Process ACMS.Process (pid 5900)(adj 0) has died(83,606)
I/ActivityManager(  807): Killing 4856:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
F/libc    ( 5655): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e3d350 in tid 5655 (p.assistantmenu)
E/        (  277): failed responding to client: Bad address
E/audit_log( 2169): File locking failed. error= Bad file number
,I/ActivityManager(  807): Process com.samsung.android.app.assistantmenu (pid 5655)(adj 0) has died(89,606)
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
I/Zygote  (  314): Process 5655 exited due to signal (7)
W/libprocessgroup(  807): failed to open /acct/uid_10078/pid_4856/cgroup.procs: No such file or directory
E/Zygote  ( 6166): MountEmulatedStorage()
E/Zygote  ( 6166): v2
I/libpersona( 6166): KNOX_SDCARD checking this for 1000
I/libpersona( 6166): KNOX_SDCARD not a persona
I/ActivityManager(  807): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SQLiteLog( 1662): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1662): (10) POSIX Error : 9 SQLite Error : 3850
I/EventHub(  807): Removing device '/dev/input/event4' due to inotify event
,I/art     (  314): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 10.842ms
,I/EventHub(  807): Removing device '/dev/input/event5' due to inotify event
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 300us total 17.011ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.918ms
,I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:73000 mC
I/ThermalEngine(  307): Sensor:tsens_tz_sensor6:73000 mC
I/ThermalEngine(  307): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 73.0 degC
,I/SELinux ( 6166): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
I/ThermalEngine(  307): ACTION: OPT_CURR_REQ 0
E/SELinux ( 6166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6166): TimaSignature is unavailable
,D/ActivityThread( 6166): Added TimaKeyStore provider
,I/EventHub(  807): Removing device '/dev/input/event6' due to inotify event
,D/ResourcesManager( 6166): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,W/ContextImpl( 6166): Unable to create files subdir /data/data/com.samsung.android.app.assistantmenu/cache
,E/ActivityThread( 6166): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  807): Removing device '/dev/input/event7' due to inotify event
,F/libc    ( 5995): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0cba4c0 in tid 5995 (android.vending)
,E/        (  277): failed responding to client: Bad address
E/        (  277): ptrace detach from 5995 failed: No such process
E/        (  277): debuggerd committing suicide to free the zombie!
,E/audit_log( 2169): File locking failed. error= Bad file number
,F/libc    ( 6096): Fatal signal 7 (SIGBUS), code 2, fault addr 0x746418c0 in tid 6181 (IntentService[G)
,F/libc    ( 6096): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2169): File locking failed. error= Bad file number
,E/lowmemorykiller(  246): Error writing /proc/6096/oom_score_adj; errno=22
,I/EventHub(  807): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager(  807): Process com.android.vending (pid 5995)(adj 5) has died(97,607)
,W/ActivityManager(  807): Scheduling restart of crashed service com.android.vending/com.google.android.finsky.services.DailyHygiene in 1000ms
,I/ActivityManager(  807): Process com.google.android.gm (pid 6096)(adj 0) has died(109,607)
,W/ActivityManager(  807): Scheduling restart of crashed service com.google.android.gm/.GmailIntentService in 1000ms
,I/EventHub(  807): Removing device '/dev/input/event9' due to inotify event
,I/Zygote  (  314): Process 5995 exited due to signal (7)
,I/Zygote  (  314): Process 6096 exited due to signal (7)
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6182): MountEmulatedStorage()
E/Zygote  ( 6182): v2
I/libpersona( 6182): KNOX_SDCARD checking this for 10114
I/libpersona( 6182): KNOX_SDCARD not a persona
,I/ActivityManager(  807): Start proc com.google.android.gm for broadcast com.google.android.gm/.GmailReceiver: pid=6182 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  807): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 6182): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6182): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6182): TimaSignature is unavailable
,D/ActivityThread( 6182): Added TimaKeyStore provider
,I/EventHub(  807): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 6182): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ActivityManager(  807): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/SQLiteDatabase( 6182): Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
E/SQLiteDatabase( 6182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6182): 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
E/SQLiteDatabase( 6182): 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
E/SQLiteDatabase( 6182): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/SQLiteDatabase( 6182): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6182): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 6182): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 6182): 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
E/SQLiteDatabase( 6182): 	at com.android.email.provider.r.run(SourceFile:6330)
E/SQLiteDatabase( 6182): 	at com.android.emailcommon.b.h.au(SourceFile:247)
E/SQLiteDatabase( 6182): 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
E/SQLiteDatabase( 6182): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6182): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6182): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime( 6182): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 6182): Process: com.google.android.gm, PID: 6182
E/AndroidRuntime( 6182): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 6182): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 6182): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 6182): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 6182): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 6182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6182): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 6182): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 6182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6182): 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
E/AndroidRuntime( 6182): 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
E/AndroidRuntime( 6182): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/AndroidRuntime( 6182): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/AndroidRuntime( 6182): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/AndroidRuntime( 6182): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime( 6182): 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
E/AndroidRuntime( 6182): 	at com.android.email.provider.r.run(SourceFile:6330)
E/AndroidRuntime( 6182): 	at com.android.emailcommon.b.h.au(SourceFile:247)
E/AndroidRuntime( 6182): 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
E/AndroidRuntime( 6182): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 6182): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 6182): 	... 3 more
,F/libc    ( 6182): Fatal signal 7 (SIGBUS), code 2, fault addr 0x76b43198 in tid 6200 (AsyncTask #1)
,F/libc    ( 6182): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2169): File locking failed. error= Bad file number
,I/ActivityManager(  807): Process com.google.android.gm (pid 6182)(adj 0) has died(110,607)
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  807): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6204 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 6204): MountEmulatedStorage()
I/libpersona( 6204): KNOX_SDCARD checking this for 10117
E/Zygote  ( 6204): v2
I/libpersona( 6204): KNOX_SDCARD not a persona
,I/Zygote  (  314): Process 6182 exited due to signal (7)
,I/SELinux ( 6204): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6204): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/TimaKeyStoreProvider( 6204): TimaSignature is unavailable
,D/ActivityThread( 6204): Added TimaKeyStore provider
,D/ResourcesManager( 6204): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 6204): Unable to create files subdir /data/data/com.google.android.talk/cache
,E/ActivityThread( 6204): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 6204): Fatal signal 7 (SIGBUS), code 2, fault addr 0xafa10000 in tid 6204 (le.android.talk)
,F/libc    ( 6204): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2169): File locking failed. error= Bad file number
,I/ActivityManager(  807): Process com.google.android.talk (pid 6204)(adj 0) has died(110,607)
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  807): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6219): MountEmulatedStorage()
,E/Zygote  ( 6219): v2
I/libpersona( 6219): KNOX_SDCARD checking this for 10117
I/libpersona( 6219): KNOX_SDCARD not a persona

```
