#### Test 63377149f0d5e10_thali03_samsung-SM-N910C Logs


```
--------- beginning of system
03-18 15:47:53.140  8605  8605 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:53.140  8605  8605 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-18 15:47:53.140  8605  8605 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
--------- beginning of main
03-18 15:47:53.145  8554  8554 D Mms/MmsApp: [start]    initCountryIso consume time = 59.075625
03-18 15:47:53.145  3508  4054 D CountryDetector: The first listener is added
03-18 15:47:53.155  8554  8554 D Mms/MmsApp: [end]    initCountryIso consume time = 10.784084
03-18 15:47:53.155  8554  8554 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.061208
03-18 15:47:53.160  8554  8554 D Mms/MmsConfig: before partial update
03-18 15:47:53.160  3508  3594 V AlarmManager: waitForAlarm result :4
03-18 15:47:53.165  8554  8554 D Mms/MmsConfig: Load Resize quality : 80
03-18 15:47:53.170  8554  8554 D Mms/MmsConfig:  enable multiwindow = true
03-18 15:47:53.180  8605  8605 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
03-18 15:47:53.185  8554  8554 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-18 15:47:53.185  8554  8554 E Mms/MessageUtils: updateCountryIso : update country iso info 
03-18 15:47:53.190  8554  8554 D Mms/PackageInfo: com.sec.imsservice is not installed
03-18 15:47:53.190  8554  8554 D Mms/MmsConfig: [end]    init() consume time = 36.728667
03-18 15:47:53.190  8554  8554 D Mms/Contact: [start]    init() consume time = 0.408416
03-18 15:47:53.200  8605  8605 W System.err: android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
03-18 15:47:53.200  8554  8554 D Mms/Contact: [end]    init consume time = 6.694875
03-18 15:47:53.200  8605  8605 W System.err: 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.provider.Settings$System.getLong(Settings.java:1669)
03-18 15:47:53.200  8605  8605 W System.err: 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
03-18 15:47:53.200  8605  8605 W System.err: 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:53.200  8605  8605 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5944)
03-18 15:47:53.200  8605  8605 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-18 15:47:53.200  8605  8605 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-18 15:47:53.200  8605  8605 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-18 15:47:53.200  8605  8605 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-18 15:47:53.200  8554  8638 D Mms/DraftCache: [start]    rebuildCache consume time = 1.681875
03-18 15:47:53.200  3982  5471 D TP/MmsSmsProvider: query,matched:13, calling pid = 8554
03-18 15:47:53.200  3982  5471 D TP/MmsSmsProvider: match 13:Elapsed time : 1.179 ms
03-18 15:47:53.205  3982  5179 D TP/MmsSmsProvider: query,matched:12, calling pid = 8554
03-18 15:47:53.205  3508  4000 I ActivityManager: Killing 7331:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
03-18 15:47:53.210  3982  5179 D TP/MmsSmsProvider: match 12:Elapsed time : 3.571 ms
03-18 15:47:53.210  8554  8554 D Mms/TelephonyUtils: getSubI,d from simSlot 0, return Value = -1
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: auto download without roaming -> true
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-18 15:47:53.215  8554  8554 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-18 15:47:53.215  8554  8554 D Mms/TelephonyUtils: getSubId from simSlot 1, return Value = 9223372036854775807
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: auto download without roaming -> true
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: auto download during roaming secondary -> false
03-18 15:47:53.215  8554  8554 D Mms/DownloadManager: mAutoDownload ------> true
03-18 15:47:53.220  8554  8638 D Mms/DraftCache: [end]    rebuildCache consume time = 16.743625
03-18 15:47:53.220  8554  8639 D Mms/Conversation: [start]    init() consume time = 0.861209
03-18 15:47:53.220  8554  8554 D Mms/MmsApp: [end]    onCreate() consume time = 0.84025
03-18 15:47:53.220  3982  4360 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=692]
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
03-18 15:47:53.220  3982  4360 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
03-18 15:47:53.220  8554  8554 D Mms/TelephonyUtils: getSubId from simSlot 0, return Value = -1
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: auto download without roaming -> true
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-18 15:47:53.220  8554  8554 D Mms/DownloadManager: mAutoDownload ------> true
03-18 15:47:53.220  3508  4303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.220  3508  4303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.220  3508  4303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.220  3508  4303 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-18 15:47:53.225  3982  4360 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-18 15:47:53.225  3982  4360 D TP/MmsSmsProvider: need read changed broadcast:false
03-18 15:47:53.235  8640  8640 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.235  8640  8640 I libpersona: KNOX_SDCARD checking this for 10069
03-18 15:47:53.235  8640  8640 E Zygote  : v2
03-18 15:47:53.235  8640  8640 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.235  8640  8640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-18 15:47:53.235  8640  8640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-18 15:47:53.235  8640  8640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.235  3508  4303 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=8640 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:53.240  3508  4303 I ActivityManager: Killing 7952:com.sec.pcw.device/1000 (adj 13): bgCount ##31
03-18 15:47:53.240  8554  8639 D Mms/Conversation: [end]    init consume time = 21.759666
03-18 15:47:53.240  8554  8639 D Mms/MessagingNotification: [start]    init() consume time = 0.064125
03-18 15:47:53.240  3508  3626 I WifiStateMachine: CMD_RSSI_POLL : calculateWifiScore in!
03-18 15:47:53.240  3508  3626 I WifiStateMachine: CMD_RSSI_POLL : calculateWifiScore out!
03-18 15:47:53.240  3508  3626 I WifiStateMachine: CMD_RSSI_POLL : out!
03-18 15:47:53.245  3508  3746 I ActivityManager: Killing 7968:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
03-18 15:47:53.250  3692  3692 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: applyOpen
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: applyOpen
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: applyOpen
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
03-18 15:47:53.250  3692  3692 D StatusBar.NetworkController: applyOpen
03-18 15:47:53.250  8554  8639 D Mms/MessagingNotification: [end]    init consume time = 10.151334
03-18 15:47:53.250  3508  3564 D AutomaticBrightnessController: mCallbacks.updateBrightness()
03-18 15:47:53.250  3508  3564 D DisplayPowerController: getFinalBrightness : 11 -> 11
03-18 15:47:53.250  3508  3564 D DisplayPowerController: animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-18 15:47:53.250  8554  8651 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.062541
03-18 15:47:53.255  8554  8652 D Mms/Synchronizer: [start]    doSync consume time = 1.105084
03-18 15:47:53.255  3982  5471 D TP/MmsSmsProvider: query,matched:0, calling pid = 8554
03-18 15:47:53.255  3982  5471 V TP/MmsSmsProvider: getSimpleConversations entered.
03-18 15:47:53.255  3982  5179 D TP/MmsSmsProvider: update uri: content://mms-sms/db_synchronization
03-18 15:47:53.255  3982  5179 V TP/MmsSmsProvider: syncDBData start
03-18 15:47:53.260  3982  5471 D TP/MmsSmsProvider: match 0:Elapsed time : 1.543 ms
03-18 15:47:53.260  3982  5179 V TP/MmsSmsProvider: syncDBData sms end
03-18 15:47:53.260  3982  3995 D TP/MmsSmsProvider: query,matched:400, calling pid = 8554
03-18 15:47:53.260  3982  5179 V TP/MmsSmsProvider: syncDBData mms end
03-18 15:47:53.260  3982  5179 V TP/MmsSmsProvider: syncDBData end
03-18 15:47:53.260  8554  8652 D Mms/Synchronizer: [end]    doSync consume time = 6.07775
03-18 15:47:53.260  8554  8651 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 1.01275
03-18 15:47:53.260  8640  8640 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.260  8640  8640 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.265  3508  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.265  3508  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.265  3508  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.265  3508  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.270  8640  8640 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
03-18 15:47:53.280  8657  8657 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.280  8657  8657 I libpersona: KNOX_SDCARD checking this for 10082
03-18 15:47:53.280  8657  8657 E Zygote  : v2
03-18 15:47:53.280  8657  8657 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.280  8657  8657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-18 15:47:53.285  3508  3574 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8657 uid=10082 gids={50082, 9997} abi=armeabi-v7a
03-18 15:47:53.285  8657  8657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-18 15:47:53.285  8657  8657 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-18 15:47:53.295  2880  2880 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 659us total 13.708ms
03-18 15:47:53.305  8657  8657 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.305  8657  8657 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.305  3508  4001 I ActivityManager: Killing 7993:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
03-18 15:47:53.310  5253  5253 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
03-18 15:47:53.310  2880  2880 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 690us total 11.555ms
03-18 15:47:53.310  3508  3990 I ActivityManager: Killing 8012:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
03-18 15:47:53.310  5253  5253 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
03-18 15:47:53.310  3508  4057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.310  3508  4057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.310  3508  4057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.310  3508  4057 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.315  8657  8657 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
03-18 15:47:53.320  8640  8674 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
03-18 15:47:53.320  2880  2880 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 900us total 10.765ms
03-18 15:47:53.320  8060  8076 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
03-18 15:47:53.325  8657  8657 D BadgeProvider: onCreate
03-18 15:47:53.325  8657  8657 D BadgeProvider: DatabaseHelper
03-18 15:47:53.330  8675  8675 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.330  8675  8675 E Zygote  : v2
03-18 15:47:53.330  8675  8675 I libpersona: KNOX_SDCARD checking this for 10094
03-18 15:47:53.330  8675  8675 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.335  8675  8675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-18 15:47:53.335  8675  8675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-18 15:47:53.335  3508  4057 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=8675 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:53.335  8675  8675 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.350  8675  8675 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.350  8675  8675 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.350  8554  8639 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
03-18 15:47:53.365  8675  8675 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:53.365  8675  8675 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-18 15:47:53.380  6258  6309 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llllllIllIlIlllIIlIl)] waits 11 sec
03-18 15:47:53.380  6258  6309 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-18 15:47:53.380  6258  6309 I DBG_DM  : [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
03-18 15:47:53.385  6258  6309 I DBG_DM  : [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
03-18 15:47:53.385  6258  6309 I DBG_DM  : [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
03-18 15:47:53.400  6258  6309 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-18 15:47:53.405  6258  6309 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
03-18 15:47:53.410  6258  6309 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
03-18 15:47:53.410  6258  6309 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
03-18 15:47:53.415  6258  6309 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
03-18 15:47:53.415  6258  6309 I DBG_DM  : [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
03-18 15:47:53.415  6258  6310 I DBG_DM  : [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
03-18 15:47:53.420  6258  6309 I DBG_DM  : [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
03-18 15:47:53.420  6258  6309 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
03-18 15:47:53.420  6258  6258 I DBG_DM  : [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
03-18 15:47:53.420  6258  6309 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
03-18 15:47:53.425  6258  6258 I DBG_DM  : [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.android.launcher2.Launcher
03-18 15:47:53.425  6258  6258 I DBG_DM  : [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
03-18 15:47:53.425  8511  8533 E MTPJNIInterface: Status for mount/Unmount :removed
03-18 15:47:53.425  8511  8533 E MTPJNIInterface: SDcard is not available
03-18 15:47:53.435  6258  6258 I DBG_DM  : [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
03-18 15:47:53.435  6258  6258 I DBG_DM  : [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
03-18 15:47:53.435  6258  6310 I DBG_DM  : [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-18 15:47:53.435  6258  6258 E DBG_DM  : [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
03-18 15:47:53.435  6258  6258 E DBG_DM  : [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3973ad5f
03-18 15:47:53.440  3508  4001 D SettingsProvider: name = next_alarm_formatted
03-18 15:47:53.440  3508  4001 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:53.440  3508  4001 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:53.440  3508  4001 D SettingsProvider: selectionArgs: false
03-18 15:47:53.440  3508  4001 D SettingsProvider: selectionArgs: 10094
03-18 15:47:53.440  3508  4001 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:53.440  3508  4001 D SettingsProvider: ret = -1
03-18 15:47:53.440  6258  6310 I DBG_DM  : [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : true
03-18 15:47:53.440  3508  3564 D AutomaticBrightnessController: mCallbacks.updateBrightness()
03-18 15:47:53.440  3508  3564 D DisplayPowerController: getFinalBrightness : 11 -> 11
03-18 15:47:53.440  3508  3564 D DisplayPowerController: animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-18 15:47:53.440  6258  6258 I DBG_DM  : [com.wssyncmldm.XDMService(919/IIIIllIlIIlIIIIlllIl)] UI_id:223
03-18 15:47:53.440  8511  8533 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
03-18 15:47:53.445  6258  6258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.IIIIllIlIIlIIIIlllIl:925 com.wssyncmldm.XDMService.IllIlIIIIlIIlIIIllIl:75 com.wssyncmldm.IIIIllIlIIlIIIIlllIl.handleMessage:1256 
03-18 15:47:53.445  6258  6258 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:36560
03-18 15:47:53.445  6258  6258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.IIIIllIlIIlIIIIlllIl:925 com.wssyncmldm.XDMService.IllIlIIIIlIIlIIIllIl:75 
03-18 15:47:53.445  3508  6790 E PersonaManagerService: inState():  stateMachine is null !!
03-18 15:47:53.445  3508  6790 I PersonaManagerService: PersonaId don't exist
03-18 15:47:53.445  3508  6790 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-18 15:47:53.455  8511  8533 E MTPJNIInterface: Status for mount/Unmount :removed
03-18 15:47:53.455  8511  8533 E MTPJNIInterface: SDcard is not available
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) API call with NULL database connection pointer
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) misuse at line 105958 of [9491ba7d73]
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) API call with NULL database connection pointer
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) misuse at line 100622 of [9491ba7d73]
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) API call with NULL database connection pointer
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) misuse at line 100622 of [9491ba7d73]
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) API call with NULL database connection pointer
03-18 15:47:53.455  8511  8533 E SQLiteLog: (21) misuse at line 105958 of [9491ba7d73]
03-18 15:47:53.455  8511  8511 W MTPRx   : notification from stack 2
03-18 15:47:53.455  3508  6790 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-18 15:47:53.455  3508  6790 I ActivityManager: START u0 {act=223 flg=0x14000000 cmp=com.wssyncmldm/.ui.XUIDialogActivity} from uid 1000 on display 0
03-18 15:47:53.455  8511  8690 D         : [mtp_init_device] Library open with 32 bits.
03-18 15:47:53.455  8511  8690 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-18 15:47:53.455  8511  8690 E         : [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
03-18 15:47:53.455  3508  6790 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
03-18 15:47:53.455  8511  8690 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-18 15:47:53.455  8511  8690 E         :  [sua_support_present:1277] returning false 
03-18 15:47:53.455  8511  8690 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
03-18 15:47:53.460  3508  6790 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3508  pkgName : ACTIVITY_RESUME_BOOSTER@2
03-18 15:47:53.465  3508  4054 I art     : Explicit concurrent mark sweep GC freed 41057(2MB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 49MB/65MB, paused 5.971ms total 108.222ms
03-18 15:47:53.465  3982  5471 D TP/SmsProvider: query,matched:26, calling pid = 8554
03-18 15:47:53.465  3508  6790 W ActivityManager: mDVFSHelper.acquire()
03-18 15:47:53.465  3508  6790 D FocusedStackFrame: Set to : 0
03-18 15:47:53.465  3982  5471 D TP/SmsProvider: match 26:Elapsed time : 1.389 ms

```
