#### Test 564496606be5677_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
I/SELinux ( 7279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7279): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
--------- beginning of system
W/libprocessgroup(  894): failed to open /acct/uid_10093/pid_6066/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7279): TimaSignature is unavailable
D/ActivityThread( 7279): Added TimaKeyStore provider
D/ResourcesManager( 7279): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 7279): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7279): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Icing   ( 2477): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
D/Mms/MmsApp( 7279): [start]    onCreate() consume time = 0.0
D/Mms/TelephonyPermission( 7279): start operation mode monitor
I/Icing   ( 2477): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
D/ResourcesManager( 7279): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager( 7279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 7279): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 7279): isDefault true
D/Mms/MmsApp( 7279): onCreate() com.android.mms
D/Mms/MmsConfig( 7279): [start]    MmsConfig.init() consume time = 31.404687
D/Mms/MmsConfig( 7279): before partial update
D/Mms/MmsConfig( 7279): Load Resize quality : 80
E/ActivityThread( 7279): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 7279): serviceId : 1, features : -1
D/Mms/MmsConfig( 7279): setFreeMessageEnabled, free message policy(getSupportedFeatures) is = -1
D/TP/MmsSmsProvider( 1480): query,matched:2117, calling pid = 7279
D/TP/MmsSmsProvider( 1480): match 2117:Elapsed time : 1.117 ms
E/ActivityThread( 7279): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 7279): serviceId : 3, features : -1
D/Mms/MmsConfig( 7279): Shop agent feature value :-1
D/Mms/MmsConfig( 7279):  enable multiwindow = true
E/Mms/MessageUtils( 7279): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 7279): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 7279): [end]    init() consume time = 38.971615
D/Mms/MmsApp( 7279): [start]    initCountryIso consume time = 0.215677
D/CountryDetector(  894): The first listener is added
D/Mms/MmsApp( 7279): [end]    initCountryIso consume time = 3.705572
D/Mms/Contact( 7279): [start]    init() consume time = 0.882448
D/TP/MmsSmsProvider( 1480): query,matched:13, calling pid = 7279
D/TP/MmsSmsProvider( 1480): match 13:Elapsed time : 0.714 ms
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_list_thumbnail.pkm
D/Mms/Contact( 7279): [end]    init consume time = 13.28599
D/Mms/DraftCache( 7279): [start]    rebuildCache consume time = 1.331302
D/TP/MmsSmsProvider( 1480): query,matched:12, calling pid = 7279
D/Mms/Conversation( 7279): [start]    init() consume time = 1.643281
D/TP/MmsSmsProvider( 1480): match 12:Elapsed time : 0.845 ms
D/TP/MmsSmsProvider( 1480): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1480): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/Mms/DraftCache( 7279): [end]    rebuildCache consume time = 5.617709
D/TP/MmsSmsProvider( 1480): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1480): need read changed broadcast:false
D/Mms/Conversation( 7279): [end]    init consume time = 1.648229
V/AlarmManager(  894): waitForAlarm result :4
D/Mms/TelephonyUtils( 7279): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager( 7279): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7279): auto download without roaming -> true
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/Mms/TelephonyUtils( 7279): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 7279): getSubId from simSlot 1, return Value = -1000
D/Mms/DownloadManager( 7279): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 7279): auto download without roaming -> true
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 7279): auto download during roaming secondary -> false
D/Mms/DownloadManager( 7279): mAutoDownload ------> true
D/Mms/MessagingNotification( 7279): [start]    init() consume time = 13.158177
D/Mms/MessagingNotification( 7279): [end]    init consume time = 1.137812
D/Mms/SpamFilter( 7279): [start]    SpamFilter fill() begin consume time = 1.113959
D/TP/MmsSmsProvider( 1480): query,matched:400, calling pid = 7279
D/Mms/ComposeMessageFragment( 7279): [start]    fillCache consume time = 2.038073
D/Mms/ComposeMessageFragment( 7279): fillCache, easy = false
D/Mms/SpamFilter( 7279): [end]    SpamFilter fill() finished consume time = 1.590938
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  894): stay LED for fully charged
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_add.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template_left.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_recieved_check_msg.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_read_check_msg.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
D/AbsListView( 7279): Get MotionRecognitionManager
D/MotionRecognitionService(  894):  ssp status : true
D/Mms/ComposeMessageFragment( 7279): [end]    fillCache consume time = 106.014895
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_contact_picture.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/sms_msg_bt.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw_2.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_bubble_icon_locked.pkm
D/AndroidRuntime( 7299): 
D/AndroidRuntime( 7299): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7299): CheckJNI is OFF
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate1.png
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate2.png
D/AndroidRuntime( 7299): setted country_code = Poland
D/AndroidRuntime( 7299): setted countryiso_code = PL
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate3.png
D/AndroidRuntime( 7299): setted sales_code = XEO
D/AndroidRuntime( 7299): readGMSProperty: start
D/AndroidRuntime( 7299): readGMSProperty: already setted!!
D/AndroidRuntime( 7299): readGMSProperty: end
D/AndroidRuntime( 7299): addProductProperty: start
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_translator_normal.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_press.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_focus.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_disable.pkm
V/BitmapFactory( 7279): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_normal.pkm
E/AffinityControl( 7299): AffinityControl: registerfunction enter
D/AndroidRuntime( 7299): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  894): inState():  stateMachine is null !!
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  894): mDVFSHelper.acquire()
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7318): MountEmulatedStorage()
E/Zygote  ( 7318): v2
I/libpersona( 7318): KNOX_SDCARD checking this for 10191
I/libpersona( 7318): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7318 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
I/SELinux ( 7318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7318): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7299): Shutting down VM
D/TimaKeyStoreProvider( 7318): TimaSignature is unavailable
D/ActivityThread( 7318): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/Mms/BubbleViewCache( 7279): fillCache bubble = 8
D/TP/MmsSmsProvider( 1480): query,matched:0, calling pid = 7279
V/TP/MmsSmsProvider( 1480): getSimpleConversations entered.
D/Mms/Synchronizer( 7279): [start]    doSync consume time = 240.362031
D/TP/MmsSmsProvider( 1480): match 0:Elapsed time : 1.220 ms
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TP/MmsSmsProvider( 1480): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1480): syncDBData start
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1480): syncDBData sms end
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1480): syncDBData mms end
V/TP/MmsSmsProvider( 1480): syncDBData end
D/ResourcesManager( 7318): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/Zygote  ( 7337): MountEmulatedStorage()
I/libpersona( 7337): KNOX_SDCARD checking this for 10077
E/Zygote  ( 7337): v2
I/libpersona( 7337): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7337 uid=10077 gids={50077, 9997} abi=armeabi-v7a
I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
I/SELinux ( 7337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SELinux ( 7337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7337): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/Synchronizer( 7279): [end]    doSync consume time = 45.069636
D/TimaKeyStoreProvider( 7337): TimaSignature is unavailable
D/ActivityThread( 7337): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7337): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/BadgeProvider( 7337): onCreate
D/BadgeProvider( 7337): DatabaseHelper
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/Mms/MessagingNotification( 7279): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1480): query,matched:26, calling pid = 7279
D/TP/SmsProvider( 1480): match 26:Elapsed time : 0.704 ms
D/TP/MmsSmsProvider( 1480): query,matched:6, calling pid = 7279
D/TP/MmsSmsProvider( 1480): match 6:Elapsed time : 1.073 ms
I/Mms/ReservationManager( 7279): ReservationManager()
I/Mms/ReservationManager( 7279): resetAfterConnected()
D/TP/MmsSmsProvider( 1480): query,matched:7, calling pid = 7279
D/TP/MmsSmsProvider( 1480): match 7:Elapsed time : 1.135 ms
I/Mms/ReservationManager( 7279): getReservedSendMessageCount(): retMessageCount=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7362): MountEmulatedStorage()
E/Zygote  ( 7362): v2
I/libpersona( 7362): KNOX_SDCARD checking this for 10024
I/libpersona( 7362): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7362 uid=10024 gids={50024, 9997} abi=armeabi-v7a
I/SELinux ( 7362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/WebViewFactory( 7318): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7318): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/SELinux ( 7362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/LibraryLoader( 7318): Loading: webviewchromium
I/LibraryLoader( 7318): Time to load native libraries: 3 ms (timestamps 7393-7396)
I/LibraryLoader( 7318): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 7362): TimaSignature is unavailable
D/ActivityThread( 7362): Added TimaKeyStore provider
D/ResourcesManager( 7362): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
W/ResourcesManager( 7362): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 7318): Binding Chromium to main looper Looper (main, tid 1) {161504fd}
I/LibraryLoader( 7318): Expected native library version number "",actual native library version number ""
I/chromium( 7318): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7318): Initializing chromium process, renderers=0
W/art     ( 7318): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7318): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7318): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7318): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7318): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7318): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7318): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7318): Remote Branch: 
I/Adreno-EGL( 7318): Local Patches: 
I/Adreno-EGL( 7318): Reconstruct Branch: 
D/Mms/Omacp( 7279): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Mms/MmsApp( 7279): [end]    onCreate() consume time = 215.551874
D/Mms/PerformanceUtils( 7279): link cahcing start
W/chromium( 7318): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 7318): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/Mms/DownloadManager( 7279): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager( 7279): roaming ------> false, mSimSlot = 0
D/Mms/TelephonyUtils( 7279): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager( 7279): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 7279): auto download without roaming -> true
D/Mms/DownloadManager( 7279): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 7279): mAutoDownload ------> true
I/ActivityManager(  894): Killing 6082:com.sec.android.widgetapp.dualclockdigital/u0a102 (adj 15): bgCount ##41
W/art     ( 7318): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7318): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  894): Killing 5744:com.sec.android.GeoLookout/u0a112 (adj 15): bgCount ##41
D/Mms/FreeMessageReceiver( 7279): onReceive, action : android.intent.action.PACKAGE_ADDED
D/Mms/PerformanceUtils( 7279): link cahcing done
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageReceiverService( 7279): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 7279): onHandleIntent: ACTION_PACKAGE_ADDED
D/SystemWebViewEngine( 7318): CordovaWebView is running on device made by: samsung
E/Zygote  ( 7401): MountEmulatedStorage()
E/Zygote  ( 7401): v2
I/libpersona( 7401): KNOX_SDCARD checking this for 10050
I/libpersona( 7401): KNOX_SDCARD not a persona
I/SELinux ( 7401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  894): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7401 uid=10050 gids={50050, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/ActivityManager(  894): Killing 6101:com.sec.android.app.camera/u0a153 (adj 15): bgCount ##41
W/libprocessgroup(  894): failed to open /acct/uid_10112/pid_5744/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10102/pid_6082/cgroup.procs: No such file or directory
W/art     ( 7318): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7318): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 7401): TimaSignature is unavailable
D/ActivityThread( 7401): Added TimaKeyStore provider
D/ResourcesManager( 7401): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 7401): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7401): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/libprocessgroup(  894): failed to open /acct/uid_10153/pid_6101/cgroup.procs: No such file or directory
D/Activity( 7318): performCreate Call secproduct feature valuefalse
D/Activity( 7318): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7318): Render dirty regions requested: true
D/ActivityManager(  894): post active user change for 0
D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
D/MyFiles ( 7401): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager(  894): Killing 5763:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): bgCount ##41
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/installd(  301): system dir 0 : /system/app/
E/installd(  301): system dir 1 : /system/priv-app/
E/installd(  301): system dir 2 : /vendor/app/
E/installd(  301): system dir 3 : /oem/app/
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/TactileAssist(  894): enable value -1
I/TactileAssist(  894): internal enable value -1
I/TactileAssist(  894): intensity value -1
I/TactileAssist(  894): saveAppList value true
I/TactileAssist(  894): List of disabled apps :
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/OpenGLRenderer( 7318): Initialized EGL, version 1.4
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/OpenGLRenderer( 7318): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7318): Enabling debug mode 0
E/Zygote  ( 7428): MountEmulatedStorage()
I/libpersona( 7428): KNOX_SDCARD checking this for 10057
E/Zygote  ( 7428): v2
I/libpersona( 7428): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7428 uid=10057 gids={50057, 9997, 3003, 3002} abi=armeabi-v7a
I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
I/SELinux ( 7428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7428): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/libprocessgroup(  894): failed to open /acct/uid_10148/pid_5763/cgroup.procs: No such file or directory
D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/PackageManager(  894): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/TimaKeyStoreProvider( 7428): TimaSignature is unavailable
D/ActivityThread( 7428): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/ActivityManager(  894): mDVFSHelper.release()
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{3cc062a2 u0 com.test.thalitest/.MainActivity t10} time:107803
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ResourcesManager( 7428): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
W/IInputConnectionWrapper( 7318): showStatusIcon on inactive InputConnection
I/Timeline( 7318): Timeline: Activity_idle id: android.os.BinderProxy@3bab4384 time:107808
W/ResourcesManager( 7428): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/Compatibility( 7428): onReceive() it will make start service
D/Compatibility( 7428): onHandleIntent()
D/Compatibility( 7428): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10191, android.intent.extra.user_handle=0}]
D/Compatibility( 7428): found: 2
D/Compatibility( 7428): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7428): skipping ResolveInfo{13724dc1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7428): considering ResolveInfo{3fa21966 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7428): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7428): enabling receiver ResolveInfo{6a614a7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 1574): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 7428): enabling receiver ResolveInfo{f2bdd54 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 7428): enabling receiver ResolveInfo{161504fd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 7428): enabling receiver ResolveInfo{272665f2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl( 6160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
D/Compatibility( 7428): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7455): MountEmulatedStorage()
I/libpersona( 7455): KNOX_SDCARD checking this for 10097
E/Zygote  ( 7455): v2
I/libpersona( 7455): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7455 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/JsMessageQueue( 7318): Set native->JS mode to OnlineEventsBridgeMode
D/ResourcesManager( 1574): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/chromium( 7318): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7318): 
I/UpdateIcingCorporaServi( 1574): UpdateCorporaTask done [took 92 ms] updated apps [took 92 ms] 
I/SELinux ( 7455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7455): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7455): TimaSignature is unavailable
D/ActivityThread( 7455): Added TimaKeyStore provider
D/ResourcesManager( 7455): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/DocsApplication( 7455): Installing DEX configuration.
D/DexInstaller( 7455): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7455): Provided clientMode=RELEASE, packageInfo=PackageInfo{34697ea8 com.google.android.apps.docs}
D/jxcore_app_log( 7318): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259452416
D/TAG     ( 7455): onCreate()
I/chromium( 7318): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/CrossAppStateProvider( 7455): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7479): MountEmulatedStorage()
E/Zygote  ( 7479): v2
,I/libpersona( 7479): KNOX_SDCARD checking this for 10098
I/libpersona( 7479): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7479 uid=10098 gids={50098, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5778:com.android.calendar/u0a149 (adj 15): bgCount ##41
,I/SELinux ( 7479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 7455): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 7479): TimaSignature is unavailable
,D/ActivityThread( 7479): Added TimaKeyStore provider
,D/ResourcesManager( 7479): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
W/libprocessgroup(  894): failed to open /acct/uid_10149/pid_5778/cgroup.procs: No such file or directory
,W/ResourcesManager( 7479): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 7479): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7479): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7479): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7503): MountEmulatedStorage()
,E/Zygote  ( 7503): v2
I/libpersona( 7503): KNOX_SDCARD checking this for 10032
I/libpersona( 7503): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7503 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 285us total 13.048ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.962ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.338ms
,I/SELinux ( 7503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7503): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7503): TimaSignature is unavailable
D/ActivityThread( 7503): Added TimaKeyStore provider
,D/ResourcesManager( 7503): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7503): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 7455): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/System.out( 7503): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7503): Inside WakeupProvider
,E/DatabaseUtils( 7503): Writing exception to parcel
E/DatabaseUtils( 7503): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7503): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7503): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7503): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7503): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7503): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7503): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7503): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7479): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 7503): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=XEO
,W/System.err( 7479): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7479): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7479): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7479): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7479): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7479): 	at android.content.ContentResolver.query(ContentResolver.java:428)
,W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
,W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7479): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7479): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7479): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
,W/System.err( 7479): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7479): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7479): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7479): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7479): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7479): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7479): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7479): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7479): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7479): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7479): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7479): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7479): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 7503): Writing exception to parcel
E/DatabaseUtils( 7503): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7503): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7503): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7503): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7503): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7503): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7503): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7503): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7503): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7479): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7479): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7479): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7479): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7479): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7479): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7479): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
,W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7479): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7479): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7479): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 7479): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7479): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
,W/System.err( 7479): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7479): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7479): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7479): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7479): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7479): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7479): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7479): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7479): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,W/System.err( 7479): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 7479): [DLApplication]-Init Called!:false
E/[CarMode]( 7479): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 7479): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7479): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7479): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7479): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7479): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7479): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7479): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7479): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7479): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7479): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7479): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7479): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7479): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7479): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoAndroidCore( 7503): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 7479): initialize
,D/[CarModeFW]( 7479): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 7479): CDH-initiazlieCaches : after sync
,E/SMD     (  293): DCD ON
,D/[CarModeFW]( 7479): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7479): CDH-ContactDataHandler initiazlieCaches time : 23
D/[CarModeFW]( 7479): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 7479): DrivingManager-initialize...
,I/SensorService(  894): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  894): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  894): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 7503): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7503): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7479): Need to enable context aware info
,V/MediaPlayer-JNI( 7479): native_setup
V/MediaPlayer( 7479): constructor
,V/MediaPlayer( 7479): setListener
E/MediaPlayer-JNI( 7479): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 7479): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7479): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode]( 7479): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1453288588539
,D/[CarMode]( 7479): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1453288588540
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1453288588540
,D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1453288588540
,D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1453288588542
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1453288588542
,D/TP/SmsProvider( 1480): query,matched:2, calling pid = 7479
D/TP/SmsProvider( 1480): query,matched:2, calling pid = 7479
,D/TP/SmsProvider( 1480): match 2:Elapsed time : 1.870 ms
,D/TP/SmsProvider( 1480): match 2:Elapsed time : 1.234 ms
,I/[CarMode]( 7479): [LogNotNull]-Package name is: com.google.android.apps.maps
E/[CarMode]( 7479): [DLApplication]-Init End!:true
,D/MessageDataHandler( 7479):  getInboxList smsCursor : 16
,D/[CarModeFW]( 7479): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1480): Query uri=content://mms/inbox, match=2, calling pid = 7479
,D/MessageDataHandler( 7479):  getInboxList mmsCursor : 4
,D/MessageDataHandler( 7479):  getInboxList mms,sms cursor join : 3
,D/[CarModeFW]( 7479): RecommendHandler-selection = type = '3'
,D/[CarModeFW]( 7479): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsSmsProvider( 1480): query,matched:0, calling pid = 7479
,V/TP/MmsSmsProvider( 1480): getSimpleConversations entered.
D/[CarModeFW]( 7479): RecommendHandler-selection = type = '3'
,D/TP/MmsSmsProvider( 1480): match 0:Elapsed time : 1.810 ms
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/[CarMode]( 7479): [DLApplication]-GooglePlayServices SUCCESS.
,E/Zygote  ( 7536): MountEmulatedStorage()
E/Zygote  ( 7536): v2
I/libpersona( 7536): KNOX_SDCARD checking this for 10019
I/libpersona( 7536): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7536 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7542): MountEmulatedStorage()
E/Zygote  ( 7542): v2
I/libpersona( 7542): KNOX_SDCARD checking this for 10003
I/libpersona( 7542): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7542 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 7479): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7479): Intent : android.intent.action.PACKAGE_ADDEDWed Jan 20 12:16:28 GMT+01:00 2016
,I/SELinux ( 7536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7536): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/SELinux ( 7542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  894): Explicit concurrent mark sweep GC freed 254837(17MB) AllocSpace objects, 5(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.703ms total 149.415ms
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7536): TimaSignature is unavailable
,D/ActivityThread( 7536): Added TimaKeyStore provider
,E/Zygote  ( 7560): MountEmulatedStorage()
E/Zygote  ( 7560): v2
I/libpersona( 7560): KNOX_SDCARD checking this for 1000
I/libpersona( 7560): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7318): Initializing JXcore engine
W/jxcore-log( 7318): JXcore engine is ready
,I/SELinux ( 7560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7542): TimaSignature is unavailable
,D/[CarModeFW]( 7479): CDH-buildContactCacheWireFrame : cur len =0
,D/ActivityThread( 7542): Added TimaKeyStore provider
,D/TP/MmsProvider( 1480): Query uri=content://mms, match=0, calling pid = 7479
I/ActivityManager(  894): Killing 6216:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/TP/MmsSmsProvider( 1480): query,matched:13, calling pid = 7479
,I/MessageDataHandler( 7479): getUnreadMessageCount :0
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 188
,D/TP/MmsSmsProvider( 1480): match 13:Elapsed time : 2.198 ms
,D/TimaKeyStoreProvider( 7560): TimaSignature is unavailable
D/MessageDataHandler( 7479):  getInboxList address cursor : 16
,D/ResourcesManager( 7542): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/ActivityThread( 7560): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1480): query,matched:0, calling pid = 7479
V/TP/MmsSmsProvider( 1480): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1480): match 0:Elapsed time : 1.084 ms
,D/MessageDataHandler( 7479):  getInboxList thread cursor : 12
,D/[CarModeFW]( 7479): PushMessageService-onCreate
,I/ActivityManager(  894): Killing 6293:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,I/ActivityManager(  894): Killing 6274:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##42
,I/ActivityManager(  894): Killing 6231:com.sec.android.app.sns3/u0a35 (adj 15): bgCount ##43
,E/auditd  ( 2201): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  894): Got Modify Event and sending Denial Intent foraudit.log
,D/MessageDataHandler( 7479):  thread, addr result: 20
,I/[CarModeFW]( 7479): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 227
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,I/[CarModeFW]( 7479): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 231
D/[CarModeFW]( 7479): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7479): PushMessageService-registerPushMessageServiceListener
,D/SecurityLogAgent:SEDenialService(  894): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/ResourcesManager( 7560): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,W/jxcore-log( 7318): Starting JXcore engine
,D/ResourcesManager( 7536): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,W/ContextImpl( 7560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7560): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7584): MountEmulatedStorage()
I/libpersona( 7584): KNOX_SDCARD checking this for 10111
E/Zygote  ( 7584): v2
I/libpersona( 7584): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7584 uid=10111 gids={50111, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/FilterInstaller( 7560): There is no requred permission
I/SELinux ( 7584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  894): Killing 6125:com.google.android.talk/u0a116 (adj 15): bgCount ##41
,D/UserAnalysis.PlaceProvider( 7542): PlaceProvider onCreate()
,D/TimaKeyStoreProvider( 7584): TimaSignature is unavailable
,D/ActivityThread( 7584): Added TimaKeyStore provider
,W/jxcore-log( 7318): Platform android
W/jxcore-log( 7318): 
W/jxcore-log( 7318): Process ARCH arm
W/jxcore-log( 7318): 
,D/ResourcesManager( 7584): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 7479): -[snowdeer] Rec : Missed Call : 355
,D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 382
,D/PackageIntentReceiver( 7584): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7584): Not GearManger package! 
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.SecureDbManager( 7542): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7542): SecurePlaceDbHelper() 
,D/UserAnalysis.PlaceProvider( 7542): Create SecureDbHelper
,E/Zygote  ( 7603): MountEmulatedStorage()
E/Zygote  ( 7603): v2
I/libpersona( 7603): KNOX_SDCARD checking this for 10117
I/libpersona( 7603): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7603 uid=10117 gids={50117, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6660:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/[CarModeFW]( 7479): -[snowdeer] Rec : Favorite : 41
,I/SELinux ( 7603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7603): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 7542): onCreate()
,I/[CarModeFW]( 7479): -[snowdeer] Rec : CallLog : 47
,I/SQLiteSecureOpenHelper( 7542): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7542): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7542): Open Place.db in secure mode
,I/SQLiteSecureOpenHelper( 7542): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7542): ...getDatabaseLocked(b,b,pwd)
,I/[CarModeFW]( 7479): -[snowdeer] Rec : Schedule : 29
,D/[CarModeFW]( 7479): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7479): MyPlaceProvider-=============
D/[CarModeFW]( 7479): MyPlaceProvider-=============
D/[CarModeFW]( 7479): MyPlaceProvider-=============
D/[CarModeFW]( 7479): MyPlaceProvider-=============
D/[CarModeFW]( 7479): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7479): MyPlaceProvider-==============
D/[CarModeFW]( 7479): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7479): MyPlaceProvider-==============
D/[CarModeFW]( 7479): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7479): MyPlaceProvider-==============
D/[CarModeFW]( 7479): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 497
,D/TimaKeyStoreProvider( 7603): TimaSignature is unavailable
,D/ActivityThread( 7603): Added TimaKeyStore provider
D/[CarMode]( 7479): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@f9669f14, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@435177a] LOCATIONS
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_6231/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10037/pid_6274/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7479): -[snowdeer] Rec : During DL app : 13
W/libprocessgroup(  894): failed to open /acct/uid_10037/pid_6293/cgroup.procs: No such file or directory
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 508
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6216/cgroup.procs: No such file or directory
I/[CarModeFW]( 7479): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7479): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7479): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7479): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 510
,D/ResourcesManager( 7603): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7603): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  894): failed to open /acct/uid_10116/pid_6125/cgroup.procs: No such file or directory
,D/MagazineService Version( 7603): Magazine-Administrator: 11
,D/MagazineService Version( 7603): Magazine-Provider: 14
,D/MagazineService Version( 7603): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7603): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7603): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7603): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7619): MountEmulatedStorage()
,E/Zygote  ( 7619): v2
I/libpersona( 7619): KNOX_SDCARD checking this for 1000
I/libpersona( 7619): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7619 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7603): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager(  894): Killing 5900:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): bgCount ##41
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
I/SELinux ( 7619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7619): TimaSignature is unavailable
,D/ActivityThread( 7619): Added TimaKeyStore provider
,D/ResourcesManager( 7619): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10157/pid_5900/cgroup.procs: No such file or directory
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7634): MountEmulatedStorage()
I/libpersona( 7634): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7634): v2
I/libpersona( 7634): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 4672:com.android.providers.calendar/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7318): JXcore Cordova bridge is ready!
I/jxcore-log( 7318): 
,W/jxcore-log( 7318): JXcore engine is started
,D/TimaKeyStoreProvider( 7634): TimaSignature is unavailable
,D/ActivityThread( 7634): Added TimaKeyStore provider
,D/ResourcesManager( 7634): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10045/pid_4672/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7634): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7634): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7634): Enter Oncreate
D/AcmsServiceMonitor( 7634): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 7634): creating AcmsCore
D/AcmsCore( 7634): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 7634): AcmsCore
,I/System.out( 7503): INFO:Resource not found:/Common.properties Using default values
,D/AcmsCore( 7634): init
,D/AcmsCore( 7634): Looper handler is not null
D/AcmsCore( 7634): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7634): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7634): Incrementing - Counter value: 1
D/AcmsCore( 7634): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsCertificateMngr( 7634): AcmsCertificateMngr
D/AcmsRevocationMngr( 7634): AcmsRevocationMngr
,D/AcmsService( 7634): onStartCommand
,D/AcmsService( 7634): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7634): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7634): Incrementing - Counter value: 2
D/AcmsService( 7634): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7634): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7653): MountEmulatedStorage()
I/libpersona( 7653): KNOX_SDCARD checking this for 10165
E/Zygote  ( 7653): v2
I/libpersona( 7653): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7653 uid=10165 gids={50165, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 7318): Toggling radios to true
I/jxcore-log( 7318): 
,D/BluetoothAdapter( 7318): enable()
,I/SELinux ( 7653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/BluetoothAdapter( 7318): enable(): BT is already enabled..!
,E/SELinux ( 7653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiService(  894): New client listening to asynchronous messages
,I/WifiManager( 7318): packageName : com.test.thalitest
D/SecContentProvider(  894): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  894): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  894): mCursor = null
D/WifiService(  894): setWifiEnabled: true pid=7318, uid=10191
E/WifiService(  894): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  894): Permission Denial: getCurrentUser() from pid=7318, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  894): Failed getting userId using ActivityManagerNative
W/WifiService(  894): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7318, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  894): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  894): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  894): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  894): name = wifi_on
,I/WifiService(  894): disconnect: pid=7318, uid=10191
,I/wpa_supplicant( 1311): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7318): Radios toggled
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): My device name is: samsung-SM-G900F
I/jxcore-log( 7318): 
,D/TimaKeyStoreProvider( 7653): TimaSignature is unavailable
,D/ActivityThread( 7653): Added TimaKeyStore provider
,I/wpa_supplicant( 1311): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1311): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1311): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1311): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1311): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1311): Disconnected - do not scan
I/wpa_supplicant( 1311): wlan0: State: DISCONNECTED -> DISCONNECTED
D/ResourcesManager( 7653): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  894): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/AcmsService( 7634): Inside handle Intent
D/AcmsService( 7634): App added - package name: com.test.thalitest
D/AcmsCore( 7634): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7634): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7634): Incrementing - Counter value: 3
D/AcmsCore( 7634): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7634): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7634): Decrementing - Counter value: 2
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
D/WifiP2pService(  894): InactiveState{ what=143375 }
D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
D/CommandListener(  288): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2263): Read error: ssl=0xb4e64200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2263): SSL shutdown failed: ssl=0xb4e64200: I/O error during system call, Broken pipe
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): ignoring duplicate network state non-change
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  894): Start Disconnecting Watchdog 1
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1311): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1311): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1311): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1311): First Scan Start
I/wpa_supplicant( 1311): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  894): ConnectModeState: Network connection lost 
E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ResourcesManager( 7653): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  894): Not allowed due to - mEnabled false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  894): updateConfiguredNetworkExpiration - currTime: 1453288589726
D/CSLegacyTypeTracker(  894): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
D/TelephonyNetworkFactory( 1480): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
D/WifiStateMachine(  894): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524292
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,V/NetworkStats(  894): updateIfacesLocked()
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): performPollLocked(flags=0x1)
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
,V/NetworkStats(  894): performPollLocked() took 11ms
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/SecContentProvider2(  894): mCursor = null
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/KidsPlatformStub( 7653): Package not found : com.sec.android.app.kidshome
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7673): MountEmulatedStorage()
I/libpersona( 7673): KNOX_SDCARD checking this for 10169
E/Zygote  ( 7673): v2
I/libpersona( 7673): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7673 uid=10169 gids={50169, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5879:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,V/AlarmManager(  894): waitForAlarm result :4
,I/SELinux ( 7673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7673): TimaSignature is unavailable
,D/ActivityThread( 7673): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/ResourcesManager( 7673): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1480): FileWriteThread : threadType = 3
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_5879/cgroup.procs: No such file or directory
,E/SQLiteLog( 7673): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 6598): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  894): Killing 6186:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2477): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2477): Loading module APK com.google.android.play.games
,D/ResourcesManager( 2477): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10167/pid_6186/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2477): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2477): Submit a task: k
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2477): Processing package: com.test.thalitest
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 7711): MountEmulatedStorage()
E/Zygote  ( 7711): v2
I/libpersona( 7711): KNOX_SDCARD checking this for 10039
I/libpersona( 7711): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7711 uid=10039 gids={50039, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/GassUtils( 2477): Found app info for package com.test.thalitest:18. Hash: 8d179c3391de64cb252217b95c8671d16c87cb117668119dbcd10fd1a66cc302
,D/k       ( 2477): Found info for package com.test.thalitest in db.
,I/ApplicationPolicy(  894): updateDataUsageMap
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  894): MasterInitialState.processMessage what=3
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  894): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,I/CLocInfoService(  894): CLoinfo wifi false
,I/SELinux ( 7711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7711): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SystemBroadcastReceiver( 6341): [#DCM#] [DCM_Performance] onReceive completed in time  383 microsec. 
,D/accuweather( 2059): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 6341): [#DCM#] Calling notifyListeners. 
,I/DCMController( 6341): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 6341): [#DCM#] setIsConnectedForExtractors 
,W/SLocation(  894): No Active Data Connection
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 6310): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 7711): TimaSignature is unavailable
,D/ActivityThread( 7711): Added TimaKeyStore provider
,D/ResourcesManager( 7711): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,I/PowerManagerService(  894): [PWL] Off : 5s ago
,I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=894, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=4621)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1881)
,I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1880)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=894, ws=null) (elapsedTime=655)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=2477, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=110)
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,W/BaseAppContext( 2477): Using Auth Proxy for data requests.
,I/ActivityManager(  894): Killing 5954:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,D/BootupListener( 1480): ACTION_DRIVELINK
,D/SettingsProvider(  894): name = drivelink_navigation
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1001
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
D/BootupListener( 1480): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  894): name = internet_call_settings_visibility
,D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
,D/SettingsProvider(  894): selectionArgs: 1001
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7729): MountEmulatedStorage()
E/Zygote  ( 7729): v2
I/libpersona( 7729): KNOX_SDCARD checking this for 1000
I/libpersona( 7729): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7729 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 318us total 15.374ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.192ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.256ms
,I/SELinux ( 7729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7729): TimaSignature is unavailable
,D/ActivityThread( 7729): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10113/pid_5954/cgroup.procs: No such file or directory
,D/ResourcesManager( 7729): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7729):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7729):  SeDenialReceiver : File path = null
,I/ActivityManager(  894): Killing 6341:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/Hs20UtilService( 1312): Starting #6
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1312): Starting #7
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
,I/PCWCLIENTTRACE_PushUtil( 7218): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7218): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7218): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7218): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7218): noConnectivity : true
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7746): MountEmulatedStorage()
E/Zygote  ( 7746): v2
I/libpersona( 7746): KNOX_SDCARD checking this for 10002
I/libpersona( 7746): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7746 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1311): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1311): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1311): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1311): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  894): [1,453,288,590,746 ms] noteScanEnd no scan source
,E/WifiStateMachine(  894): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2284ebb0 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info0x
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/SELinux ( 7746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CLocInfoService(  894): External Intent Received android.net.wifi.SCAN_RESULTS
,D/TimaKeyStoreProvider( 7746): TimaSignature is unavailable
,D/ActivityThread( 7746): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10004/pid_6341/cgroup.procs: No such file or directory
,D/ResourcesManager( 7746): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1311): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1311): Associated with C0.AA.48
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/ActivityManager(  894): Killing 6406:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7763): MountEmulatedStorage()
I/libpersona( 7763): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7763): v2
I/libpersona( 7763): KNOX_SDCARD not a persona
I/wpa_supplicant( 1311): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
I/ActivityManager(  894): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7763 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 1311): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1311): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1311): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1311): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1311): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1311): Blacklist: Clear (temp) 
I/wpa_supplicant( 1311): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,E/WifiStateMachine(  894): Network connection established
,D/WifiNative-HAL(  894): callSECApiVoid - ID [50]
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  894): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  894): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  894): Got NetworkAgent Messenger
D/ConnectivityService(  894): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  894): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  894): NetworkAgent connected
,E/WifiStateMachine(  894): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  894): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  894): Start Dhcp Watchdog 2
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7763): TimaSignature is unavailable
,D/ActivityThread( 7763): Added TimaKeyStore provider
,D/ResourcesManager( 7763): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10043/pid_6406/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7763): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/AcmsKeyStoreHelper( 7634):  getKeyStoreForApplication Enter
,I/DIAGMON_AGENT( 7763): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend false
,D/WifiP2pService(  894): InactiveState{ what=143375 }
D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,I/AcmsKeyStoreHelper( 7634): Key Store exist
I/AcmsKeyStoreHelper( 7634): Hence loading the keystore file
,I/DIAGMON_AGENT( 7763): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7763): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7763): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7763): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,V/AlarmManager(  894): waitForAlarm result :4
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7780): MountEmulatedStorage()
E/Zygote  ( 7780): v2
I/libpersona( 7780): KNOX_SDCARD checking this for 10010
I/libpersona( 7780): KNOX_SDCARD not a persona
,D/FactoryTest( 6684): Not factory mode
,D/FactoryTest( 6684): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6684): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6684): still no open session command from host, so toast
,W/ContextImpl( 6684): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6684): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6684): Timeline: Activity_launch_request id:com.android.settings time:112288
,W/art     ( 2477): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 273.539ms
,I/ActivityManager(  894): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7780 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/dhcpcd  ( 7781): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7781): version 5.5.6 starting
,E/dhcpcd  ( 7781): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7780): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/PersonaManagerService(  894): inState():  stateMachine is null !!
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  894): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7781): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7781): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7781): bssid match
,I/dhcpcd  ( 7781): wlan0: rebinding lease of 192.168.1.136
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/TimaKeyStoreProvider( 7780): TimaSignature is unavailable
,D/ActivityThread( 7780): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/MTPRx   ( 6684): started activity for popup
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3484): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3484): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager( 7780): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/AcmsKeyStoreHelper( 7634):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7634): getKeyStoreForApplication success 
D/AcmsCore( 7634): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7634): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7634): Decrementing - Counter value: 1
D/AcmsCore( 7634): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7634): This is NOT a valid MirrorLink app
D/AcmsCore( 7634): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7634): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7634): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 7634): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7634): getSvcCounter - Counter value: 0
D/AcmsService( 7634): Enter onDestroy
,I/AcmsService( 7634): cleanUp(): inside service clean up
D/AcmsCore( 7634): AcmsCore: inside DeInit
D/AcmsCore( 7634): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7634): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 7634): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7634): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7634): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7634): getSvcCounter - Counter value: 0
,D/AcmsService( 7634): killing acms process
I/Process ( 7634): Sending signal. PID: 7634 SIG: 9
,I/ActivityManager(  894): Process ACMS.Process (pid 7634)(adj 0) has died(77,554)
,D/ResourcesManager( 6684): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6684): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Killing 6827:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,E/SettingsReceiverActivity( 6684): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/FOTA_Client( 7780): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  894): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@13d7e004 attribute=null, token = android.os.BinderProxy@2b9d3738
,I/Icing   ( 2477): Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,I/FOTA_Client( 7780): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,E/SMD     (  293): DCD ON
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,I/FOTA_Client( 7780): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,I/ActivityManager(  894): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7803 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6684): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,I/ActivityManager(  894): Killing 7054:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,E/Zygote  ( 7803): MountEmulatedStorage()
E/Zygote  ( 7803): v2
I/libpersona( 7803): KNOX_SDCARD checking this for 10018
I/libpersona( 7803): KNOX_SDCARD not a persona
,D/ResourcesManager( 2477): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SELinux ( 7803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsReceiverActivity( 6684): dev.kiessupport is : TRUE
,I/Icing   ( 2477): Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,W/libprocessgroup(  894): failed to open /acct/uid_10011/pid_6827/cgroup.procs: No such file or directory
,D/Activity( 6684): performCreate Call secproduct feature valuefalse
D/Activity( 6684): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/TimaKeyStoreProvider( 7803): TimaSignature is unavailable
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ActivityThread( 7803): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ActivityManager(  894): post active user change for 0
,D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
,D/ResourcesManager( 7803): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10178/pid_7054/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/Timeline( 7318): Timeline: Activity_idle id: android.os.BinderProxy@3bab4384 time:112648
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/KLMS-2.4.503: ( 7803): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7803): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453288591579
,I/KLMS-2.4.503: ( 7803): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7803): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
D/ChimeraCfgMgr( 2477): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/KLMS-2.4.503: ( 7803): StateImplV2(): networkChangeListener().END
D/ChimeraModuleLdr( 2477): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  894): Killing 6484:com.samsung.android.app.FileShareServer/u0a74 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7820): MountEmulatedStorage()
I/libpersona( 7820): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7820): v2
I/libpersona( 7820): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7820 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 7820): TimaSignature is unavailable
,D/ActivityThread( 7820): Added TimaKeyStore provider
,D/ResourcesManager( 7820): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10074/pid_6484/cgroup.procs: No such file or directory
,I/SO_AGENT( 7820): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5205): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7256): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7256): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7256): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7256): [SLFUCHKMGR] constructor called
,I/SA      ( 7256): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7256): [OR] == isSIMCardReady false ==
I/SA      ( 7256): [SCU] == networkStateCheck == false
I/SA      ( 7256): [OR] onReceive END
,E/SPPClientService( 5205): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7838): MountEmulatedStorage()
,E/Zygote  ( 7838): v2
I/libpersona( 7838): KNOX_SDCARD checking this for 10070
I/libpersona( 7838): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7838 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  894): Killing 6508:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/SELinux ( 7838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7838): TimaSignature is unavailable
,D/ActivityThread( 7838): Added TimaKeyStore provider
,D/ResourcesManager( 7838): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7838): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7838): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/comsamsunglog( 7838): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7838): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7838): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7838): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7838): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7838): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7838): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7838): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  894): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 10070
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6508/cgroup.procs: No such file or directory
,D/accuweather( 7838): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7838): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7838): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7838): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7838): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7838): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7838): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7838): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1349): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7838): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7838): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
,E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 1000
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6554:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6554/cgroup.procs: No such file or directory
,W/ResourcesManager( 7855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7855): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7855): premStatus:2
,I/KnoxUsageLogPro( 7855): isEulaShown : false
I/KnoxUsageLogPro( 7855): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7870): MountEmulatedStorage()
,E/Zygote  ( 7870): v2
I/libpersona( 7870): KNOX_SDCARD checking this for 10087
I/libpersona( 7870): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7870 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7177:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 7870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7870): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7870): TimaSignature is unavailable
,D/ActivityThread( 7870): Added TimaKeyStore provider
,D/ResourcesManager( 7870): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10014/pid_7177/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 7198:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,D/Headlines( 5437): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5437): getCountryCode(): countryCode = PL
,D/Headlines( 5437): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5437): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5437): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5437): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7889): MountEmulatedStorage()
I/libpersona( 7889): KNOX_SDCARD checking this for 10127
E/Zygote  ( 7889): v2
I/libpersona( 7889): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7889 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7889): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7889): TimaSignature is unavailable
,D/ActivityThread( 7889): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10015/pid_7198/cgroup.procs: No such file or directory
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7889): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  ( 7781): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,I/dhcpcd  ( 7781): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/WebViewFactory( 7889): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7889): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/LibraryLoader( 7889): Loading: webviewchromium
,I/LibraryLoader( 7889): Time to load native libraries: 4 ms (timestamps 3768-3772)
I/LibraryLoader( 7889): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7889): Binding Chromium to main looper Looper (main, tid 1) {245a7c03}
,I/LibraryLoader( 7889): Expected native library version number "",actual native library version number ""
,I/chromium( 7889): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7889): Initializing chromium process, renderers=0
,W/art     ( 7889): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7889): Requires BLUETOOTH permission
,W/chromium( 7889): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7889): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7889): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7889): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7889): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7889): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7889): Remote Branch: 
I/Adreno-EGL( 7889): Local Patches: 
I/Adreno-EGL( 7889): Reconstruct Branch: 
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  894): WifiStateMachine DHCP successful
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  894): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  894): Not connected state, yet.
E/WifiStateMachine(  894): VerifyingLinkState enter
,D/WifiStateMachine(  894): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  894): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  894): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  894): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  894): Adding iface wlan0 to network 503
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  894): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/NSApplication( 7889): Starting up...
,D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  894): updateSourceRoutes : add src route for:192.168.1.136
V/        (  288): QcRouteController
,E/WifiStateMachine(  894): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  894): Now, connected state.
E/WifiStateMachine(  894): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  894): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  288): QcRouteController
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  894): mBoosterFLAG : 0
I/WifiTrafficPoller(  894): current booster mode : FullMode
,D/WifiNative-HAL(  894): callSECApiVoid - ID [212]
,V/        (  288): QcRouteController
,E/WifiStateMachine(  894): ConnectedState Enter  mScreenOn=false scanperiod=20000
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  894): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,D/ConnectivityService(  894): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): calling update connectivity
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): ignoring duplicate network state non-change
D/ConnectivityService(  894): ignoring duplicate network state non-change
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,I/art     (  894): Explicit concurrent mark sweep GC freed 62941(3MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 35MB/51MB, paused 1.473ms total 152.611ms
,D/ConnectivityService(  894): currentScore = 0, newScore = 60
D/ConnectivityService(  894):    accepting network in place of null
D/ConnectivityService(  894): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1480): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  894): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity(  894): Not allowed due to - mEnabled false
,V/NetworkStats(  894): updateIfacesLocked()
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): performPollLocked(flags=0x1)
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkStatsFactory(  894): UpdateStatsForKnox
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524290
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,V/NetworkStats(  894): performPollLocked() took 9ms
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/GAV2    ( 7455): Thread[GAThread,5,main]: No campaign data found.
,E/Zygote  ( 7989): MountEmulatedStorage()
,E/Zygote  ( 7989): v2
I/libpersona( 7989): KNOX_SDCARD checking this for 10137
I/libpersona( 7989): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7989 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6465:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7989): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7989): TimaSignature is unavailable
,D/ActivityThread( 7989): Added TimaKeyStore provider
,D/ResourcesManager( 7989): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7989): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7989): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  894): failed to open /acct/uid_10033/pid_6465/cgroup.procs: No such file or directory
,D/QuickConnect( 7989): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7989): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7989): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8004): MountEmulatedStorage()
,E/Zygote  ( 8004): v2
I/libpersona( 8004): KNOX_SDCARD checking this for 10162
I/libpersona( 8004): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8004 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  894): Killing 4787:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,I/art     (  320): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 11.380ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 12.554ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 8.398ms
,I/SELinux ( 8004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8004): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8004): TimaSignature is unavailable
,D/ActivityThread( 8004): Added TimaKeyStore provider
,D/ResourcesManager( 8004): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8004): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8004): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8004): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8004): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  894): failed to open /acct/uid_10034/pid_4787/cgroup.procs: No such file or directory
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/BadgeProvider( 7337): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 7337): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7337): sendNotify, [notify] : null
D/BadgeProvider( 7337): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7337): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7337): update, [UpdateCount] : 1
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher.Model( 1501): reloadBadges entered.
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7729): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7729): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7729): StateMachine : Current State = 1
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7729): StateMachine : Changed Current State = 1
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,I/ActivityManager(  894): Killing 6036:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,E/Zygote  ( 8028): MountEmulatedStorage()
,E/Zygote  ( 8028): v2
I/libpersona( 8028): KNOX_SDCARD checking this for 10177
I/libpersona( 8028): KNOX_SDCARD not a persona
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,I/ActivityManager(  894): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8028 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8004): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 8028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  894): failed to open /acct/uid_10041/pid_6036/cgroup.procs: No such file or directory
,I/SELinux ( 8028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8028): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 8028): TimaSignature is unavailable
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityThread( 8028): Added TimaKeyStore provider
,D/Tethering(  894): MasterInitialState.processMessage what=3
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  894): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  894): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  894): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  894): CLocinfo wifi true 
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2059): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2251): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2251): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 6310): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3713): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 8028): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  894): Killing 6006:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ServiceManager(  352): Waiting for service AtCmdFwd...
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  894): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  894): failed to open /acct/uid_10047/pid_6006/cgroup.procs: No such file or directory
V/GLSActivity( 2263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/VacuumService( 2263): Vacuum at: now=1453288593721 tag=VacuumService
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WaitQueueForNetworkActivate( 7711): notifyNetworkActivated
W/ContextImpl( 7711): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  894): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7711): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 7711): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7711): exit::IDLE
D/InitializeManagerStateMachine( 7711): entry::NETWORK_CHECK
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7711): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7711): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7711): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7711): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7711): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7711): entry::SUCCESS
D/hcjo    ( 7711): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/Hs20UtilService( 1312): Starting #8
I/Hs20UtilService( 1312): Message received 5007
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 7711): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7711): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7711): exit::SUCCESS
D/InitializeManagerStateMachine( 7711): entry::IDLE
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1312): Starting #9
I/Hs20UtilService( 1312): Message received 5007
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 1312): Starting #10
I/Hs20UtilService( 1312): Message received 5007
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 1312): Starting #11
I/Hs20UtilService( 1312): Message received 5007
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
I/WifiStateMachine(  894): callSECApi what=220
D/WifiStateMachine(  894): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
I/PCWCLIENTTRACE_PushUtil( 7218): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7218): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7218): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7218): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7763): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7763): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Toast
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/PowerManagerService(  894): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/FOTA_Client( 7780): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 7780): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client( 7780): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/ConnectivityService(  894): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
I/KLMS-2.4.503: ( 7803): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 7803): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453288594055
I/KLMS-2.4.503: ( 7803): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7803): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.503: ( 7803): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.503: ( 7803): NetworkChangeOperations(): uploadRequestLog().START 
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/KLMS-2.4.503: ( 7803): StateImplV2(): networkChangeListener().END
I/SO_AGENT( 7820): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SPPClientService( 5205): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
I/SA      ( 7256): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
I/SA      ( 7256): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7256): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7256): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7256): [OR] == isSIMCardReady false ==
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7256): [SCU] == networkStateCheck == true
I/SA      ( 7256): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7256): isChinaCountryCode : false
I/SA      ( 7256): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7256): [OR] == networkStateCheck true ==
I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7318): 
I/SA      ( 7256): [OR] GetMyCountryZoneTask
I/SA      ( 7256): [OR] onReceive END
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7256): [SRS] prepareGetMyCountryZone
I/SA      ( 7256): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7256): [SSP] query invoked
D/accuweather( 7838): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 7838): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
I/SA      ( 7256): [TPMU] GetMccFromDB : null
I/SA      ( 7256): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7256): [TPM] isNoProxy(default) : true
I/KnoxUsageLogPro( 7855): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7855): premStatus:2
I/KnoxUsageLogPro( 7855): isEulaShown : false
I/KnoxUsageLogPro( 7855): KnoxUsageReceiver onReceive : not Processible, just return
D/Headlines( 5437): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5437): getCountryCode(): countryCode = PL
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Headlines( 5437): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5437): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5437): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5437): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5437): requestUpdateNewsWelcomeCard !!! no welcome card
E/File    ( 7256): fail readDirectory() errno=2
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/QuickConnect( 7989): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 7989): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7989): PeriphStartReceiver.onReceive - no need to start
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  894): exchangeData() failure , invalid userId
D/RCPManagerService(  894): exchangeData() failure , invalid userId
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7729): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7729): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7729): StateMachine : Current State = 1
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7729): StateMachine : Changed Current State = 1
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  894): mDVFSHelper.release()
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7711): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 7711): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7711): exit::IDLE
D/InitializeManagerStateMachine( 7711): entry::NETWORK_CHECK
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7711): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7711): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7711): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7711): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7711): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7711): entry::SUCCESS
D/hcjo    ( 7711): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7711): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7711): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7711): exit::SUCCESS
D/InitializeManagerStateMachine( 7711): entry::IDLE
,E/SMD     (  293): DCD ON
,I/SA      ( 7256): [RC New] Execute method=[GET] start
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ProcessCpuTracker(  894): Skipping unknown process pid 8068
,W/ProcessCpuTracker(  894): Skipping unknown process pid 8069
W/ProcessCpuTracker(  894): Skipping unknown process pid 8071
,I/SA      ( 7256): [RC New] Security=[true]
,I/System.out( 7256): Thread-1120(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7256): Thread-1120(ApacheHTTPLog):isShipBuild true
,I/System.out( 7256): Thread-1120(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7318): 
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  894): identical MTU - not setting
D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  894): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  288): QcRouteController
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,V/        (  288): QcRouteController
,W/NetworkManagementService(  894): route cmd failed: 
W/NetworkManagementService(  894): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  894): '
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  894): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  894): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524295
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2477): CM callback handler got msg 524295
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  894): SIOP:: AP = 410, PST = 357, CUR = 450
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 2263): Scheduling Phenotype for one-off execution 12688 seconds from now (1453288595425)
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 7256): [RC New] [v2liruge] api execute + 728
I/SA      ( 7256): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7256): AsyncTask #1 calls detatch()
,I/SA      ( 7256): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7256): [OCP] update openData : PL
,I/SA      ( 7256): [TPMU] getNetworkMcc : 
,I/SA      ( 7256): [SCU] saveMccToPreferece Start
I/SA      ( 7256): [SCU] RegionMCC : 260
I/SA      ( 7256): [SSP] query invoked
,I/SA      ( 7256): [TPMU] GetMccFromDB : null
I/SA      ( 7256): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7256): [SCU] saveMccToPreferece End
,I/SA      ( 7256): [RC New] executeRequest [v2liruge] end. 779
I/SA      ( 7256): [RC New] Execute end
,D/GetConfigurationSnapshotOperation( 2263): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/SA      ( 7256): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7256): [OR] GetMyCountryZoneTask Success
,I/PhenotypeFlagCommitter( 2263): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2263): Using platform SSLCertificateSocketFactory
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2263): Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 2263, getuid(): 10011
,I/qtaguid ( 2263): Tagging socket 85 with tag 1000120100000000{268440065,0} uid -1, pid: 2263, getuid(): 10011
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 2263): Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 2263, getuid(): 10011
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  894): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  894): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PackageManager(  894): [MSG] MCS_UNBIND
,I/ActivityManager(  894): Killing 7362:com.wsomacp/u0a24 (adj 15): bgCount ##41
,W/libprocessgroup(  894): failed to open /acct/uid_10024/pid_7362/cgroup.procs: No such file or directory
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,I/SurfaceFlinger(  257): id=17 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Toast (-2/9)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PowerManagerService(  894): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 894) eventTime = 118548
,D/PowerManagerService(  894): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894 (0x0)
D/PowerManagerService(  894): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=894, ws=WorkSource{10058}) (elapsedTime=3477)
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/GAV4    ( 7889): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7318): Test app app.js loaded
I/jxcore-log( 7318): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7318): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7318): BLE advertisement is supported
I/jxcore-log( 7318): 
,I/chromium( 7318): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7218): mConnectivityHandler : connected
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7218): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7218): [GetString-S]
,I/ReactiveServiceManager( 7218): Supported : 1
,D/QSEECOMAPI: (  894): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: (  894): App is not loaded in QSEE
,D/QSEECOMAPI: (  894): Loaded image: APP id = 2
,D/QSEECOMAPI: (  894): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  894): QSEECom_shutdown_app, app_id = 2
E/terrier (  894): handleString: Failed to handle string(-4)
,E/terrier (  894): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7218): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7218): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7218): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7218): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7218): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7218): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService(  894): [PWL] Off : 15s ago,
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/dhcpcd  ( 7781): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7781): wlan0: no IPv6 Routers available
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7711): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7711): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7711): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7711): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7711): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7711): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7711): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7711): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7711): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7711): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7711): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7711): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7711): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7711): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7711): entry::IDLE
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,V/AlarmManager(  894): waitForAlarm result :4
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  894): SIOP:: AP = 350, PST = 349, CUR = 450
,D/Finsky  ( 6598): [1080] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6598): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 4
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  894): SIOP:: AP = 320, PST = 341, CUR = 450
,I/PowerManagerService(  894): [PWL] Off : 30s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,V/AlarmManager(  894): waitForAlarm result :8
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 336, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/BatteryService(  894): stay LED for fully charged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,I/PowerManagerService(  894): [PWL] Off : 50s ago
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  894): SIOP:: AP = 290, PST = 332, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 5
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  894): SIOP:: AP = 290, PST = 328, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 290, PST = 324, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 75s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/SSRM:m  (  894): SIOP:: AP = 290, PST = 321, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 6
,I/ClearcutLoggerApiImpl( 2263): disconnect managed GoogleApiClient
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SSRM:m  (  894): SIOP:: AP = 270, PST = 315, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/SSRM:m  (  894): SIOP:: AP = 270, PST = 308, CUR = 450
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  894): [PWL] Off : 105s ago
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 293, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/Watchdog(  894): !@Sync 7
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 284, CUR = 450
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...,
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 278, CUR = 450
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 140s ago
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 274, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 8
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 271, CUR = 450
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 260, PST = 268, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/jxcore-log( 7318): --= Surplus to requirements =--
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): ****TEST TOOK:  ms ****
I/jxcore-log( 7318): 
,I/jxcore-log( 7318): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7318): 
,D/AndroidRuntime( 8140): 
D/AndroidRuntime( 8140): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8140): CheckJNI is OFF
,D/AndroidRuntime( 8140): setted country_code = Poland
,D/AndroidRuntime( 8140): setted countryiso_code = PL
,D/AndroidRuntime( 8140): setted sales_code = XEO
,D/AndroidRuntime( 8140): readGMSProperty: start
,D/AndroidRuntime( 8140): readGMSProperty: already setted!!
D/AndroidRuntime( 8140): readGMSProperty: end
D/AndroidRuntime( 8140): addProductProperty: start
,E/AffinityControl( 8140): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8140): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  894): START PACKAGE DELETE: observer{648403528}
D/PackageManager(  894): pkg{<packageName>}
D/PackageManager(  894): user{0}
D/PackageManager(  894): caller{2000}
D/PackageManager(  894): flags{3}
,D/PersonaManagerService(  894): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  894): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  894): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  894): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  894): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  894): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  894): getApplicationUninstallationEnabled
D/ApplicationPolicy(  894): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  894): !@killApplicatoin: 10191, uninstall pkg
,I/ActivityManager(  894): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  894): Killing 7318:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
,I/ActivityManager(  894):   Force finishing activity ActivityRecord{3cc062a2 u0 com.test.thalitest/.MainActivity t10}
,W/ActivityManager(  894): mDVFSHelper.acquire()
,D/WifiService(  894): Client connection lost with reason: 4
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/WindowState(  894): WIN DEATH: Window{2613c311 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/ActivityManager(  894): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/ActivityManager(  894):   Force finishing activity ActivityRecord{3cc062a2 u0 com.test.thalitest/.MainActivity t10 f}
,W/ActivityManager(  894): Duplicate finish request for ActivityRecord{3cc062a2 u0 com.test.thalitest/.MainActivity t10 f}
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,I/art     ( 6384): Explicit concurrent mark sweep GC freed 31163(1708KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 373us total 39.440ms
,D/FocusedStackFrame(  894): Set to : 0
,I/DBG_DM  ( 3713): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 40
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 2477): Explicit concurrent mark sweep GC freed 38272(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 21MB/35MB, paused 645us total 92.300ms
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3713): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 40
,W/GeofencerStateMachine( 2263): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/art     ( 1574): Explicit concurrent mark sweep GC freed 53588(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 481us total 109.323ms
,I/DBG_DM  ( 3713): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/SamsungIME( 1868): mOCRHelper is null
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7803): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KLMS-2.4.503: ( 7803): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453288749940
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7803): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7803): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 40
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3713): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/art     (  894): Explicit concurrent mark sweep GC freed 61043(4MB) AllocSpace objects, 54(864KB) LOS objects, 30% free, 35MB/51MB, paused 1.722ms total 151.295ms
,I/art     (  894): WaitForGcToComplete blocked for 64.706ms for cause Explicit
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 3713): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3713): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3713): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  894): post active user change for 0
D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
,I/DBG_DM  ( 3713): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/RegisteredServicesCache( 1472): empty dynamic service
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/SurfaceWidgetView( 1501): destroyHardwareResources():451771029
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  894): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/Launcher( 1501): onRestart, Launcher: 833548703
,D/Launcher( 1501): onStart, Launcher: 833548703
D/Launcher.HomeView( 1501): onStart
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/Launcher.HomeView( 1501): onStop
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2059): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2059): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SurfaceFlinger(  257): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1181): value : false
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/Zygote  ( 8168): MountEmulatedStorage()
I/libpersona( 8168): KNOX_SDCARD checking this for 10103
E/Zygote  ( 8168): v2
I/libpersona( 8168): KNOX_SDCARD not a persona
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/ActivityManager(  894): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8168 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SurfaceFlinger(  257): id=18 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/9)
I/SELinux ( 8168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
I/SurfaceFlinger(  257): id=18 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
I/SELinux ( 8168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
E/SELinux ( 8168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService(  894): Package has changed for user 0
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/Timeline( 3713): Timeline: Activity_idle id: android.os.BinderProxy@dac1f91 time:271246
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/EnterpriseDeviceManagerService(  894): Admin package name: com.google.android.gms
,W/InputMethodManagerService(  894): Got RemoteException sending setActive(false) notification to pid 7318 uid 10191
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/TimaKeyStoreProvider( 8168): TimaSignature is unavailable
,D/ActivityThread( 8168): Added TimaKeyStore provider
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/ResourcesManager( 8168): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,W/ActivityManager(  894): mDVFSHelper.release()
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{3f8e6719 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:271321
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/RCPManagerService(  894): PackageReceiver onReceive()
,I/HarmonyEASService(  894): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  894): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8168): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8168): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8168): MDMBridge.setEnterpriseBridge()
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  894): uID is 10191
V/EnterpriseBillingPolicy(  894): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - enter
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - end - null
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
,D/elm:14451( 8168): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TaskPersister(  894): removeObsoleteFile: deleting file=10_task.xml
,D/TaskPersister(  894): removeObsoleteFile: deleting file=9_task.xml
,D/elm:14451( 8168): ElmAgentService : onCreate()
,D/elm:14451( 8168): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8168): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8168): MDMBridge.getInstance()
D/elm:14451( 8168): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14451( 8168): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 8187): MountEmulatedStorage()
E/Zygote  ( 8187): v2
I/libpersona( 8187): KNOX_SDCARD checking this for 10016
I/libpersona( 8187): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8187 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/art     (  894): Explicit concurrent mark sweep GC freed 15412(784KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 6.567ms total 295.802ms
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/SELinux ( 8187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8187): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8168): ElmAgentService : onDestroy().
,I/ActivityManager(  894): Killing 7279:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1181): Icon Only
,D/LockPatternUtilsCache( 1181): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1181): value : false
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): There is/are notification(s) 
,D/TimaKeyStoreProvider( 8187): TimaSignature is unavailable
,D/ActivityThread( 8187): Added TimaKeyStore provider
,D/ResourcesManager( 8187): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/PackageManager(  894): delete codoeFile: 
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8187): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8187): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8187): onReceive() : package name is not s health. Return !!!
,D/CountryDetector(  894): No listener is left
,D/PackageManager(  894): result of delete: 1{648403528}
,D/AndroidRuntime( 8140): Shutting down VM
I/PCWCLIENTTRACE_PushUtil( 7218): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7218): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7218): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7218): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10049/pid_7279/cgroup.procs: No such file or directory
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  ( 8204): MountEmulatedStorage()
E/Zygote  ( 8204): v2
I/libpersona( 8204): KNOX_SDCARD checking this for 10033
I/libpersona( 8204): KNOX_SDCARD not a persona
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/ActivityManager(  894): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8204 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7401:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux ( 8204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux ( 8204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TimaKeyStoreProvider( 8204): TimaSignature is unavailable
,D/ActivityThread( 8204): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10050/pid_7401/cgroup.procs: No such file or directory
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  894): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  894): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/FeatureConfig( 8204): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/SMD     (  293): DCD ON
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  894): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  894): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8204): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8229): MountEmulatedStorage()
E/Zygote  ( 8229): v2
I/libpersona( 8229): KNOX_SDCARD checking this for 10034
I/libpersona( 8229): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8229 uid=10034 gids={50034, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  894): Killing 7428:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,I/SELinux ( 8229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8229): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  894): failed to open /acct/uid_10057/pid_7428/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8229): TimaSignature is unavailable
,D/ActivityThread( 8229): Added TimaKeyStore provider
,D/ResourcesManager( 8229): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,F/libc    ( 8229): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa03e2000 in tid 8229 (oid.app.shealth)
,E/audit_log( 2201): File locking failed. error= Bad file number
,E/audit_log( 2201): File locking failed. error= Bad file number
,E/SharedPreferencesImpl( 8204): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  894): Removing device '/dev/input/event4' due to inotify event
,I/ActivityManager(  894): Process com.sec.android.app.shealth (pid 8229)(adj 0) has died(156,596)
,F/libc    ( 5205): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7764ea00 in tid 5205 (om.sec.spp.push)
,F/libc    ( 5205): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2201): File locking failed. error= Bad file number
,I/Zygote  (  320): Process 8229 exited due to signal (7)
,I/EventHub(  894): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  894): Process com.sec.spp.push (pid 5205)(adj 0) has died(162,596)
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8244): MountEmulatedStorage()
I/libpersona( 8244): KNOX_SDCARD checking this for 10037
E/Zygote  ( 8244): v2
I/libpersona( 8244): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8244 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  320): Process 5205 exited due to signal (7)
,I/EventHub(  894): Removing device '/dev/input/event6' due to inotify event
,I/EventHub(  894): Removing device '/dev/input/event7' due to inotify event
,I/EventHub(  894): Removing device '/dev/input/event8' due to inotify event
,I/EventHub(  894): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  894): Removing device '/dev/input/event10' due to inotify event
,I/SELinux ( 8244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8244): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8244): TimaSignature is unavailable
,D/ActivityThread( 8244): Added TimaKeyStore provider
,I/EventHub(  894): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager( 8244): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/        ( 8244): Zip: read 65557 failed: I/O error
,W/zipro   ( 8244): Error opening archive /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk: I/O Error
D/asset   ( 8244): failed to open Zip archive '/system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk'
,W/ContextImpl( 8244): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8244): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8244): Zip: read 65557 failed: I/O error
,F/libc    ( 8244): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb502c000 in tid 8244 (moteNotiProcess)
,F/libc    ( 8244): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2201): File locking failed. error= Bad file number
,I/ActivityManager(  894): Process com.sec.spp.push:RemoteNotiProcess (pid 8244)(adj 0) has died(161,597)
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8267): MountEmulatedStorage()
E/Zygote  ( 8267): v2
I/libpersona( 8267): KNOX_SDCARD checking this for 10041
I/libpersona( 8267): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8267 uid=10041 gids={50041, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/Zygote  (  320): Process 8244 exited due to signal (7)
,I/SELinux ( 8267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8267): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8267): TimaSignature is unavailable
,D/ActivityThread( 8267): Added TimaKeyStore provider
,D/ResourcesManager( 8267): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,W/        ( 8267): Zip: read 65557 failed: I/O error
W/zipro   ( 8267): Error opening archive /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk: I/O Error
D/asset   ( 8267): failed to open Zip archive '/system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk'
,W/ContextImpl( 8267): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
,E/ActivityThread( 8267): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8267): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3b1f000 in tid 8267 (sdk.samsunglink)
,F/libc    ( 8267): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2201): File locking failed. error= Bad file number
,I/ActivityManager(  894): Process com.samsung.android.sdk.samsunglink (pid 8267)(adj 0) has died(161,597)
,I/SA      ( 7256): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7256): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10191 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1820): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7726a44c in tid 1820 (d.process.acore)
,F/libc    ( 1820): Fatal signal 7 (SIGBUS), code 2, fault addr 0x776f8e10 in tid 1894 (ContactsProvide)
,F/libc    ( 1820): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2201): File locking failed. error= Bad file number

```
