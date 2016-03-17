#### Test 62509094b685d58_thali03_samsung-SM-N910C Logs


```
--------- beginning of main
03-17 12:28:22.007  8640  8640 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.007  8640  8640 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.017  8640  8640 D ResourcesManager: creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive(): intent.getExtras() is not null
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive() USB CONNECTED
03-17 12:28:22.042  8640  8640 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Exit 
03-17 12:28:22.047  8640  8659 D TMNetworkReceiver: TMNetworkReceiver.onReceive() UsbCheck Thread Enter
03-17 12:28:22.047  8640  8640 D TMSLogRemovalReceiver: TMLogRemovalReceiver.onReceive() Enter isCalled =false
03-17 12:28:22.047  8640  8640 D TMSLogRemovalReceiver: TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
03-17 12:28:22.047  8640  8640 D TMSLogRemovalReceiver: TMLogRemovalReceiver.onReceive() Exit
--------- beginning of system
03-17 12:28:22.047  3515  4205 I ActivityManager: Killing 8153:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
03-17 12:28:22.052  4641  4641 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
03-17 12:28:22.072  8622  8622 D BluetoothNotiBroadcastReceiver: onReceive
03-17 12:28:22.082  4641  4641 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
03-17 12:28:22.082  3515  4187 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.082  3515  4187 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.082  3515  4187 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.082  3515  4187 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.092  8663  8663 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.092  8663  8663 E Zygote  : v2
03-17 12:28:22.092  8663  8663 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:28:22.092  8663  8663 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.097  8663  8663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-17 12:28:22.097  8663  8663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-17 12:28:22.097  3515  4187 I ActivityManager: Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=8663 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 12:28:22.097  8663  8663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:28:22.112  8663  8663 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.112  8663  8663 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.117  3515  3564 D AutomaticBrightnessController: mCallbacks.updateBrightness()
03-17 12:28:22.117  3515  3564 D DisplayPowerController: getFinalBrightness : 11 -> 11
03-17 12:28:22.117  3515  3564 D DisplayPowerController: animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 12:28:22.122  8663  8663 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DeviceTest/DeviceTest.apk
03-17 12:28:22.122  8663  8663 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 12:28:22.132  8663  8663 D FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](8663) onReceive action=android.intent.action.SECPHONE_READY
03-17 12:28:22.132  8663  8663 I FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](8663) android.intent.action.SECPHONE_READY
03-17 12:28:22.137  8663  8663 D FactoryTest: User mode
03-17 12:28:22.137  8109  8109 I KLMS-2.4.521: : KLMSAbstractReciever(): onReceive(): Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.listner.ContainerReceiver (has extras) } | timestamp: Thu Mar 17 12:28:22 GMT+01:00 2016
03-17 12:28:22.142  8109  8109 I KLMS-2.4.521: : KLMSAbstractReciever(): onReceive().END.
03-17 12:28:22.147  8109  8109 I KLMS-2.4.521: : KLMSIntentService(): onCreate()
03-17 12:28:22.147  8109  8109 I KLMS-2.4.521: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 12:28:22.147  8109  8109 I KLMS-2.4.521: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 12:28:22.147  8109  8678 I KLMS-2.4.521: : KLMSIntentService(): onHandleIntent().START: Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 12:28:22.152  3515  3569 D PackageManager: [MSG] SEND_PENDING_BROADCAST
03-17 12:28:22.152  8109  8678 I KLMS-2.4.521: : KLMSIntentService(): RP_MODE_NOTIFY
03-17 12:28:22.152  7198  8679 E SQLiteLog: (284) automatic index on view_events(_id)
03-17 12:28:22.157  8109  8678 I KLMS-2.4.521: : B2C-ContainerStateImpl(): uploadRPMode().Start.
03-17 12:28:22.157  3515  3515 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
03-17 12:28:22.162  8109  8678 I KLMS-2.4.521: : B2C-ContainerStateImpl(): checkKNOXLicenseStatus().No activation record is found when container license check came.
03-17 12:28:22.167  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.167  3515  3562 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
03-17 12:28:22.167  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.167  3515  3600 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 12:28:22.172  4002  4072 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
03-17 12:28:22.172  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.172  3515  3553 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-17 12:28:22.177  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.177  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.177  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.177  8560  8560 I LocationWidgetApplication: Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.gms
03-17 12:28:22.177  4862  4862 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
03-17 12:28:22.177  3515  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.177  3515  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.177  3515  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.177  3515  4206 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.187  7198  8679 D CalendarAlarmManager: sys current time:1458214102158
03-17 12:28:22.187  7198  8679 D CalendarAlarmManager: reminder amount:0
03-17 12:28:22.192  8684  8684 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.192  8684  8684 I libpersona: KNOX_SDCARD checking this for 10160
03-17 12:28:22.192  8684  8684 E Zygote  : v2
03-17 12:28:22.192  8684  8684 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.192  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
03-17 12:28:22.192  8684  8684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-17 12:28:22.197  8684  8684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-17 12:28:22.197  8684  8684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.197  3515  4206 I ActivityManager: Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.control.ui.quickmemo.receiver.PenGestureReceiver: pid=8684 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
03-17 12:28:22.202  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.207  3515  3515 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-17 12:28:22.207  3515  3515 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-17 12:28:22.207  3515  3515 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-17 12:28:22.212  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.212  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.212  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.212  5140  5178 W ResourceType: For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
03-17 12:28:22.212  5140  5178 W ResourceType: Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
03-17 12:28:22.217  3964  3964 D RegisteredServicesCache: empty dynamic service
03-17 12:28:22.217  3515  3515 D TimaService: BroadcastReceiver - action:  com.samsung.action.knox.klms.KLMS_RP_NOTIFICATION
03-17 12:28:22.217  3515  3515 D TimaService: handleLicenseStatus - notiTrigger: 3, licenseStatus: false
03-17 12:28:22.217  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.217  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
03-17 12:28:22.222  8109  8109 I KLMS-2.4.521: : KLMSIntentService(): onDestroy()
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.222  3515  3515 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 12:28:22.222  3515  3515 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 12:28:22.222  3515  3515 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 12:28:22.222  3515  3515 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
03-17 12:28:22.222  3515  3515 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: device_id = 0x0
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: tlc_open() was called
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: Opening MobiCore device
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 12:28:22.222  3515  4187 I ActivityManager: Killing 8170:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: Allocating WSM for TCI
03-17 12:28:22.222  3515  3515 I TZ: mc_tlc_communication: Opening the session
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.222  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 12:28:22.227  8684  8684 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.227  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.227  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 12:28:22.227  8684  8684 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.227  3515  3553 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:28:22.232  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
03-17 12:28:22.237  3515  3515 I TZ: mc_tlc_communication: tlc_open() succeeded
03-17 12:28:22.237  3515  3515 I TLC_TZ_KEYSTORE: : ctx = 0x9affec70, comm = 0x9c565f40, sendmsg = 0xb4ec7e00, recvmsg = 0xb4ec8240
03-17 12:28:22.237  3515  3515 I TZ_init: : TZ_init: sending initialization request...
03-17 12:28:22.242  3515  3515 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-17 12:28:22.242  3515  3515 E TZ_init: : trustlet initialization failed
03-17 12:28:22.247  3515  3515 I TZ_init: : TZ_init_START...
03-17 12:28:22.247  3515  3515 I TZ_init: : TZ_init_with_data: sending initialization request...
03-17 12:28:22.252  3515  5353 I System.out: AsyncTask #4 calls detatch()
03-17 12:28:22.252  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
03-17 12:28:22.252  3515  5353 W System.err: java.io.IOException: Not Found
03-17 12:28:22.257  3515  5353 W System.err: 	at a.d.b(Unknown Source)
03-17 12:28:22.257  3515  5353 W System.err: 	at a.d.doInBackground(Unknown Source)
03-17 12:28:22.257  3515  5353 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 12:28:22.257  3515  5353 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:28:22.257  3515  5353 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 12:28:22.257  3515  5353 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:28:22.257  3515  5353 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:28:22.257  3515  5353 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 12:28:22.257  8684  8684 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
03-17 12:28:22.257  3515  3515 I TZ_init: : TZ_init: successful initialization
03-17 12:28:22.257  3515  3515 I TZ: mc_tlc_communication: tlc_close() was called
03-17 12:28:22.257  3515  3515 I TZ: mc_tlc_communication: Closing the session
03-17 12:28:22.257  8684  8684 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 12:28:22.257  8684  8684 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:22.262  8684  8684 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-17 12:28:22.262  3515  3515 I TZ: mc_tlc_communication: Freeing message buffer
03-17 12:28:22.262  3515  3515 I TZ: mc_tlc_communication: Closing MobiCore device
03-17 12:28:22.267  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: tlc_close() succeeded
03-17 12:28:22.272  3515  3515 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
03-17 12:28:22.272  3515  3515 I TLC_TZ_KEYSTORE: : TZ_KEYSTORE_set_license_status
03-17 12:28:22.272  3515  3515 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 12:28:22.272  3515  3515 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 12:28:22.272  3515  3515 I TLC_TZ_KEYSTORE: : root = 0, root_strlen = 1
03-17 12:28:22.272  3515  3515 I TLC_TZ_KEYSTORE: : process = ffffffff000000000000000000000013, process_strlen = 32
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: input max_sendmsg_size = 1080
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: input max_recvmsg_size = 1080
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: process = ffffffff000000000000000000000013, process_strlen = 32
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 1088
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 1088
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: device_id = 0x0
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: tlc_open() was called
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: Opening MobiCore device
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: Allocating WSM for TCI
03-17 12:28:22.272  3515  3515 I TZ: mc_tlc_communication: Opening the session
03-17 12:28:22.282  3515  3515 I TZ: mc_tlc_communication: tlc_open() succeeded
03-17 12:28:22.282  3515  3515 I TLC_TZ_KEYSTORE: : ctx = 0x9affec70, comm = 0x9c565f40, sendmsg = 0xb4ec7e00, recvmsg = 0xb4ec8240
03-17 12:28:22.282  3515  3515 I TLC_TZ_KEYSTORE: set_license_status: : TZ_KEYSTORE_set_license_status_START
03-17 12:28:22.287  3515  3515 I TLC_TZ_KEYSTORE: set_license_status: : TZ_KEYSTORE_set_license_status_END
03-17 12:28:22.287  3515  3515 I TZ: mc_tlc_communication: tlc_close() was called
03-17 12:28:22.287  3515  3515 I TZ: mc_tlc_communication: Closing the session
03-17 12:28:22.287  4641  4641 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-17 12:28:22.292  3515  3515 I TZ: mc_tlc_communication: Freeing message buffer
03-17 12:28:22.292  3515  3515 I TZ: mc_tlc_communication: Closing MobiCore device
03-17 12:28:22.292  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
03-17 12:28:22.302  3515  3515 I TZ: mc_tlc_communication: tlc_close() succeeded
03-17 12:28:22.302  3515  3515 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-17 12:28:22.302  3515  3515 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2702a1d1
03-17 12:28:22.302  3515  3714 D SettingsProvider: name = assisted_gps_enabled
03-17 12:28:22.302  3515  3714 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:28:22.302  3515  3714 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:28:22.302  3515  3714 D SettingsProvider: selectionArgs: false
03-17 12:28:22.302  3515  3714 D SettingsProvider: selectionArgs: 10014
03-17 12:28:22.302  3515  3714 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:28:22.302  3515  3714 D SettingsProvider: ret = -1
03-17 12:28:22.307  3515  4026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 12:28:22.307  3515  4026 D SecContentProvider2: mCursor = null
03-17 12:28:22.307  3515  3564 D AutomaticBrightnessController: mCallbacks.updateBrightness()
03-17 12:28:22.307  3515  3564 D DisplayPowerController: getFinalBrightness : 11 -> 11
03-17 12:28:22.307  3515  3564 D DisplayPowerController: animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 12:28:22.312  3515  3553 D LocationProviderProxy: applying state to connected service
03-17 12:28:22.322  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
03-17 12:28:22.327  3515  3553 D LocationProviderProxy: applying state to connected service
03-17 12:28:22.327  8684  8684 V Common  : getScreenSize 1440 2560
03-17 12:28:22.332  3515  3594 V AlarmManager: waitForAlarm result :4
03-17 12:28:22.332  3515  7196 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.332  3515  7196 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.332  3515  7196 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.332  3515  7196 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.332  4002  4002 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
03-17 12:28:22.337  4002  4002 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
03-17 12:28:22.347  8705  8705 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.347  8705  8705 E Zygote  : v2
03-17 12:28:22.347  8705  8705 I libpersona: KNOX_SDCARD checking this for 10160
03-17 12:28:22.347  8705  8705 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.347  8705  8705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-17 12:28:22.347  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
03-17 12:28:22.352  3515  7196 I ActivityManager: Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=8705 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
03-17 12:28:22.352  8705  8705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-17 12:28:22.352  8705  8705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.352  8680  8680 D AndroidRuntime: 
03-17 12:28:22.352  8680  8680 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:28:22.357  8680  8680 D AndroidRuntime: CheckJNI is OFF
03-17 12:28:22.357  8680  8680 D AndroidRuntime: readGMSProperty: start
03-17 12:28:22.357  8680  8680 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:28:22.357  8680  8680 D AndroidRuntime: readGMSProperty: end
03-17 12:28:22.357  8680  8680 D AndroidRuntime: addProductProperty: start
03-17 12:28:22.357  8684  8684 I JAM     : Load The ApaService JNI
03-17 12:28:22.357  8684  8684 I JAM     : version: ProfessionalAudio_v1.0.b5
03-17 12:28:22.357  8684  8684 I JAM     : Try v1.0.b3 ...
03-17 12:28:22.357  8684  8684 D Spen    : SpenSdk version level = 55
03-17 12:28:22.357  8684  8684 D Spen    : SpenSdk jar version = 3.0.243
03-17 12:28:22.362  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
03-17 12:28:22.362  8684  8684 D Spen    : SpenSdk apk version = 3.0.235
03-17 12:28:22.362  8684  8684 D Spen    : Server UPDATE Check
03-17 12:28:22.362  8684  8684 W linker  : libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
03-17 12:28:22.362  8684  8684 D SPenError: JNI_OnLoad
03-17 12:28:22.362  8684  8684 D JNI_Bitmap: Init .. Done
03-17 12:28:22.362  8684  8684 D SPenSpiDecoder: JNI_OnLoad .. Done
03-17 12:28:22.362  8684  8684 D SPenError: JNI_OnLoad Success
03-17 12:28:22.362  8684  8684 D PluginManager: Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
03-17 12:28:22.362  8684  8684 D PluginManager: Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
03-17 12:28:22.367  8684  8684 D Init_SPenSdk_Jni: JNI_OnLoad
03-17 12:28:22.367  8684  8684 D Init_SPenSdk_Jni: AndroidSDK: 21
03-17 12:28:22.367  8684  8684 D Init_SPenSdk_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8705  8705 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.372  8705  8705 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.372  8684  8684 D Model_ObjectBase_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8684  8684 D Model_ObjectStroke_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8684  8684 D Model_ObjectImage_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
03-17 12:28:22.372  8684  8684 D Model_ObjectText_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8684  8684 D Model_ObjectContainer_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8684  8684 D Model_PageDoc_Jni: JNI_OnLoad .. Done
03-17 12:28:22.372  8684  8684 D Model_NoteDoc_Jni: check build type eng[0]
03-17 12:28:22.372  8560  8683 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 12:28:22.372  8684  8684 D Model_NoteDoc_Jni: JNI_OnLoad .. Done
03-17 12:28:22.377  8684  8684 D Model_NoteFile_Jni: JNI_OnLoad .. Done
03-17 12:28:22.377  8684  8684 D Model_ObjectUtil_Jni: JNI_OnLoad .. Done
03-17 12:28:22.377  8684  8684 D Model   : OnLoad class Done
03-17 12:28:22.382  8684  8684 D spe_log : SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
03-17 12:28:22.382  8684  8684 D SPen_Library: Draw Engine JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: Canvas JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: Canvas JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: TextView JNI_OnLoad enter!!
03-17 12:28:22.382  8705  8705 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
03-17 12:28:22.382  8684  8684 D SPen_Library: TextView JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: Text JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: Text JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: FontManager JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: FontManager JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: CapturePage JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: CapturePage JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: Multi JNI_OnLoad enter!!
03-17 12:28:22.382  8684  8684 D SPen_Library: Multi JNI_OnLoad Success
03-17 12:28:22.382  8684  8684 D SPen_Library: Draw Engine JNI_OnLoad Success
03-17 12:28:22.387  8684  8684 D SPen_Library: Brush JNI_OnLoad enter!!
03-17 12:28:22.387  8705  8705 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 12:28:22.387  8705  8705 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:22.387  8705  8705 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-17 12:28:22.387  8684  8684 D SPen_Library: Brush JNI_OnLoad Success
03-17 12:28:22.387  8684  8684 D SPen_Library: ChineseBrush JNI_OnLoad enter!!
03-17 12:28:22.387  8684  8684 D SPen_Library: ChineseBrush JNI_OnLoad Success
03-17 12:28:22.387  8684  8684 D SPen_Library: InkPen JNI_OnLoad enter!!
03-17 12:28:22.392  8684  8684 D SPen_Library: InkPen JNI_OnLoad Success
03-17 12:28:22.392  8684  8684 D SPen_Library: Marker JNI_OnLoad enter!!
03-17 12:28:22.392  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
03-17 12:28:22.392  8684  8684 D SPen_Library: Marker JNI_OnLoad Success
03-17 12:28:22.392  8684  8684 D SPen_Library: Pencil JNI_OnLoad enter!!
03-17 12:28:22.392  8684  8684 D SPen_Library: Pencil JNI_OnLoad Success
03-17 12:28:22.392  8684  8684 D SPen_Library: NativePen JNI_OnLoad enter!!
03-17 12:28:22.397  8684  8684 D SPen_Library: NativePen JNI_OnLoad Success
03-17 12:28:22.397  8684  8684 D SPen_Library: MontblancFountainPen JNI_OnLoad enter!!
03-17 12:28:22.397  8684  8684 D SPen_Library: MontblancFountainPen JNI_OnLoad Success
03-17 12:28:22.397  8684  8684 D SPen_Library: MontblancCalligraphyPen JNI_OnLoad enter!!
03-17 12:28:22.397  8684  8684 D SPen_Library: MontblancCalligraphyPen JNI_OnLoad Success
03-17 12:28:22.402  8684  8684 D SPen_Library: MagicPen JNI_OnLoad enter!!
03-17 12:28:22.402  8684  8684 D SPen_Library: MagicPen JNI_OnLoad Success
03-17 12:28:22.402  8684  8684 D SPen_Library: ObliquePen JNI_OnLoad enter!!
03-17 12:28:22.402  8684  8684 D SPen_Library: ObliquePen JNI_OnLoad Success
03-17 12:28:22.402  8684  8684 D SPen_Library: FountainPen JNI_OnLoad enter!!
03-17 12:28:22.402  8684  8684 D SPen_Library: FountainPen JNI_OnLoad Success
03-17 12:28:22.402  8684  8684 D Spen    : SpenSdk Libraries are loaded.
03-17 12:28:22.402  8684  8684 D Init_SPenSdk_Jni: SPenSdk_init2
03-17 12:28:22.402  8684  8684 D Init_SPenSdk: Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
03-17 12:28:22.407  8684  8684 D Init_SPenSdk: Total S Pen SDK Directory Size = 0
03-17 12:28:22.407  8684  8684 D Spen    : initialize complete
03-17 12:28:22.407  8684  8684 W linker  : libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
03-17 12:28:22.412  8684  8684 D QuickSNote: PenGestureReceiver onReceive - Pen Insert Action : true.
03-17 12:28:22.422  8684  8684 D QuickSNote: PenGestureReceiver onReceive - PenInsert recieved.
03-17 12:28:22.422  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
03-17 12:28:22.427  3515  4189 I ActivityManager: Killing 8201:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
03-17 12:28:22.427  3515  4189 I ActivityManager: Killing 8185:com.android.chrome/u0a90 (adj 13): bgCount ##32
03-17 12:28:22.432  8705  8705 D SNoteProvider: onCreate enableSnoteSync = true
03-17 12:28:22.432  4862  4862 I PageBuddyNotiSvc: Intent received : action=com.samsung.pen.INSERT
03-17 12:28:22.437  4862  4862 I PageBuddyNotiSvc: service running
03-17 12:28:22.437  3515  3621 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.437  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
03-17 12:28:22.437  3515  3621 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.437  3515  3621 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.437  3515  3621 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.437  3515  5856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 12:28:22.447  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
03-17 12:28:22.447  8560  8683 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:28:22.447  8560  8683 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:28:22.447  8560  8683 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:28:22.447  8560  8683 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-17 12:28:22.452  8730  8730 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.452  8730  8730 I libpersona: KNOX_SDCARD checking this for 10161
03-17 12:28:22.452  8730  8730 E Zygote  : v2
03-17 12:28:22.452  8730  8730 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.452  8730  8730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-17 12:28:22.452  8730  8730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-17 12:28:22.452  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
03-17 12:28:22.452  3515  3621 I ActivityManager: Start proc com.sec.android.app.SPenKeeper for broadcast com.sec.android.app.SPenKeeper/.SPenKeeperReceiver: pid=8730 uid=10161 gids={50161, 9997, 1028} abi=armeabi-v7a
03-17 12:28:22.452  8730  8730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.457  8705  8713 D SNoteProvider: ===query=== 
03-17 12:28:22.467  8680  8680 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:28:22.467  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
03-17 12:28:22.467  8730  8730 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:28:22.467  8730  8730 D ActivityThread: Added TimaKeyStore provider
03-17 12:28:22.467  8705  8705 V Common  : getScreenSize 1440 2560
03-17 12:28:22.477  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
03-17 12:28:22.482  8730  8730 D ResourcesManager: creating new AssetManager and set to /system/app/SPenKeeper/SPenKeeper.apk
03-17 12:28:22.487  8705  8713 D SNoteProvider: ===query=== 
03-17 12:28:22.487  8680  8680 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:28:22.492  3515  3564 D AutomaticBrightnessController: mCallbacks.updateBrightness()
03-17 12:28:22.492  3515  3564 D DisplayPowerController: getFinalBrightness : 11 -> 11
03-17 12:28:22.492  3515  3564 D DisplayPowerController: animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 12:28:22.497  8602  8631 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 12:28:22.497  8602  8631 E MTPJNIInterface: SDcard is not available
03-17 12:28:22.507  3515  4015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.507  3515  4015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.507  3515  4015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.507  3515  4015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:28:22.507  8560  8683 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
03-17 12:28:22.507  3515  3714 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:28:22.507  3515  3714 I PersonaManagerService: PersonaId don't exist
03-17 12:28:22.507  3515  3714 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:28:22.517  8560  8683 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
03-17 12:28:22.517  8602  8631 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
03-17 12:28:22.517  8748  8748 E Zygote  : MountEmulatedStorage()
03-17 12:28:22.517  8748  8748 E Zygote  : v2
03-17 12:28:22.517  8748  8748 I libpersona: KNOX_SDCARD checking this for 10056
03-17 12:28:22.517  8748  8748 I libpersona: KNOX_SDCARD not a persona
03-17 12:28:22.522  8748  8748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-17 12:28:22.522  8602  8631 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 12:28:22.522  8602  8631 E MTPJNIInterface: SDcard is not available
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) misuse at line 105958 of [9491ba7d73]
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) misuse at line 100622 of [9491ba7d73]
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) misuse at line 100622 of [9491ba7d73]
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:28:22.522  8602  8631 E SQLiteLog: (21) misuse at line 105958 of [9491ba7d73]
03-17 12:28:22.522  8602  8602 W MTPRx   : notification from stack 2
03-17 12:28:22.522  8748  8748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
03-17 12:28:22.522  8748  8748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:28:22.522  8602  8753 D         : [mtp_init_device] Library open with 32 bits.
03-17 12:28:22.522  8602  8753 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-17 12:28:22.522  8602  8753 E         : [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
03-17 12:28:22.522  8602  8753 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 12:28:22.522  8602  8753 E         :  [sua_support_present:1277] returning false 
03-17 12:28:22.522  8602  8753 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
03-17 12:28:22.527  3515  4015 I ActivityManager: Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8748 uid=10056 gids={50056, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
03-17 12:28:22.527  3515  4015 I ActivityManager: Killing 8217:com.google.android.apps.magazines/u0a136 (adj 13): bgCount ##31
03-17 12:28:22.527  8560  8683 D ResourcesManager: creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
03-17 12:28:22.527  3515  3714 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:28:22.527  3515  3714 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 12:28:22.527  3515  3714 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
03-17 12:28:22.537  3515  3714 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3515  pkgName : ACTIVITY_RESUME_BOOSTER@2

```
