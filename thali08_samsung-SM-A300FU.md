#### Test 50388019831b9e1_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 2514): [ModuleCommon$ModuleCommon](2514) Create ModuleCommon
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
D/FactoryTestApp( 2514): [Support$Kernel.read](2514) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2514): [ModuleCommon$readFactoryMode](2514) mode: ON
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2514): [FactoryTestBroadcastReceiver$onReceive](2514) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2514): [Support$Values.getBoolean](2514) id=INBATT_SAVE_SOC, value=false
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2514): [Support$Properties.get](2514) property=ro.factory.factory_binary
D/FactoryTestApp( 2514): [FactoryTestBroadcastReceiver$onReceive](2514) Boot completed, IS_FACTORY_BINARY = USER MODE
I/FactoryTestApp( 2514): [ModuleCommon$getFtClientEnableState](2514) result : false
I/FactoryTestApp( 2514): [ModuleCommon$connectedJIG](2514) ...
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2514): [ModuleCommon$connectedJIG](2514) cable_type = ANYWAY_JIG
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
D/FactoryTestApp( 2514): [Support$Kernel.read](2514) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2514): [ModuleCommon$connectedJIG](2514) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2514): [ModuleCommon$isConnectionModeNone](2514) mConnectionMode = gsm
I/FactoryTestApp( 2514): [ModuleCommon$isRunningFtClient](2514) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2514): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2514) start DummyFtClient service for APO
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
D/FactoryTest( 2514): User mode
I/FactoryTestApp( 2514): [ModuleCommon$disableFtClient](2514) ...
--------- beginning of system
W/ContextImpl( 2514): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:345 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:192 
D/FactoryTestApp( 2514): [DummyFtClient$onCreate](2514) Create DummyFtClient service
I/FactoryTestApp( 2514): [XMLDataStorage$parsingXML](2514) FtClient => data parsing was completed.
D/FactoryTestApp( 2514): [DummyFtClient$onReceive](2514) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2514): [ModuleCommon$isConnectionModeNone](2514) mConnectionMode = gsm
D/FactoryTestApp( 2514): [Support$Values.getBoolean](2514) id=SUPPORT_AUTO_WAKELOCK, value=false
D/FactoryTestApp( 2514): [DummyFtClient$onStartCommand](2514) ...
I/WifiService( 1018): android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2536): MountEmulatedStorage()
E/Zygote  ( 2536): v2
I/libpersona( 2536): KNOX_SDCARD checking this for 1000
I/libpersona( 2536): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2536): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbDeviceManager( 1018): boot completed
D/UsbDeviceManager( 1018): handleMessage -> MSG_BOOT_COMPLETED
D/UsbDeviceManager( 1018): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1018): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
D/UsbDeviceManager( 1018): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
I/KeyguardEffectViewUtil( 1180): set resource id
D/SettingsProvider( 1018): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
D/TimaKeyStoreProvider( 2536): TimaSignature is unavailable
D/ActivityThread( 2536): Added TimaKeyStore provider
E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1018): [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SamsungIME( 1769): showDlgMsgBox : false true true
D/NfcService( 1439): call the applyRouting
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
I/RecoverySystem( 1018): !@RecoverySystem handleAftermath
V/OtaStartupReceiver( 1454): onOtaspChanged: mOtaspMode=1
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/File    ( 2536): fail readDirectory() errno=2
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/RecoverySystem( 1018): No recovery log file
E/Zygote  ( 2559): MountEmulatedStorage()
E/Zygote  ( 2559): v2
I/libpersona( 2559): KNOX_SDCARD checking this for 1001
I/libpersona( 2559): KNOX_SDCARD not a persona
I/SELinux ( 2559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2559 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
I/SELinux ( 2559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1018): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
I/art     (  310): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 34.507ms
D/TimaKeyStoreProvider( 2559): TimaSignature is unavailable
D/ActivityThread( 2559): Added TimaKeyStore provider
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.622ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ResourcesManager( 2559): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.645ms
I/GAV4    ( 2133): Thread[GAThread,5,main]: No campaign data found.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
D/Reset_Reason( 1018): resetString = NPON
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
D/FactoryTestApp( 2514): [ProtectedFactoryTestBroadcastReceiver$onReceive](2514) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2514): [ProtectedFactoryTestBroadcastReceiver$onReceive](2514) com.samsung.intent.action.SECPHONE_READY
D/FactoryTest( 2514): User mode
I/GAv4-SVC( 1865): Google Analytics 8.4.89 is starting up.
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/Mms/NotificationReceiver( 2248): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2248): handleBootCompleted
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Mms/RcsOwnCapsManager( 2248): queue Uri = content://im/queue-messages?box=pending
I/BootReceiver( 1018): Copying audit failures to DropBox
I/BootReceiver( 1018): Checking for fsck errors
I/BootReceiver( 1018): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TP/ImProvider( 1454): im query match24
D/TP/ImProvider( 1454): URI_IM_QUEUED_MESSAGES
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/TP/ImProvider( 1454): ftSesstionId must be a long.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TP/ImProvider( 1454): getQueuedImMessages
D/TP/ImProvider( 1454): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
D/Mms/NotificationReceiver( 2248):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2248): Call to GET_LAST_MESSAGES_SENT
W/ActivityManager( 1018): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/BootReceiver( 1018): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/CrashAnrDetector( 1018): Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 1
D/CrashAnrDetector( 1018): Bootloader: A300FUXXU1BOEC
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '1'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 5708, tid: 6266, name: Thread-979  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d8fdff0
D/CrashAnrDetector( 1018):     r0 703224a8  r1 728378f8  r2 12c0acf0  r3 1332b8e0
D/CrashAnrDetector( 1018):     r4 000000c2  r5 703224a8  r6 728378f8  r7 1332b8e0
D/CrashAnrDetector( 1018):     r8 728378a0  r9 ba652ef8  sl 12c0acf0  fp 9d9ff8a8
D/CrashAnrDetector( 1018):     ip 9d8fdff0  sp 9d8ffff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
D/CrashAnrDetector( 1018):     d0  12c0acf0728378e0  d1  00730020006500b8
D/CrashAnrDetector( 1018):     d2  c0c0c0c0c0c0c032  d3  0102020202020213
D/CrashAnrDetector( 1018):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1018):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1018):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1018):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1018):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1018):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1018):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1018):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1018):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1018):     scr 20000013
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9d8fff70  00000000  
D/CrashAnrDetector( 1018):          9d8fff74  00000000  
D/CrashAnrDetector( 1018):          9d8fff78  00000000  
D/CrashAnrDetector( 1018):          9d8fff7c  00000000  
D/CrashAnrDetector( 1018):          9d8fff80  00000000  
D/CrashAnrDetector( 1018):          9d8fff84  00000000  
D/CrashAnrDetector( 1018):          9d8fff88  00000000  
D/CrashAnrDetector( 1018):          9d8fff8c  00000000  
D/CrashAnrDetector( 1018):          9d8fff90  00000000  
D/CrashAnrDetector( 1018):          9d8fff94  00000000  
D/CrashAnrDetector( 1018):          9d8fff98  00000000  
D/CrashAnrDetector( 1018):          9d8fff9c  00000000  
D/CrashAnrDetector( 1018):          9d8fffa0  00000000  
D/CrashAnrDetector( 1018):          9d8fffa4  00000000  
D/CrashAnrDetector( 1018):          9d8fffa8  00000000  
D/CrashAnrDetector( 1018):          9d8fffac  00000000  
D/CrashAnrDetector( 1018):          9d8fffb0  00000000  
D/CrashAnrDetector( 1018):          9d8fffb4  00000000  
D/CrashAnrDetector( 1018):          9d8fffb8  00000000  
D/CrashAnrDetector( 1018):          9d8fffbc  00000000  
D/CrashAnrDetector( 1018):          9d8fffc0  00000000  
D/CrashAnrDetector( 1018):          9d8fffc4  00000000  
D/CrashAnrDetector( 1018):          9d8fffc8  00000000  
D/CrashAnrDetector( 1018):          9d8fffcc  00000000  
D/CrashAnrDetector( 1018):          9d8fffd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d8fffd4  00000000  
D/CrashAnrDetector( 1018):          9d8fffd8  00000000  
D/CrashAnrDetector( 1018):          9d8fffdc  00000000  
D/CrashAnrDetector( 1018):          9d8fffe0  00000000  
D/CrashAnrDetector( 1018):          9d8fffe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d8fffe8  e3a070ad  
D/CrashAnrDetector( 1018):          9d8fffec  ef9000ad  
D/CrashAnrDetector( 1018):     #00  9d8ffff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9d8ffff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d8ffff4  00000000  
D/CrashAnrDetector( 1018):          9d8ffff8  00000000  
D/CrashAnrDetector( 1018):          9d8ffffc  00000000  
D/CrashAnrDetector( 1018):          9d900000  00000000  
D/CrashAnrDetector( 1018):          9d900004  00000000  
D/CrashAnrDetector( 1018):          9d900008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d90000c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d900010  1332b8e0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d900014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d900018  12c0acf0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d90001c  7541f33d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):          9d900020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d900024  00000000  
D/CrashAnrDetector( 1018):          9d900028  00000000  
D/CrashAnrDetector( 1018):          9d90002c  00000000  
D/CrashAnrDetector( 1018):          9d900030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d900034  00000000  
D/CrashAnrDetector( 1018):          9d900038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d90003c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d900040  1332b8e0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d900044  728
D/CrashAnrDetector( 1018): processName:com.test.thalitest
D/CrashAnrDetector( 1018): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/BootReceiver( 1018): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/SettingsProvider( 1018): name = db_smartlock_supported
D/CrashAnrDetector( 1018): Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 1
D/CrashAnrDetector( 1018): Bootloader: A300FUXXU1BOEC
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '1'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 5627, tid: 6272, name: Thread-956  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d40bff0
D/CrashAnrDetector( 1018):     r0 703224a8  r1 728378f8  r2 12d40cc0  r3 134181a0
D/CrashAnrDetector( 1018):     r4 000000c2  r5 703224a8  r6 728378f8  r7 134181a0
D/CrashAnrDetector( 1018):     r8 728378a0  r9 ba06ac88  sl 12d40cc0  fp 9d50d8a8
D/CrashAnrDetector( 1018):     ip 9d40bff0  sp 9d40dff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
D/CrashAnrDetector( 1018):     d0  12d40cc0728378a0  d1  0073002000650081
D/CrashAnrDetector( 1018):     d2  c0c0c0c0c0c0c041  d3  0102020202020213
D/CrashAnrDetector( 1018):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1018):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1018):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1018):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1018):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1018):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1018):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1018):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1018):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1018):     scr 20000013
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9d40df70  00000000  
D/CrashAnrDetector( 1018):          9d40df74  00000000  
D/CrashAnrDetector( 1018):          9d40df78  00000000  
D/CrashAnrDetector( 1018):          9d40df7c  00000000  
D/CrashAnrDetector( 1018):          9d40df80  00000000  
D/CrashAnrDetector( 1018):          9d40df84  00000000  
D/CrashAnrDetector( 1018):          9d40df88  00000000  
D/CrashAnrDetector( 1018):          9d40df8c  00000000  
D/CrashAnrDetector( 1018):          9d40df90  00000000  
D/CrashAnrDetector( 1018):          9d40df94  00000000  
D/CrashAnrDetector( 1018):          9d40df98  00000000  
D/CrashAnrDetector( 1018):          9d40df9c  00000000  
D/CrashAnrDetector( 1018):          9d40dfa0  00000000  
D/CrashAnrDetector( 1018):          9d40dfa4  00000000  
D/CrashAnrDetector( 1018):          9d40dfa8  00000000  
D/CrashAnrDetector( 1018):          9d40dfac  00000000  
D/CrashAnrDetector( 1018):          9d40dfb0  00000000  
D/CrashAnrDetector( 1018):          9d40dfb4  00000000  
D/CrashAnrDetector( 1018):          9d40dfb8  00000000  
D/CrashAnrDetector( 1018):          9d40dfbc  00000000  
D/CrashAnrDetector( 1018):          9d40dfc0  00000000  
D/CrashAnrDetector( 1018):          9d40dfc4  00000000  
D/CrashAnrDetector( 1018):          9d40dfc8  00000000  
D/CrashAnrDetector( 1018):          9d40dfcc  00000000  
D/CrashAnrDetector( 1018):          9d40dfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40dfd4  00000000  
D/CrashAnrDetector( 1018):          9d40dfd8  00000000  
D/CrashAnrDetector( 1018):          9d40dfdc  00000000  
D/CrashAnrDetector( 1018):          9d40dfe0  00000000  
D/CrashAnrDetector( 1018):          9d40dfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40dfe8  e3a070ad  
D/CrashAnrDetector( 1018):          9d40dfec  ef9000ad  
D/CrashAnrDetector( 1018):     #00  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40dff4  00000000  
D/CrashAnrDetector( 1018):          9d40dff8  00000000  
D/CrashAnrDetector( 1018):          9d40dffc  00000000  
D/CrashAnrDetector( 1018):          9d40e000  00000000  
D/CrashAnrDetector( 1018):          9d40e004  00000000  
D/CrashAnrDetector( 1018):          9d40e008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e010  134181a0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d40e014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e018  12d40cc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d40e01c  7541f33d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):          9d40e020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e024  00000000  
D/CrashAnrDetector( 1018):          9d40e028  00000000  
D/CrashAnrDetector( 1018):          9d40e02c  00000000  
D/CrashAnrDetector( 1018):          9d40e030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e034  00000000  
D/CrashAnrDetector( 1018):          9d40e038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d40e040  134181a0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d40e044  728
D/CrashAnrDetector( 1018): processName:com.test.thalitest
D/CrashAnrDetector( 1018): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/AccessibilityManagerService( 1018): setmDNIeNegative (false)
D/CrashAnrDetector( 1018): Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/CrashAnrDetector( 1018): Hardware: MSM8916
D/CrashAnrDetector( 1018): Revision: 1
D/CrashAnrDetector( 1018): Bootloader: A300FUXXU1BOEC
D/CrashAnrDetector( 1018): Radio: unknown
D/CrashAnrDetector( 1018): Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1018): Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
D/CrashAnrDetector( 1018): Revision: '1'
D/CrashAnrDetector( 1018): ABI: 'arm'
D/CrashAnrDetector( 1018): pid: 5655, tid: 6424, name: Thread-966  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1018): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d209ff0
D/CrashAnrDetector( 1018):     r0 703224a8  r1 728378f8  r2 12c0ba50  r3 133acf40
D/CrashAnrDetector( 1018):     r4 000000c2  r5 703224a8  r6 728378f8  r7 133acf40
D/CrashAnrDetector( 1018):     r8 728378a0  r9 b90e0430  sl 12c0ba50  fp 9d30b8a8
D/CrashAnrDetector( 1018):     ip 9d209ff0  sp 9d20bff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
D/CrashAnrDetector( 1018):     d0  12c0ba5072837840  d1  00730020006500cf
D/CrashAnrDetector( 1018):     d2  c0c0c0c0c0c0c03a  d3  0102020202020213
D/CrashAnrDetector( 1018):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1018):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1018):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1018):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1018):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1018):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1018):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1018):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1018):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1018):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1018):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1018):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1018):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1018):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1018):     scr 20000013
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): backtrace:
D/CrashAnrDetector( 1018):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018): 
D/CrashAnrDetector( 1018): stack:
D/CrashAnrDetector( 1018):          9d20bf70  00000000  
D/CrashAnrDetector( 1018):          9d20bf74  00000000  
D/CrashAnrDetector( 1018):          9d20bf78  00000000  
D/CrashAnrDetector( 1018):          9d20bf7c  00000000  
D/CrashAnrDetector( 1018):          9d20bf80  00000000  
D/CrashAnrDetector( 1018):          9d20bf84  00000000  
D/CrashAnrDetector( 1018):          9d20bf88  00000000  
D/CrashAnrDetector( 1018):          9d20bf8c  00000000  
D/CrashAnrDetector( 1018):          9d20bf90  00000000  
D/CrashAnrDetector( 1018):          9d20bf94  00000000  
D/CrashAnrDetector( 1018):          9d20bf98  00000000  
D/CrashAnrDetector( 1018):          9d20bf9c  00000000  
D/CrashAnrDetector( 1018):          9d20bfa0  00000000  
D/CrashAnrDetector( 1018):          9d20bfa4  00000000  
D/CrashAnrDetector( 1018):          9d20bfa8  00000000  
D/CrashAnrDetector( 1018):          9d20bfac  00000000  
D/CrashAnrDetector( 1018):          9d20bfb0  00000000  
D/CrashAnrDetector( 1018):          9d20bfb4  00000000  
D/CrashAnrDetector( 1018):          9d20bfb8  00000000  
D/CrashAnrDetector( 1018):          9d20bfbc  00000000  
D/CrashAnrDetector( 1018):          9d20bfc0  00000000  
D/CrashAnrDetector( 1018):          9d20bfc4  00000000  
D/CrashAnrDetector( 1018):          9d20bfc8  00000000  
D/CrashAnrDetector( 1018):          9d20bfcc  00000000  
D/CrashAnrDetector( 1018):          9d20bfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20bfd4  00000000  
D/CrashAnrDetector( 1018):          9d20bfd8  00000000  
D/CrashAnrDetector( 1018):          9d20bfdc  00000000  
D/CrashAnrDetector( 1018):          9d20bfe0  00000000  
D/CrashAnrDetector( 1018):          9d20bfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20bfe8  e3a070ad  
D/CrashAnrDetector( 1018):          9d20bfec  ef9000ad  
D/CrashAnrDetector( 1018):     #00  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          ........  ........
D/CrashAnrDetector( 1018):     #01  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20bff4  00000000  
D/CrashAnrDetector( 1018):          9d20bff8  00000000  
D/CrashAnrDetector( 1018):          9d20bffc  00000000  
D/CrashAnrDetector( 1018):          9d20c000  00000000  
D/CrashAnrDetector( 1018):          9d20c004  00000000  
D/CrashAnrDetector( 1018):          9d20c008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c010  133acf40  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d20c014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c018  12c0ba50  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d20c01c  7541f33d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1018):          9d20c020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c024  00000000  
D/CrashAnrDetector( 1018):          9d20c028  00000000  
D/CrashAnrDetector( 1018):          9d20c02c  00000000  
D/CrashAnrDetector( 1018):          9d20c030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c034  00000000  
D/CrashAnrDetector( 1018):          9d20c038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1018):          9d20c040  133acf40  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1018):          9d20c044  728
D/CrashAnrDetector( 1018): processName:com.test.thalitest
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1018): broadcastEvent : null SYSTEM_TOMBSTONE
W/Settings( 1291): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/SettingsProvider( 1018): name = block_emergency_message
D/SettingsProvider( 1018): name = safetycare_geolookout_registering
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/SmartFaceService( 1018): onReceive: android.intent.action.BOOT_COMPLETED
D/SmartFaceIndicator( 1018): no icon
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/SmartFaceService( 1018): mActiveServiceType: 0
E/SmartFaceService( 1018): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1018): updateClientsDone. def. do nothing.
E/SmartFaceService( 1018): Service Type to Worker: 0
E/SmartFaceService( 1018): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1018): Last Smart Pause clients: 0 Current Smart Pause clients: 0
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/AlarmManagerEXT( 1018): mGmsLocationBundling: false
D/RCPManagerService( 1018): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1018):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/RCPManagerService( 1018): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/RCPManagerService( 1018):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
E/USB_UICC(  302): Timeout! No signal received. Retry num = 23
D/EnterpriseDeviceManagerService( 1018): android.intent.action.BOOT_COMPLETED
D/EnterpriseDeviceManagerService( 1018): runAdminUpdate
D/EnterpriseUtils( 1018): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1018): nothing to selfUpdate
V/ApplicationPolicy( 1018): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1018): refresh widget status for user 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
W/PhoneRestrictionPolicy( 1018): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1018): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1018): MSG_REMOVE_ORPHANED_CONTAINERS received
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1018): cvList size 0
W/PhoneRestrictionPolicy( 1018):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1018): cvList size 0
D/WifiP2pService( 1018): P2pDisabledState{ what=143415 }
D/WifiP2pService( 1018): DefaultState{ what=143415 }
D/WIFI_P2P( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI_P2P
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/i       ( 1018): No model
D/ConnectivityService( 1018): Got NetworkFactory Messenger for WIFI
D/Tethering( 1018): Boot complete.
E/WifiStateMachine( 1018): Blacklist file delete
V/EnterpriseBillingEngine( 1018): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1018): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - start - 
D/FactoryTest( 1018): Not factory mode
D/FactoryTest( 1018): Not factory mode. isFactoryMode() returend false
D/w       ( 1018): isUserBuild = true
V/EnterpriseBillingPolicyStorage( 1018): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1018): handleAllprofiles - end
D/UsbHostNotification( 1018): boot completed
D/UsbHostRestrictor( 1018): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1018): initSetUsbBlock STARTED
D/UsbHostRestrictor( 1018): SIM was never inserted
D/UsbHostRestrictor( 1018): writableHostSysNode[false]
D/UsbHostRestrictor( 1018): Can NOT Write Disable Sys Node to [ON]
D/PersonaManagerService( 1018): ACTION_BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1018):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/KnoxKeyguardUpdateMonitor( 1018): onBootComplete
D/UsbStorageNotification( 1018): boot completed
D/StorageNotification( 1180): boot completed
I/KnoxKeyguardUpdateMonitor( 1018): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1018): onTrustChanged user:0, enable:false
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_init 
D/KeyguardViewMediator( 1180): onTrustChanged( Showing = false , userId = 0 )
D/WIFI    ( 1018): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SSRM:n  ( 1018): SIOP:: AP = 370
D/GpsLocationProvider( 1018): set_capabilities_callback: 55u
E/LocSvc_api_v02( 1018): I/locClientOpen:2279]: Service instance id is -1
D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1018): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1018): BOOT_COMPLETED native_cleanup 
D/StatusBarManagerService( 1018): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1180): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1018): qmi_secgps_client_init()
E/Zygote  ( 2606): MountEmulatedStorage()
E/Zygote  ( 2606): v2
I/libpersona( 2606): KNOX_SDCARD checking this for 1000
I/SELinux ( 2606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 2606): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2606 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2606): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1018): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
D/TimaKeyStoreProvider( 2606): TimaSignature is unavailable
D/ActivityThread( 2606): Added TimaKeyStore provider
W/ContextImpl( 2606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
I/splitIntent( 1018): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
I/splitIntent( 1018): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2623): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2623 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 2623): v2
I/libpersona( 2623): KNOX_SDCARD checking this for 10097
I/libpersona( 2623): KNOX_SDCARD not a persona
I/SELinux ( 2623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2623): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2638): MountEmulatedStorage()
E/Zygote  ( 2638): v2
I/libpersona( 2638): KNOX_SDCARD checking this for 10081
I/libpersona( 2638): KNOX_SDCARD not a persona
I/SELinux ( 2638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2638 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2623): TimaSignature is unavailable
D/ActivityThread( 2623): Added TimaKeyStore provider
E/LocSvc_utils_cfg( 1018): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
D/SensorService( 1018): [SO] currT = 29721104000, prevT = 29281041000, diff = 440063000, [-0.383 0.038 9.883]
D/SensorService( 1018): [SO] -0.383 0.038 9.883
D/SensorService( 1018): [SO] [100 -> 255]
,E/Zygote  ( 2649): MountEmulatedStorage()
I/libpersona( 2649): KNOX_SDCARD checking this for 1101
E/Zygote  ( 2649): v2
I/libpersona( 2649): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2649 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
I/SELinux ( 2649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1018): SECGPS: Set AGPS Mode : 7
E/SELinux ( 2649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
D/TimaKeyStoreProvider( 2638): TimaSignature is unavailable
D/ActivityThread( 2638): Added TimaKeyStore provider
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1018): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1018): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1018): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1018): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
D/TimaKeyStoreProvider( 2649): TimaSignature is unavailable
D/ActivityThread( 2649): Added TimaKeyStore provider
W/ResourcesManager( 2649): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1018): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1018): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1018): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
V/SmartcardService( 2649): main Received broadcast
V/SmartcardService( 2649): Starting smartcard service after boot completed
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/CursorWrapperInner( 2248): Cursor finalized without prior close()
D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2674): MountEmulatedStorage()
E/Zygote  ( 2674): v2
I/libpersona( 2674): KNOX_SDCARD checking this for 1000
I/libpersona( 2674): KNOX_SDCARD not a persona
I/SELinux ( 2674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2674 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 2674): TimaSignature is unavailable
D/ActivityThread( 2674): Added TimaKeyStore provider
W/ContextImpl( 2674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2691): MountEmulatedStorage()
I/libpersona( 2691): KNOX_SDCARD checking this for 10153
E/Zygote  ( 2691): v2
I/libpersona( 2691): KNOX_SDCARD not a persona
I/SELinux ( 2691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2691 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/SELinux ( 2691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2691): TimaSignature is unavailable
D/ActivityThread( 2691): Added TimaKeyStore provider
W/ResourcesManager( 2691): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2708): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2708 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 2708): v2
I/ActivityManager( 1018): Killing 1193:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/libpersona( 2708): KNOX_SDCARD checking this for 1000
I/libpersona( 2708): KNOX_SDCARD not a persona
I/SELinux ( 2708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2708): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2708): TimaSignature is unavailable
D/ActivityThread( 2708): Added TimaKeyStore provider
D/SettingsProvider( 1018): name = next_alarm_formatted
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10081
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1193/cgroup.procs: No such file or directory
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2724): MountEmulatedStorage()
I/libpersona( 2724): KNOX_SDCARD checking this for 10155
E/Zygote  ( 2724): v2
I/libpersona( 2724): KNOX_SDCARD not a persona
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
I/SELinux ( 2724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2724 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 1399:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2724): TimaSignature is unavailable
D/ActivityThread( 2724): Added TimaKeyStore provider
E/ActivityThread( 2623): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2623): Failed to find provider info for flipboard.auth.internal
I/ActivityManager( 1018): Killing 1383:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
I/DrmEventReceiver( 1018): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1018): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
W/ResourcesManager( 2724): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/DrmEventReceiver( 1018): DrmEventReceiver : beginStartingService
I/System.out( 1018): start Service
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1454): Update uri=content://mms, match=0
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onInitialize : 1206
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onSetOnInfoListener : add 1206
D/TP/MmsProvider( 1454): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
I/Mms:transaction( 2248): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1399/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2248): [start]    nonBlockingUpdateMessageIndicator() consume time = 2379.511979
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_1383/cgroup.procs: No such file or directory
I/Mms/ReservationManager( 2248): resetAfterConnected()
D/Mms/MessagingNotification( 2248): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2248): isDefault true
D/TP/MmsSmsProvider( 1454): query,matched:7, calling pid = 2248
D/TP/MmsProvider( 1454): Query uri=content://mms, match=0, calling pid = 2248
D/TP/MmsSmsProvider( 1454): match 7:Elapsed time : 3.861 ms
W/art     ( 2638): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 120.203ms
D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
D/TP/MmsSmsProvider( 1454): query,matched:200, calling pid = 2248
I/Mms/ReservationManager( 2248): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1454): match 200:Elapsed time : 2.067 ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/[0]UMC:Core( 2724): onCreate(): 
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2742): MountEmulatedStorage()
E/Zygote  ( 2742): v2
I/libpersona( 2742): KNOX_SDCARD checking this for 10043
I/libpersona( 2742): KNOX_SDCARD not a persona
I/SELinux ( 2742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2742 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 2742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/TimaServiceEventReceiver( 1018): TimaServiceEventReceiver : onReceive
I/DrmEventService( 1018): action event :android.intent.action.BOOT_COMPLETED
E/SELinux ( 2742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ANDROID_DRM_FRWORKS_DrmManager(  283): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
D/TP/SmsProvider( 1454): query,matched:0, calling pid = 2248
D/TP/SmsProvider( 1454): match 0:Elapsed time : 3.617 ms
E/CscReceiver( 1454): onReceive android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2248): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2248): isDefault true
D/Mms/SmsReceiverService( 2248): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/[0]UMC:DeviceInfo( 2724): USA==US==
D/Mms/SmsReceiverService( 2248): [start]    handleBootCompleted() consume time = 69.545208
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TimaKeyStoreProvider( 2742): TimaSignature is unavailable
D/ActivityThread( 2742): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2759): MountEmulatedStorage()
E/Zygote  ( 2759): v2
I/libpersona( 2759): KNOX_SDCARD checking this for 10002
I/libpersona( 2759): KNOX_SDCARD not a persona
D/CscUpdateService( 1454): onStart
E/CscUpdateService( 1454): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1454): set_CSC_version
E/CscParser( 1454): update(): xml file exist
I/SELinux ( 2759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/USB_UICC(  302): Timeout! No signal received. Retry num = 24
I/ActivityManager( 1018): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2759 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 2759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2759): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/CscUtil ( 1454): isWifiOnly = false
I/System.out( 1454): HandDataNode = null
I/CscUpdateService( 1454): PATH_CSCNAME =CustomerDataSet.CSCName
I/CscUpdateService( 1454): This is normal boot : CSC not updated
E/CscParser( 1454): update(): xml file exist
W/ResourcesManager( 2742): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2759): TimaSignature is unavailable
W/ResourcesManager( 2742): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 2759): Added TimaKeyStore provider
W/ResourcesManager( 2742): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/CscGPS  ( 1454): CSCGPS.updateParameters
D/CscGPS  ( 1454): supl host : null
D/CscGPS  ( 1454): SUPL Host is null or invalid
D/CscGPS  ( 1454): supl_ver : null
D/CscGPS  ( 1454): SUPL Ver is null or invalid
D/CscGPS  ( 1454): supl port : null
D/CscGPS  ( 1454): SUPL PORT is null or invalid
D/CscGPS  ( 1454): LPP : null
D/CscGPS  ( 1454): LPP is null or invalid
D/CscGPS  ( 1454): CSC don't have any AGPS value.
D/USER_AGENT( 2724): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 2724): init - start
D/TP/MmsSmsProvider( 1454): getThreadUnReadCount unreadCount=0 imUnreadCount=0
I/CscUpdateService( 1454): same CSC Version
D/CscUtil ( 1454): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/TP/MmsSmsProvider( 1454): deleteConversation threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1454): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1454): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1454): sUpgradeVersion = 0, db.getVersion() = 81
D/[0]UMC:AdminManager( 2724): loadAdmins
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1454): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1454): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
D/Mms/Conversation( 2248): deleteTempConversation(),deleted=0
D/SmsProvider( 1454): Update uri=content://sms/outbox, match=8
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/[0]UMC:AdminManager( 2724): init - end
D/GSLBManager( 2724): migrateStoredUrlFromOldPref
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/Mms/SmsReceiverService( 2248): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2248): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2248): [SIM-1]sendFirstQueuedMessage()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 2724): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2724): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2724): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2724): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2724): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2724): isContainer : 0
D/EnterpriseDeviceManagerService( 1018): isManagedProfileUser(): userId = 0
E/Zygote  ( 2779): MountEmulatedStorage()
E/Zygote  ( 2779): v2
I/libpersona( 2779): KNOX_SDCARD checking this for 1000
I/libpersona( 2779): KNOX_SDCARD not a persona
I/SELinux ( 2779): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2779): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SQLiteLog( 1227): (283) recovered 619 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
I/ActivityManager( 1018): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2779 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 2779): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  310): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 632us total 21.798ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.781ms
I/art     ( 1454): Explicit concurrent mark sweep GC freed 39551(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 956us total 180.022ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.210ms
D/TP/SmsProvider( 1454): query,matched:51, calling pid = 2248
D/TimaKeyStoreProvider( 2779): TimaSignature is unavailable
D/ActivityThread( 2779): Added TimaKeyStore provider
D/TP/SmsProvider( 1454): query,matched:26, calling pid = 2248
E/[0]UMC:UMCAdmin( 2724): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2724): isContainer : 0
D/[0]UMC:UMCAdmin( 2724): deactivateUMCAdmin - UMC App Admin deactivated
D/[0]UMC:CoreReceiver( 2724): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2724):  check PreETag 
D/[0]UMC:ByodSetupStarter( 2724): Container ID : 0
V/[0]UMC:Utils( 2724): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2724): shutdown
I/art     ( 2724): System.exit called, status: 0
I/AndroidRuntime( 2724): VM exiting with result code 0, cleanup skipped.
D/AndroidRuntime( 2670): 
D/AndroidRuntime( 2670): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2670): CheckJNI is OFF
D/AndroidRuntime( 2670): readGMSProperty: start
D/AndroidRuntime( 2670): readGMSProperty: already setted!!
D/AndroidRuntime( 2670): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2670): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2670): readGMSProperty: end
D/AndroidRuntime( 2670): addProductProperty: start
I/ActivityManager( 1018): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2724)(adj 0) has died(33,718)
D/daemonapp( 1737): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1737): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/art     ( 1018): Explicit concurrent mark sweep GC freed 58757(4MB) AllocSpace objects, 84(4MB) LOS objects, 33% free, 21MB/32MB, paused 4.563ms total 182.388ms
D/TP/SmsProvider( 1454): match 51:Elapsed time : 156.074 ms
D/TP/SmsProvider( 1454): match 26:Elapsed time : 159.821 ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/Zygote  ( 2806): MountEmulatedStorage()
E/Zygote  ( 2806): v2
I/libpersona( 2806): KNOX_SDCARD checking this for 1000
I/libpersona( 2806): KNOX_SDCARD not a persona
D/MediaScanner( 1227): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/ActivityManager( 1018): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1737): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1737): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1737): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1737): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1737): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1737): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1737): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1018): name = block_emergency_message
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10043
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/SettingsProvider( 1018): name = aw_daemon_service_key_version_check
W/ActivityManager( 1018): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10157
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Mms/MessagingNotification( 2248): isBlockingModeEnabled() = false, Zen mode = 0
D/Mms/SmsReceiver( 2248): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2248): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2248): isDefault true
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/TimaKeyStoreProvider( 2806): TimaSignature is unavailable
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/ActivityThread( 2806): Added TimaKeyStore provider
D/daemonapp( 1737): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/TP/MmsProvider( 1454): Query uri=content://mms, match=0, calling pid = 2248
D/daemonapp( 1737): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1737): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1737): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/ResourcesManager( 2806): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/daemonapp( 1737): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1737): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1451921634784
D/daemonapp( 1737): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1451943180000
D/daemonapp( 1737): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1737): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/Launcher.Model( 1477): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2248): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2248): remove alarm
D/TP/MmsSmsProvider( 1454): query,matched:200, calling pid = 2248
D/daemonapp( 1737): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1451943180000
D/TP/SmsProvider( 1454): query,matched:0, calling pid = 2248
D/TP/SmsProvider( 1454): match 0:Elapsed time : 1.110 ms
D/TP/MmsSmsProvider( 1454): match 200:Elapsed time : 8.022 ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 22
D/daemonapp( 1737): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1451943180000
E/Zygote  ( 2823): MountEmulatedStorage()
E/Zygote  ( 2823): v2
I/libpersona( 2823): KNOX_SDCARD checking this for 10082
I/libpersona( 2823): KNOX_SDCARD not a persona
I/SELinux ( 2823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2823 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 1524:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
I/SELinux ( 2823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2823): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2248): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 2248): [end]    nonBlockingUpdateMessageIndicator() consume time = 525.052812
E/SQLiteLog( 2779): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/TP/SmsProvider( 1454): query,matched:0, calling pid = 2248
D/TP/SmsProvider( 1454): match 0:Elapsed time : 1.608 ms
D/TimaKeyStoreProvider( 2823): TimaSignature is unavailable
D/ActivityThread( 2823): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/WifiCredService( 1291): onCreate
V/MediaScanner( 1227): processDirectory :  /system/media
D/TP/SmsProvider( 1454): query,matched:51, calling pid = 2248
D/TP/SmsProvider( 1454): match 51:Elapsed time : 4.601 ms
D/WifiTimerReceiver( 1291): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1291): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1291): Action boot completed received
D/DSM     ( 2779): [Lines:107] Normal booted
D/DSM     ( 2779): [Lines:114] Boot completed
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 2841): MountEmulatedStorage()
I/ActivityManager( 1018): Killing 1851:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
E/Zygote  ( 2841): v2
I/libpersona( 2841): KNOX_SDCARD checking this for 1000
I/libpersona( 2841): KNOX_SDCARD not a persona
I/SELinux ( 2841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2248): isBlockingModeEnabled() = false, Zen mode = 0
D/TimaKeyStoreProvider( 2841): TimaSignature is unavailable
D/ActivityThread( 2841): Added TimaKeyStore provider
W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_1524/cgroup.procs: No such file or directory
D/BadgeProvider( 1559): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
W/ResourcesManager( 2841): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/Launcher.Model( 1477): reloadBadges entered.
D/BadgeProvider( 1559): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): sendNotify, [notify] : null
D/BadgeProvider( 1559): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1559): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1559): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2248): setBadgeCount(), count=0
W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_1851/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 2248): remove alarm
D/Mms/MessagingNotification( 2248): updateAllHistoryAsRead()
D/TP/SmsProvider( 1454): query,matched:0, calling pid = 2248
D/TP/SmsProvider( 1454): match 0:Elapsed time : 3.877 ms
D/Mms/SmsReceiverService( 2248): [end]    handleBootCompleted() consume time = 160.131302
W/ActivityThread( 2841): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1018): Killing 2047:com.vlingo.midas/u0a28 (adj 15): empty #31
D/comdaemonstockapp( 1737): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1737): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
E/UpdateRequestReceiver( 2823): ignoring update request
E/UpdateRequestReceiver( 2823): ignoring update request
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
V/MediaScanner( 1227):  prescan time: 598ms (DB items: 138)
V/MediaScanner( 1227):     scan time: 164ms (Caching mode: true), (makeEntry time: 27ms ~16%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 762ms
V/MediaScanner( 1227): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/NearbySettings( 1291): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1291): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1291): MountReceiver.onReceive - Create mPrefHandler
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/NearbySettings( 1291): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
V/NearbySettings( 1291): MountReceiver.mPrefHandler - 7002
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
E/Zygote  ( 2865): MountEmulatedStorage()
E/Zygote  ( 2865): v2
I/libpersona( 2865): KNOX_SDCARD checking this for 10161
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
I/libpersona( 2865): KNOX_SDCARD not a persona
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
I/SELinux ( 2865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
I/SELinux ( 2865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/LcdtestApp( 2841): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
E/SELinux ( 2865): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/UpdateRequestReceiver( 2823): ignoring update request
I/LcdtestApp( 2841): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
I/ActivityManager( 1018): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2865 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2865): TimaSignature is unavailable
D/ActivityThread( 2865): Added TimaKeyStore provider
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
I/NearbySettings( 1291): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1291): MountReceiver.onReceive - Internal Path
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/UpdateRequestReceiver( 2823): ignoring update request
E/AffinityControl( 2670): AffinityControl: registerfunction enter
W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_2047/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2885 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 2885): MountEmulatedStorage()
I/libpersona( 2885): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2885): v2
I/libpersona( 2885): KNOX_SDCARD not a persona
I/SELinux ( 2885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 2074:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
I/SELinux ( 2885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1018): name = personal_mode_enabled
D/FactoryTestApp( 2514): [DummyFtClient$mBroadcastReceiver](2514) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2514): [DummyFtClient$mBroadcastReceiver](2514) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2514): [DummyFtClient$mBroadcastReceiver](2514) ACTION_MEDIA_SCANNER_FINISHED = Ignored
E/UpdateRequestReceiver( 2823): ignoring update request
D/MediaScannerService( 1227): !@done scanning volume internal
D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/TimaKeyStoreProvider( 2885): TimaSignature is unavailable
D/AndroidRuntime( 2670): Calling main entry com.android.commands.am.Am
D/ActivityThread( 2885): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
E/UpdateRequestReceiver( 2823): ignoring update request
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
E/Zygote  ( 2906): MountEmulatedStorage()
E/Zygote  ( 2906): v2
I/libpersona( 2906): KNOX_SDCARD checking this for 10088
I/libpersona( 2906): KNOX_SDCARD not a persona
I/SELinux ( 2906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=2906 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2133:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
I/SELinux ( 2906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2906): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2906): TimaSignature is unavailable
D/ActivityThread( 2906): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10045/pid_2074/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_2133/cgroup.procs: No such file or directory
E/SMD     (  292): DCD OFF
E/USB_UICC(  302): Timeout! No signal received. Retry num = 25
I/DIAGMON_AGENT( 2885): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ResourcesManager( 1454): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1477
D/AndroidRuntime( 2670): Shutting down VM
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
W/ResourcesManager( 2865): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2865): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
V/JNIHelp ( 2865): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 2865): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2865): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20661b6c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2865): Installed default security provider GmsCore_OpenSSL
D/Launcher.HomeView( 1477): onPause
D/Launcher( 1477): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1227): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2929): MountEmulatedStorage()
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD checking this for 10334
I/libpersona( 2929): KNOX_SDCARD not a persona
I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2929 uid=10334 gids={50334, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
E/Zygote  ( 2937): MountEmulatedStorage()
E/Zygote  ( 2937): v2
I/libpersona( 2937): KNOX_SDCARD checking this for 10088
I/libpersona( 2937): KNOX_SDCARD not a persona
I/SELinux ( 2937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2937): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 2885): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=2937 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/art     ( 2670): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/ActivityThread( 1477): updateVisibility : ActivityRecord{3afbb179 token=android.os.BinderProxy@1fcbaf69 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/DIAGMON_AGENT( 2885): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/SmartcardBootCompleteReceiver( 1291): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1291): Received intent with action - android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
D/ActivityThread( 2929): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/ContextImpl( 1291): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher.HomeView( 1477): onStop
V/ActivityThread( 1477): updateVisibility : ActivityRecord{3afbb179 token=android.os.BinderProxy@1fcbaf69 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/TimaKeyStoreProvider( 2937): TimaSignature is unavailable
,D/ActivityThread( 2937): Added TimaKeyStore provider
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
V/MediaScanner( 1227):  prescan time: 209ms (DB items: 26)
V/MediaScanner( 1227):     scan time: 75ms (Caching mode: true), (makeEntry time: 13ms ~17%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 287ms
I/DIAGMON_AGENT( 2885): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
V/MediaScanner( 1227): checked files: 10  directories : 16  (I: 0, U: 0)
I/DIAGMON_AGENT( 2885): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2885): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2885): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SmartcardBootCompleteReceiver( 1291): Broadcast sent with current lockscreen type
,I/iu.UploadsManager( 1865): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/Launcher( 1477): onTrimMemory. Level: 20
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/FactoryTestApp( 2514): [DummyFtClient$mBroadcastReceiver](2514) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2514): [DummyFtClient$mBroadcastReceiver](2514) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2514): [DummyFtClient$sendBootCompletedAndFinish](2514) ...
D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2514): [ModuleCommon$isConnectionModeNone](2514) mConnectionMode = gsm
D/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$ResponseWriter](2514) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$connectToSecPhoneService](2514)  
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/ContextImpl( 2514): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/MediaScannerService( 1227): !@done scanning volume external
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$onServiceConnected](2514) connected done
D/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$write](2514) Send Response Message to SecPhone
D/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$write](2514) Response ��
,D/[SBeam] ( 1291): SBeamEnabler.initPreferenceForSbeam : 0
,D/AT_Distributor(  321): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$handleMessage](2514) Send BOOTING COMPLETED done
,E/Zygote  ( 2969): MountEmulatedStorage()
,E/Zygote  ( 2969): v2
I/ActivityManager( 1018): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=2969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/libpersona( 2969): KNOX_SDCARD checking this for 1000
I/libpersona( 2969): KNOX_SDCARD not a persona
,I/SELinux ( 2969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 2969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 2969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,I/com.dropbox.android.service.DropboxNetworkReceiver( 2906): Setting receiver enabled: false,
I/SettingSearch/SearchIntentReceiver( 1291): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1291): search setting db init!!
,W/ContextImpl( 1291): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SettingSearch/SearchIntentReceiver( 1291): BOOT_COMPLETED call InitSerachDBThread thread start!
,E/ActivityThread( 2906): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/TimaKeyStoreProvider( 2969): TimaSignature is unavailable
,D/ActivityThread( 2969): Added TimaKeyStore provider
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 2865): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1018): [SO] -0.383 0.057 9.883
D/SensorService( 1018): [SO] [100 -> 255]
,E/Zygote  ( 2989): MountEmulatedStorage()
I/libpersona( 2989): KNOX_SDCARD checking this for 10146
E/Zygote  ( 2989): v2
I/libpersona( 2989): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2989 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,D/AT_Distributor(  321): SetAtdStatus(), 1_1_0
D/AT_Distributor(  321): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/SELinux ( 2989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 2989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2989): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2989): TimaSignature is unavailable
D/ActivityThread( 2989): Added TimaKeyStore provider
E/Zygote  ( 3004): MountEmulatedStorage()
E/Zygote  ( 3004): v2
I/libpersona( 3004): KNOX_SDCARD checking this for 1000
I/libpersona( 3004): KNOX_SDCARD not a persona
I/SELinux ( 3004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3004): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 19.547ms
,I/dbxyzptlk.db240408.D.h( 2906): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,D/TimaKeyStoreProvider( 3004): TimaSignature is unavailable
,D/ActivityThread( 3004): Added TimaKeyStore provider
,I/dbxyzptlk.db240408.D.h( 2906): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.021ms
,I/dbxyzptlk.db240408.D.h( 2906): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 16.584ms,
,I/WebViewFactory( 2929): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/iu.UploadsManager( 1865): End new media; added: 0, uploading: 0, time: 282 ms
,W/ResourcesManager( 3004): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/LibraryLoader( 2929): Loading: webviewchromium
,I/LibraryLoader( 2929): Time to load native libraries: 5 ms (timestamps 2037-2042)
I/LibraryLoader( 2929): Expected native library version number "",actual native library version number ""
,I/dbxyzptlk.db240408.D.h( 2906): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/FOTA    ( 3004): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/breakpad( 2906): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,E/Zygote  ( 3029): MountEmulatedStorage()
,E/Zygote  ( 3029): v2
I/libpersona( 3029): KNOX_SDCARD checking this for 10008
I/libpersona( 3029): KNOX_SDCARD not a persona
,I/SELinux ( 3029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3029 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3029): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,D/TimaKeyStoreProvider( 3029): TimaSignature is unavailable
,D/ActivityThread( 3029): Added TimaKeyStore provider
I/DBG_POLICYDM( 2969): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,I/DBG_POLICYDM( 2969): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,V/WebViewChromiumFactoryProvider( 2929): Binding Chromium to main looper Looper (main, tid 1) {1cfb870a}
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
I/LibraryLoader( 2929): Expected native library version number "",actual native library version number ""
,I/chromium( 2929): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/SurfaceFlinger(  258): id=7 Removed Mauncher (-2/8)
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 2969): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/BrowserStartupController( 2929): Initializing chromium process, renderers=0
,W/art     ( 2929): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,W/chromium( 2929): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,I/com.dropbox.sync.android.a( 2906): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,W/chromium( 2929): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 2929): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 2929): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter( 2929): 905558907: getState() :  mService = null. Returning STATE_OFF
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/Adreno-EGL( 2929): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2929): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2929): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2929): Local Branch: 
I/Adreno-EGL( 2929): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2929): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2929):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/com.dropbox.sync.android.ad( 2906): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,I/DBG_DM  ( 3004): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 26
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ContextImpl( 3004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1018): [SO] -0.383 0.057 9.883
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3081 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 3081): MountEmulatedStorage(),
I/libpersona( 3081): KNOX_SDCARD checking this for 10090
E/Zygote  ( 3081): v2
I/libpersona( 3081): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/SELinux ( 3081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
E/SELinux ( 3081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3004): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_POLICYDM( 2969): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 2969): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_DM  ( 3004): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3004): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_POLICYDM( 2969): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_POLICYDM( 2969): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_DM  ( 3004): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
E/DBG_POLICYDM( 2969): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
I/DBG_POLICYDM( 2969): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3004): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1180): isSafeMode = false
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,D/TimaKeyStoreProvider( 3081): TimaSignature is unavailable
,D/ActivityThread( 3081): Added TimaKeyStore provider
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3004): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,D/BootupListener( 1454): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1454): isSupportVoLTE is false.
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,W/chromium( 2929): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,I/DBG_DM  ( 3004): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3004): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,W/chromium( 2929): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/Telecom ( 1430): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/ActivityManager( 1018): Killing 1493:com.android.printspooler/u0a132 (adj 15): empty #31
,E/YouTube MDX( 2865): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/art     ( 2929): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2929): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2929): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2929): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2929): CordovaWebView is running on device made by: samsung
,D/elm:15121( 3081): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3081): ELMEngine.ELMEngine( context ).
,D/elm:15121( 3081): MDMBridge.setEnterpriseBridge()
,I/System.out( 2906): Thread-374(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2906): Thread-374(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 2906): Thread-374(ApacheHTTPLog):isShipBuild true
I/System.out( 2906): Thread-374(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 2906): Thread-374(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10088
,I/System.out( 2906): pool-10-thread-1 calls detatch()
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 17826(934KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 4.068ms total 146.636ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,E/Tethering( 1018): No numeric data
,W/libprocessgroup( 1018): failed to open /acct/uid_10132/pid_1493/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,E/Tethering( 1018): No numeric data
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
E/Tethering( 1018): No numeric data
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3081): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/Tethering( 1018): No numeric data
,W/art     ( 2929): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2929): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 3081): ElmAgentService : onCreate()
E/Tethering( 1018): No numeric data
,D/elm:15121( 3081): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3081): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3081): BootCompletedState : startBootCompleted() call
,E/Tethering( 1018): No numeric data
,E/Zygote  ( 3114): MountEmulatedStorage()
I/libpersona( 3114): KNOX_SDCARD checking this for 10052
E/Zygote  ( 3114): v2
I/libpersona( 3114): KNOX_SDCARD not a persona
,I/SELinux ( 3114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3114 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/elm:15121( 3081): MDMBridge.getAllLicenseInfoFromSDK()
I/Telecom ( 1430): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,E/SELinux ( 3114): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/elm:15121( 3081): Get License : 0
D/elm:15121( 3081): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 1611:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3114): TimaSignature is unavailable
,D/ActivityThread( 3114): Added TimaKeyStore provider
,D/OpenGLRenderer( 2929): Render dirty regions requested: true
,V/EmergencyMode( 1415): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/PhoneWindow( 2929): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2929): *FMB* isFloatingMenuEnabled return false
,I/DBG_DM  ( 3004): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/DBG_DM  ( 3004): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,V/EmergencyMode( 1415): [EmergencyBase] setBootTime
V/EmergencyMode( 1415): [EmergencyFactory] No Recovery State, kill my self.
,D/[SBeam] ( 1291): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1291): SBeamEnabler.isSBeamSupported : EXIST
,E/Zygote  ( 3133): MountEmulatedStorage()
E/Zygote  ( 3133): v2
I/libpersona( 3133): KNOX_SDCARD checking this for 1000
I/libpersona( 3133): KNOX_SDCARD not a persona
I/SELinux ( 3133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3133 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1018): Focus entered window: 2929
,I/ActivityManager( 1018): Killing 2280:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2265:com.sec.tcpdumpservice/1000 (adj 15): empty #32,
I/ActivityManager( 1018): Killing 2233:com.sec.modem.settings/1000 (adj 15): empty #33,
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 2929): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 2929): Initialized EGL, version 1.4,
,D/OpenGLRenderer( 2929): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2929): Enabling debug mode 0
,D/TimaKeyStoreProvider( 3133): TimaSignature is unavailable
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3133): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,E/Zygote  ( 3149): MountEmulatedStorage(),
E/Zygote  ( 3149): v2
I/libpersona( 3149): KNOX_SDCARD checking this for 1000
I/libpersona( 3149): KNOX_SDCARD not a persona,
,I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering( 1018): No numeric data
,D/TimaKeyStoreProvider( 3149): TimaSignature is unavailable
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ActivityThread( 3149): Added TimaKeyStore provider
E/Tethering( 1018): No numeric data
,E/Tethering( 1018): No numeric data
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,I/Timeline( 2929): Timeline: Activity_idle id: android.os.BinderProxy@36c796b time:32903
,I/DBG_DM  ( 3004): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s304ms
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,I/CameraApp( 3149): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3149): Feature.Feature(context)
I/testFeature( 3149): Feature.readInternalDefaultXml()
,I/testFeature( 3149): ResetFeatureValue
,I/CameraFirmware_broadcast( 3149): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3149): CameraApp.getAppFeature()...
,E/Tethering( 1018): No numeric data
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{13e9536f u0 com.example.hello/.MainActivity t2} time:32996
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3004): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3004): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3004): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/Zygote  ( 3178): MountEmulatedStorage()
,E/Zygote  ( 3178): v2
I/libpersona( 3178): KNOX_SDCARD checking this for 10095
I/libpersona( 3178): KNOX_SDCARD not a persona
,I/SELinux ( 3178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3178 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2302:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/SELinux ( 3178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/NotificationAccessSettings( 1291): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_1611/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2265/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2233/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,E/Zygote  ( 3195): MountEmulatedStorage()
,E/Zygote  ( 3195): v2
I/libpersona( 3195): KNOX_SDCARD checking this for 10014
I/libpersona( 3195): KNOX_SDCARD not a persona
,I/SELinux ( 3195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/DBG_FMMDM( 3133): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
W/ResourcesManager( 1291): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/SELinux ( 3195): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3178): TimaSignature is unavailable
D/ActivityThread( 3178): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3195 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,I/DBG_FMMDM( 3133): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_FMMDM( 3133): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,W/libprocessgroup( 1018): failed to open /acct/uid_10127/pid_2280/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2302/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3195): TimaSignature is unavailable
D/ActivityThread( 3195): Added TimaKeyStore provider
,I/DBG_FMMDM( 3133): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2865): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ContextImpl( 2865): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2865): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3212): MountEmulatedStorage()
E/Zygote  ( 3212): v2
I/libpersona( 3212): KNOX_SDCARD checking this for 1000,
I/libpersona( 3212): KNOX_SDCARD not a persona
,I/SELinux ( 3212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3212 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/SELinux ( 3212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3212): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PreloadFilterInstaller( 3178): uses FILTER_DB_VER_1
,I/ActivityManager( 1018): Killing 2346:com.wsomacp/u0a23 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3212): TimaSignature is unavailable
,D/ActivityThread( 3212): Added TimaKeyStore provider
,V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1809): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1809): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1809): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/LocationManagerService( 1018): getProviders()=[passive]
,D/ScoverManager( 1809): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1809): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/Telecom ( 1430): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1809): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/InCall  ( 1809): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1809): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1809): InCallPresenter -  - dismissCoverDialog()...
,E/SQLiteLog( 3178): (284) automatic index on titles(filter_id)
,I/InCall  ( 1809): CallSContextMotion - stopPutDownListening
D/InCall  ( 1809): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/PhoneStatusBarView( 1180): setCallBackground:0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1809): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/FilterProviderReceiver( 3178): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3178): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1769): getCurrentCandidateView
,E/Zygote  ( 3243): MountEmulatedStorage()
,E/Zygote  ( 3243): v2
I/libpersona( 3243): KNOX_SDCARD checking this for 10098
I/libpersona( 3243): KNOX_SDCARD not a persona
,I/SELinux ( 3243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3243 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_2346/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3243): TimaSignature is unavailable
D/ActivityThread( 3243): Added TimaKeyStore provider
,I/Velvet.VelvetFactory( 3114): refreshing internal icing corpora
,I/PCWCLIENTTRACE_LOG( 3212): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3212): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3212): new DMDBOpenHelper instance
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/PackageIntentReceiver( 3243): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3243): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3269): MountEmulatedStorage()
,E/Zygote  ( 3269): v2
I/libpersona( 3269): KNOX_SDCARD checking this for 10099
I/libpersona( 3269): KNOX_SDCARD not a persona
I/Velvet.VelvetFactory( 3114): checking for language pack updates
I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3269 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2363:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
I/SELinux ( 3269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/VideoCallManager( 1809): Instantiating VideoCallManager
D/PCWCLIENTTRACE_DMContentProvider( 3212): [URIMatcher] - result : 2
I/SELinux ( 3269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ScoverManager( 1291): serviceVersion : 16908288
E/SELinux ( 3269): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
E/USB_UICC(  302): Timeout! No signal received. Retry num = 27
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1809): took 3.170938ms for 0*0 texture 0
I/ActivityManager( 1018): Killing 2394:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/GFX generate_partition_tables( 1809): took 5.814115ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3269): TimaSignature is unavailable
,D/ActivityThread( 3269): Added TimaKeyStore provider
,I/GFX raster( 1809): took 13.316615ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb8f87ef0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8f877c0 counterpartCT=4 counterpartW=176 counterparth=144
,I/ActivityManager( 1018): Killing 2410:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,I/DBG_FMMDM( 3133): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3133): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3133): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1809): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1809): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1809): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1809): Local Branch: 
I/Adreno-EGL( 1809): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1809): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1809):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/chromium( 2929): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2929): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Zygote  ( 3289): MountEmulatedStorage()
,E/Zygote  ( 3289): v2
I/libpersona( 3289): KNOX_SDCARD checking this for 1000
I/libpersona( 3289): KNOX_SDCARD not a persona
I/SELinux ( 3289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2495:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2218:com.sec.android.app.mt/1000 (adj 15): empty #32
,E/SELinux ( 3289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX GPU raster( 1809): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1809): took 0.338750ms for 320*61440 texture 37809
,I/art     (  310): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 25.449ms
,I/draw setup( 1809): took 11.774011ms for 320*240 texture 37809
E/GFX GPU raster( 1809): drawn
,I/GFX GPU raster ASTC( 1809): took 44.348332ms for 320*240 texture 12
I/GFX raster( 1809): took 44.422706ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb8f87e70 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8f879d8 counterpartCT=4 counterpartW=320 counterparth=240
,D/TimaKeyStoreProvider( 3289): TimaSignature is unavailable
,D/ActivityThread( 3289): Added TimaKeyStore provider
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1809): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1809): took 0.332917ms for 480*122880 texture 37813
I/draw setup( 1809): took 0.823750ms for 480*640 texture 37813
E/GFX GPU raster( 1809): drawn
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 24.919ms
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/GFX GPU raster ASTC( 1809): took 8.209740ms for 480*640 texture 12
I/GFX raster( 1809): took 8.264480ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb8f879d8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb91c9430 counterpartCT=4 counterpartW=480 counterparth=640
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 19.634ms
,I/ActivityManager( 1018): Killing 2474:com.android.calendar/u0a131 (adj 15): empty #31
,W/ContextImpl( 1797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1797): Service started flags 0 startId 1
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1809): eglCreateImageKHR: EGL_SUCCESS,
I/glCompressedTexImage2D( 1809): took 0.386771ms for 440*116864 texture 37809,
I/draw setup( 1809): took 0.882604ms for 440*330 texture 37809,
E/GFX GPU raster( 1809): drawn
I/GFX GPU raster ASTC( 1809): took 4.499062ms for 440*330 texture 12
,I/GFX raster( 1809): took 4.561094ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb91c9410 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb91c97e0 counterpartCT=4 counterpartW=440 counterparth=330
D/SecUISvc( 1797): Thread created.,
,D/JsMessageQueue( 2929): Set native->JS mode to OnlineEventsBridgeMode
,W/MessageQueue( 2865): Handler (android.os.Handler) {281100ce} sending message to a Handler on a dead thread
W/MessageQueue( 2865): java.lang.IllegalStateException: Handler (android.os.Handler) {281100ce} sending message to a Handler on a dead thread
W/MessageQueue( 2865): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 2865): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 2865): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 2865): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 2865): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 2865): 	at ffw.a(SourceFile:327)
W/MessageQueue( 2865): 	at guw.a(SourceFile:120)
W/MessageQueue( 2865): 	at guf.c(SourceFile:26)
W/MessageQueue( 2865): 	at gui.run(SourceFile:297)
W/MessageQueue( 2865): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 2865): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 2865): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 2865): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DBG_FMMDS( 3289): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3289): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1809): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1809): took 0.426250ms for 480*163840 texture 37811
I/draw setup( 1809): took 0.906980ms for 480*640 texture 37811
E/GFX GPU raster( 1809): drawn
,I/GFX GPU raster ASTC( 1809): took 5.762136ms for 480*640 texture 12
I/GFX raster( 1809): took 5.846094ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb91c9250 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb91dc278 counterpartCT=4 counterpartW=480 counterparth=640
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_2363/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2394/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2474/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2410/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2218/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2495/cgroup.procs: No such file or directory
,I/LockPatternUtils( 1291): isSmartCardAuthenticationAvailable: false
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SamsungIME( 1769): Dismiss ExpandCandiate
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 3114): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PCWCLIENTTRACE_DMContentProvider( 3212): [URIMatcher] - result : 2
I/FavoriteContactNamesSup( 3114): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3114): get() : Execute runnable (UI thread)
,E/DBG_FMMDS( 3289): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3289): [50.18.150420][Line:43][xdbDBInit] 
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/chromium( 2929): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 2929): 
,E/Zygote  ( 3319): MountEmulatedStorage()
E/Zygote  ( 3319): v2
I/libpersona( 3319): KNOX_SDCARD checking this for 10055
I/libpersona( 3319): KNOX_SDCARD not a persona
,I/SELinux ( 3319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3319 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
E/SELinux ( 3319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1809): took 2.252604ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1809): took 7.580832ms for 0*0 texture 0
,I/GFX raster( 1809): took 11.773644ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb91b9360 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb91dc298 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1809): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1809): took 2.441927ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1809): took 6.231355ms for 0*0 texture 0
,I/GFX raster( 1809): took 10.855781ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1809): Bitmap=0xb91c98c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb91ddf88 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1809): registerListener
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
D/Settings_Utils( 1291): isSupportVNFestival SM-A300FU XEO
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@1dbac48, pid : 1809, uid : 1001, type : 1
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/TimaKeyStoreProvider( 3319): TimaSignature is unavailable
,D/ActivityThread( 3319): Added TimaKeyStore provider
,I/ContactLabelSupplier( 3114): get() : OptedIn = false
,D/InCall  ( 1809): InCallPresenter -  - Finished InCallPresenter.setUp
,I/Velvet.VelvetFactory( 3114): refreshing search history.
,I/DBG_FMMDS( 3289): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,D/jxcore_app_log( 2929): JniHelper::setJavaVM(0xb8bdb448), pthread_self() = -1188759928
,D/JX-Cordova( 2929): jxcore cordova android initializing
,D/UserAnalysis.PlaceProvider( 3319): PlaceProvider onCreate()
,W/ResourceType( 1291): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1291): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/DBG_FMMDS( 3289): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3289): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3289): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3289): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3289): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3289): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/SamsungIME( 1769): getDebugLevel  : 0x4f4c
,W/jxcore-log( 2929): Initializing JXcore engine
W/jxcore-log( 2929): JXcore engine is ready
,W/jxcore-log( 2929): Starting JXcore engine
,D/UserAnalysis.SecureDbManager( 3319): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3319): SecurePlaceDbHelper() 
D/UserAnalysis( 3319): Create SecureDbHelper,
,I/SamsungIME( 1769): getDebugLevel  : 0x4f4c
,E/audit   ( 1783): type=1400 msg=audit(1451921637.965:203): avc:  denied  { ioctl } for  pid=2929 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1783):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1783): type=1300 msg=audit(1451921637.965:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=beb1bd58 items=0 ppid=310 ppcomm=main pid=2929 auid=4294967295 uid=10334 gid=10334 euid=10334 suid=10334 fsuid=10334 egid=10334 sgid=10334 fsgid=10334 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1783): type=1320 msg=audit(1451921637.965:203): 
,I/FOTA_Client( 3029): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3029): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/FOTA_Client( 3029): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,I/SamsungIME( 1769): KeybaordView init() : load resources
,W/FOTA_Client( 3029): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3343): MountEmulatedStorage()
E/Zygote  ( 3343): v2
I/libpersona( 3343): KNOX_SDCARD checking this for 10013
I/libpersona( 3343): KNOX_SDCARD not a persona
,I/SELinux ( 3343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3343 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,E/SELinux ( 3343): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 3319): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3319): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Search.GservicesUpdateTask( 3114): Updating Gservices keys
,D/IntelligenceServiceApplication( 3319): no applications having user consent for prediction,
W/jxcore-log( 2929): Platform android
W/jxcore-log( 2929): 
W/jxcore-log( 2929): Process ARCH arm
W/jxcore-log( 2929): 
I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/SamsungIME( 1769): getCurrentKeyboard
I/SamsungIME( 1769): getTextKeyboard
D/TimaKeyStoreProvider( 3343): TimaSignature is unavailable
,E/Zygote  ( 3359): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3359 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 3359): v2
I/libpersona( 3359): KNOX_SDCARD checking this for 10056
I/libpersona( 3359): KNOX_SDCARD not a persona
,D/ActivityThread( 3343): Added TimaKeyStore provider
I/SELinux ( 3359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Killing 2536:com.android.keychain/1000 (adj 15): empty #31
,I/SELinux ( 3359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3319): [PlaceDetection::stopService] Service stopped.
,D/TimaKeyStoreProvider( 3359): TimaSignature is unavailable
,D/ActivityThread( 3359): Added TimaKeyStore provider
,I/jxcore-log( 2929): JXcore Cordova bridge is ready!
I/jxcore-log( 2929): 
,W/jxcore-log( 2929): JXcore engine is started
,V/OneTimeInitializerReceiver( 3343): OneTimeInitializerReceiver.onReceive
,I/art     ( 1621): Explicit concurrent mark sweep GC freed 7201(351KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 805us total 56.122ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3343): OneTimeService.onHandleIntent
,V/PlaceDetection v1.0.19 ( 3319): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3319): Constructor Preference
,D/SamsungIME( 1769): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2536/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/WebViewFactory( 3114): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/jxcore-log( 2929): >> samsung-SM-A300FU
E/jxcore-log( 2929): 
,I/jxcore-log( 2929): Total memory 1451114496
I/jxcore-log( 2929): 
,I/jxcore-log( 2929): Free memory 21319680
I/jxcore-log( 2929): 
I/jxcore-log( 2929): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2929): 
I/jxcore-log( 2929): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2929): 
,I/LibraryLoader( 3114): Loading: webviewchromium
,I/jxcore-log( 2929): userPath [ 'www' ]
I/jxcore-log( 2929): 
,E/SMD     (  292): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/jxcore-log( 2929): Size 540 960
I/jxcore-log( 2929): 
I/LibraryLoader( 3114): Time to load native libraries: 16 ms (timestamps 4346-4362)
,I/LibraryLoader( 3114): Expected native library version number "",actual native library version number ""
,I/jxcore-log( 2929): Screen Brightness 255
I/jxcore-log( 2929): 
,E/jxcore-log( 2929): Dummy Error Log.
E/jxcore-log( 2929): 
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 28
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Zygote  ( 3388): MountEmulatedStorage()
,I/libpersona( 3388): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3388): v2
I/libpersona( 3388): KNOX_SDCARD not a persona
I/SELinux ( 3388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/UpdateIcingCorporaServi( 3114): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/sCloudBackupApp( 3359): sCloudBackupApp Version Info : 4.04.7.KK_APP
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,D/TimaKeyStoreProvider( 3388): TimaSignature is unavailable
,D/ActivityThread( 3388): Added TimaKeyStore provider
,W/art     ( 3114): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3410): MountEmulatedStorage()
E/Zygote  ( 3410): v2
I/libpersona( 3410): KNOX_SDCARD checking this for 10058
I/libpersona( 3410): KNOX_SDCARD not a persona
,I/SELinux ( 3410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3410): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3410 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/GAV2    ( 3114): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 3410): TimaSignature is unavailable
,D/ActivityThread( 3410): Added TimaKeyStore provider
,W/GAV2    ( 3114): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/RlzPingService( 3195): Setting next ping for 1452526438542
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 3388): onCreate
,E/Zygote  ( 3434): MountEmulatedStorage()
E/Zygote  ( 3434): v2
I/libpersona( 3434): KNOX_SDCARD checking this for 10018
I/libpersona( 3434): KNOX_SDCARD not a persona
,I/SELinux ( 3434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3434 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/Hs20UtilService( 3388): Starting #1,
I/Hs20UtilService( 3388): Message received 5003
,I/SELinux ( 3434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3434): TimaSignature is unavailable
D/ActivityThread( 3434): Added TimaKeyStore provider
,I/LockPatternUtils( 1291): isSmartCardAuthenticationAvailable: false
,I/Gmail   ( 3269): getAccountsCursor
,I/ExternalOEMControlProvider( 3410): onCreate
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 22475(1247KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 21MB/32MB, paused 2.236ms total 176.703ms
,I/art     ( 1018): WaitForGcToComplete blocked for 148.547ms for cause Explicit
,D/FileApkUtils( 1865): Spent 41ms computing apk sha1.
,D/FileApkUtils( 1865): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1865): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-cf053f76526e84be2388d3f24ecde21377d895e5@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/ActivityManager( 1018): Killing 2606:com.mobeam.barcodeService/1000 (adj 15): empty #31
,D/DexOptUtils( 1865): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1865): Keeping up-to-date module: module-cf053f76526e84be2388d3f24ecde21377d895e5
,D/ChimeraCfgMgr( 1865): Reading stored module config
,I/FactoryTestApp( 2514): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2968)  
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 2120(122KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.142ms total 123.237ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2606/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10052
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/NetworkUtils( 3114): OkHttp exception
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/Zygote  ( 3462): MountEmulatedStorage()
E/Zygote  ( 3462): v2
I/libpersona( 3462): KNOX_SDCARD checking this for 1000
I/libpersona( 3462): KNOX_SDCARD not a persona
,I/SELinux ( 3462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2623:flipboard.boxer.app/u0a97 (adj 15): empty #31
,I/jxcore-log( 2929): getBuffer is called!!!!
I/jxcore-log( 2929): 
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3269): Observing account changes for notifications
D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 3462): TimaSignature is unavailable
,D/ActivityThread( 3462): Added TimaKeyStore provider
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/GAV2    ( 3269): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/libprocessgroup( 1018): failed to open /acct/uid_10097/pid_2623/cgroup.procs: No such file or directory
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GmsModuleFndr( 1865): Beginning GMS chimera module scan
,I/ActivityManager( 1018): Killing 2649:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,W/ResourcesManager( 3462): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 3434): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 16:33:59 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3434): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3434): KLMSIntentService(): onCreate()
,I/ServiceMode( 3462): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3462): setReferenceIsDumpState : 0
,D/GmsModuleFndr( 1865): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,I/KLMS-2.5.123: ( 3434): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,D/ChimeraCfgMgr( 1865): Beginning module configuration check,
,I/KLMS-2.5.123: ( 3434): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ChimeraCfgMgr( 1865): Module APKs unchanged, check complete
,E/Zygote  ( 3481): MountEmulatedStorage()
E/Zygote  ( 3481): v2
I/libpersona( 3481): KNOX_SDCARD checking this for 10020
I/libpersona( 3481): KNOX_SDCARD not a persona
,I/SELinux ( 3481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3481 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.123: ( 3434): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3434): KLMSIntentService(): BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ContextImpl( 1291): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3481): TimaSignature is unavailable
,D/ActivityThread( 3481): Added TimaKeyStore provider,
,E/Zygote  ( 3498): MountEmulatedStorage()
,I/libpersona( 3498): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3498): v2
I/libpersona( 3498): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/libprocessgroup( 1018): failed to open /acct/uid_1101/pid_2649/cgroup.procs: No such file or directory
E/SELinux ( 3498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2691:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.123: ( 3434): KLMSIntentService(): onDestroy()
,W/ContextImpl( 1291): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 3498): TimaSignature is unavailable
,D/ActivityThread( 3498): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 2708:com.sec.usbsettings/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1291): InitSerachDBThread thread end!
,E/Gmail   ( 3269): Error finding the version of the Email provider.....
E/Gmail   ( 3269): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3269): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3269): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3269): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3269): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3269): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3269): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3269): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/Gmail   ( 3269): getAccountsCursor
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2708/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_2691/cgroup.procs: No such file or directory
,E/Zygote  ( 3526): MountEmulatedStorage(),
E/Zygote  ( 3526): v2
I/libpersona( 3526): KNOX_SDCARD checking this for 10102
I/libpersona( 3526): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3526 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3526): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 29
,E/Zygote  ( 3538): MountEmulatedStorage()
,E/Zygote  ( 3538): v2
I/libpersona( 3538): KNOX_SDCARD checking this for 1000
I/libpersona( 3538): KNOX_SDCARD not a persona
,I/SELinux ( 3538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
I/SELinux ( 3538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2091:flipboard.app/u0a96 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 3526): TimaSignature is unavailable
D/ActivityThread( 3526): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3498): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3498): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,I/art     (  310): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 27.805ms
,I/GoogleHttpClient( 1621): GMS http client unavailable, use old client
,D/NPS_WSSNPS( 3498): [] Service onCreate!!
,E/ActivityThread( 3269): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@38216b0e that was originally bound here
E/ActivityThread( 3269): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@38216b0e that was originally bound here
E/ActivityThread( 3269): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3269): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3269): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3269): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3269): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3269): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3269): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3269): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3269): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3269): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3269): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3269): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3269): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3269): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 18.019ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3538): TimaSignature is unavailable
,D/ActivityThread( 3538): Added TimaKeyStore provider
E/SQLiteLog( 3269): (283) recovered 103 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 3526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.986ms
,E/Zygote  ( 3561): MountEmulatedStorage(),
E/Zygote  ( 3561): v2
I/libpersona( 3561): KNOX_SDCARD checking this for 1000
I/libpersona( 3561): KNOX_SDCARD not a persona
I/SELinux ( 3561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@39d792d9
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_2091/cgroup.procs: No such file or directory
D/NPS_WSSNPS( 3498): [50.150321] NpsServiceTask Start
D/TimaKeyStoreProvider( 3561): TimaSignature is unavailable
D/NPS_WSSNPS( 3498): [50.150321] smlDBHelper
D/ActivityThread( 3561): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 1865): Found 10011
,E/MTPRx   ( 3538): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1018): mCursor = null
V/MTPRx   ( 3538): sealedState: false
V/MTPRx   ( 3538): sealedUsbMassStorageState: false
,D/SettingsProvider( 1018): name = mtp_usb_connection_status
,D/SettingsProvider( 1018): name = access_control_enabled
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3580): MountEmulatedStorage(),
,E/Zygote  ( 3580): v2
,I/libpersona( 3580): KNOX_SDCARD checking this for 10065,
I/libpersona( 3580): KNOX_SDCARD not a persona
,I/SELinux ( 3580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3580 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NPS_WSSNPS( 3498): [50.150321] AsyncBulkFlagCheck
,I/ActivityManager( 1018): Killing 2248:com.android.mms/u0a41 (adj 15): empty #31
,I/Icing   ( 1865): Storage manager: low false usage 2.08MB avail 10.00GB capacity 11.63GB
,D/SettingsProvider( 1018): name = media_player_mode
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3580): TimaSignature is unavailable
,I/NPS_WSSNPS( 3498): [50.150321] IsRemain_AsyncBulkCheck
D/ActivityThread( 3580): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3498): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3498): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3498): [50.150321] Service onDestroy
,I/ActivityManager( 1018): Killing 2742:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,D/FileShare-Server( 3580): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_2248/cgroup.procs: No such file or directory
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/NPS_WSSNPS( 3498): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3498): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3498): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3498): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3498): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3498): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3498): [50.150321] smlBRPenMemoMDelete
W/libprocessgroup( 1018): failed to open /acct/uid_10043/pid_2742/cgroup.procs: No such file or directory
I/NPS_WSSNPS( 3498): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3498): [50.150321] cpuBooster release : false
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/NPS_WSSNPS( 3498): [50.150321] dsServerSocket close
,D/SettingsProvider( 1018): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/Babel   ( 3526): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3526): MmsConfig.loadMmsSettings
,I/Babel   ( 3526): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Babel   ( 3526): MmsConfig.loadFromDatabase
,D/SettingsProvider( 1018): name = media_mount_count
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 3269): fail readDirectory() errno=2
,D/SettingsProvider( 1018): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/Gmail   ( 3269): notifyAccountChanged
,I/Gmail   ( 3269): getAccountsCursor
,I/Gmail   ( 3269): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 1668): Explicit concurrent mark sweep GC freed 17816(1312KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 9MB/15MB, paused 1.271ms total 117.656ms
,I/ActivityManager( 1018): Killing 2638:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,D/SettingsProvider( 1018): name = boot_time_connected
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/System.out( 1668): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1668): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1668): (HTTPLog)-Static: isShipBuild true
I/System.out( 1668): (HTTPLog)-Thread-136-285831635: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1668): (HTTPLog)-Static: isSBSettingEnabled false
,D/SettingsProvider( 1018): name = mtp_open_session
,W/Settings( 3526): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3526): Unrecognized profile 2130706433 for video/avc
,E/Babel   ( 3526): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3526): MmsConfig.loadFromResources
,E/Babel   ( 3526): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3526): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/AudioCapabilities( 3526): Unsupported mime audio/evrc
,W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_2638/cgroup.procs: No such file or directory
,I/Gmail   ( 3269): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Auth    ( 1668): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,I/PCWCLIENTTRACE_PushUtil( 3212): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3212): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3212): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3212): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3212): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3212): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :8
,W/PCWCLIENTTRACE_PCWHandler( 3212): [ensureRegistration] - netwrok is not available. action ignored
,I/Gmail   ( 3269): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3269): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 3526): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3526): Unsupported mime audio/mpeg-L1
,E/Zygote  ( 3619): MountEmulatedStorage()
,I/libpersona( 3619): KNOX_SDCARD checking this for 10028
E/Zygote  ( 3619): v2
I/libpersona( 3619): KNOX_SDCARD not a persona
,I/SELinux ( 3619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3619 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,W/AudioCapabilities( 3526): Unsupported mime audio/mpeg-L2
I/ActivityManager( 1018): Killing 2806:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/SELinux ( 3619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3619): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/TimaKeyStoreProvider( 3619): TimaSignature is unavailable
,D/ActivityThread( 3619): Added TimaKeyStore provider
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Search.LoginHelper( 3114): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,W/AudioCapabilities( 3526): Unsupported mime audio/x-ms-wma
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2806/cgroup.procs: No such file or directory
W/AudioCapabilities( 3526): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3526): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3526): Unsupported mime audio/evrc
,I/CheckinService( 1865): Checkin interval check for package: unspecified last checkin: 1451292302959 min interval config: 0 actual interval: 629337168
,W/VideoCapabilities( 3526): Unsupported mime video/wvc1
,W/VideoCapabilities( 3526): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3526): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3526): Unsupported mime video/wvc1
,W/VideoCapabilities( 3526): Unsupported mime video/x-ms-wmv
,I/CheckinService( 1865): Disabling old GoogleServicesFramework version
,W/VideoCapabilities( 3526): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3526): Unsupported mime video/x-ms-wmv8
,D/ChimeraCfgMgr( 1865): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/VideoCapabilities( 3526): Unsupported mime video/mp43
,W/VideoCapabilities( 3526): Unsupported mime video/sorenson,
,D/BootCompletedReceiver( 1865): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1865): Got an BootCompleted event.
W/VideoCapabilities( 3526): Unsupported mime video/mp4v-esdp
,D/BootCompletedReceiver( 1865): Will NOT schedule AdAttestation signal task because it's disabled.
,V/Babel   ( 3526): babel boot account: SMS
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 17771(934KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.414ms total 144.328ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,V/Babel   ( 3526): babel boot account: thalitester@gmail.com
,I/Gmail   ( 3269): getAccountsCursor
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1865): onCreate
,D/GCM     ( 1865): COMPAT: Multi user not supported
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Killing 2779:com.sec.dsm.system/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1668): COMPAT: Multi user not supported
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 3526): Unsupported profile 4 for video/mp4v-es
,E/Zygote  ( 3648): MountEmulatedStorage()
E/Zygote  ( 3648): v2
I/libpersona( 3648): KNOX_SDCARD checking this for 1000
I/libpersona( 3648): KNOX_SDCARD not a persona
I/SELinux ( 3648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  302): Timeout! No signal received. Retry num = 30
,E/Zygote  ( 3662): MountEmulatedStorage()
E/Zygote  ( 3662): v2
I/libpersona( 3662): KNOX_SDCARD checking this for 1000
I/libpersona( 3662): KNOX_SDCARD not a persona
,I/SELinux ( 3662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3662 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
I/ActivityManager( 1018): Killing 2841:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 3648): TimaSignature is unavailable
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 3648): Added TimaKeyStore provider
,I/System.out( 1668): (HTTPLog)-Static: isSBSettingEnabled false
,D/TimaKeyStoreProvider( 3662): TimaSignature is unavailable
E/Auth    ( 1668): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
D/ActivityThread( 3662): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SystemUpdateService( 1865): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1865): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 1865): Checking schedule, now: 1451921640404 next: 1451859229870
I/CheckinService( 1865): active receiver: enabled
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Search.LoginHelper( 3114): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/accuweather( 1700): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1700): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1700): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,I/SystemUpdateService( 1865): cancelUpdate (empty URL)
I/SystemUpdateService( 1865): active receiver: disabled
,D/accuweather( 1700): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,E/USB_UICC(  302): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  302): usb_uicc_init_qmi failed ! 
I/USB_UICC(  302): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  302): usb_uicc_cleanup, Issuing QMI deinit ... 
D/accuweather( 1700): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1700): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1700): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
D/accuweather( 1700): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1700): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,E/accuweather( 1700): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 16 34
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2779/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2841/cgroup.procs: No such file or directory
,I/System.out( 1668): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1668): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 3114): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/System.out( 1668): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1668): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 3114): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 3114): canRun() : Opted Out
,I/art     ( 1621): Explicit concurrent mark sweep GC freed 4030(175KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 753us total 26.047ms
,W/SQLiteConnectionPool( 1621): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/AuthZen ( 1865): Handling intent: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 3619): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3619): Inside WakeupProvider,
,E/Zygote  ( 3694): MountEmulatedStorage()
I/libpersona( 3694): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3694): v2
I/libpersona( 3694): KNOX_SDCARD not a persona
I/SELinux ( 3694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 1559:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/SELinux ( 3694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3694): TimaSignature is unavailable
,D/ActivityThread( 3694): Added TimaKeyStore provider
,W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/AuthZenEventHandler( 1865): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3711): MountEmulatedStorage()
E/Zygote  ( 3711): v2
I/libpersona( 3711): KNOX_SDCARD checking this for 1000
I/libpersona( 3711): KNOX_SDCARD not a persona
,I/SELinux ( 3711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3711): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3711): TimaSignature is unavailable
,D/ActivityThread( 3711): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VlingoApplication( 3619): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,D/FactoryTestApp( 2514): [DummyFtClient$onDestroy](2514) Destroy DummyFtClient service
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_1559/cgroup.procs: No such file or directory
,W/ResourcesManager( 3711): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/KnoxSetupWizardClient( 3694): isShipMode : 1
,I/KnoxSetupWizardClient( 3694): onReceive : android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1865): Using Auth Proxy for data requests.
,D/FactoryTestApp( 2514): [Support$Values.getString](2514) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2514): [ModuleCommon$isConnectionModeNone](2514) mConnectionMode = gsm
I/FactoryTestApp( 2514): [ModuleCommon$isRunningFtClient](2514) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2514): [DummyFtClient$onDestroy](2514) kill process
I/Process ( 2514): Sending signal. PID: 2514 SIG: 9
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapter( 3619): 57440619: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3619): 57440619: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3619): 57440619: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3619): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
W/ContextImpl( 3711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ShortcutReceiver( 3694):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/libpersona( 3734): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3734): MountEmulatedStorage()
I/libpersona( 3734): KNOX_SDCARD not a persona
E/Zygote  ( 3734): v2
I/SELinux ( 3734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/F_PHONE ( 3711): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3711): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/TimaKeyStoreProvider( 3734): TimaSignature is unavailable
,D/ActivityThread( 3734): Added TimaKeyStore provider
,I/ActivityManager( 1018): Process com.sec.factory (pid 2514)(adj 0) has died(34,680)
,D/KnoxShortcutUtil( 3694): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3694):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 3694):  shortcut migration not required 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3734): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 3754): MountEmulatedStorage()
E/Zygote  ( 3754): v2
I/libpersona( 3754): KNOX_SDCARD checking this for 1000
I/libpersona( 3754): KNOX_SDCARD not a persona
I/SELinux ( 3754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3754 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/F_PHONE ( 3711): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3711): default registerAction()
I/F_PHONE ( 3711): [[com.sec.bcservice]] sendPendingMessage()
,D/BluetoothBDAdrressReceiver( 3734): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3734): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/System.err( 3694): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3694): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3694): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3694): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3694): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3694): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3694): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/SystemUpdateService( 1865): onDestroy
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1454): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BluetoothBDTestService( 1454): onCreate()
,E/BluetoothBDTestService( 1454): onStart(), extra_type: BOOT_COMPLETED
D/TimaKeyStoreProvider( 3754): TimaSignature is unavailable
,E/BluetoothBDTestService( 1454): bd_address_path: /efs/bluetooth/bt_addr
D/ActivityThread( 3754): Added TimaKeyStore provider
,E/BluetoothBDTestService( 1454): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 3770): MountEmulatedStorage()
E/Zygote  ( 3770): v2
I/libpersona( 3770): KNOX_SDCARD checking this for 1000
I/libpersona( 3770): KNOX_SDCARD not a persona
,I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2823:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
,D/ActivityThread( 3770): Added TimaKeyStore provider
,W/ResourcesManager( 3770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,W/libprocessgroup( 1018): failed to open /acct/uid_10082/pid_2823/cgroup.procs: No such file or directory
,I/art     ( 1865): Explicit concurrent mark sweep GC freed 27864(2MB) AllocSpace objects, 31(496KB) LOS objects, 24% free, 8MB/10MB, paused 1.269ms total 104.271ms
,E/BaseAppContext( 1865): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/StatusChecker( 3754): onReceive : android.intent.action.BOOT_COMPLETED
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 3770): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3770): premStatus:2
,I/KnoxUsageLogPro( 3770): isEulaShown : false
,I/KnoxUsageLogPro( 3770): KnoxUsageReceiver onReceive : not Processible, just return
,I/StatusChecker( 3754): onReceive : net.mt.init : DONE
,I/ActivityManager( 1018): Killing 2885:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3648): Resource data:2131165186
,W/ResourcesManager( 3648): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,I/KnoxUsageLogPro( 3770): savePreference: key = previous_sys_time value = 1451921641240
,D/VlingoApplication( 3619): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3619): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,E/Zygote  ( 3795): MountEmulatedStorage()
E/Zygote  ( 3795): v2
I/libpersona( 3795): KNOX_SDCARD checking this for 10113
I/libpersona( 3795): KNOX_SDCARD not a persona
,I/SELinux ( 3795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/DialogFlow( 3619): initQueue()
,I/SELinux ( 3795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3795 uid=10113 gids={50113, 9997} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2906:com.dropbox.android/u0a88 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/art     (  310): Explicit concurrent mark sweep GC freed 8775(373KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 22.158ms
,I/KnoxUsageLogPro( 3770): savePreference: key = previous_elapsed_time value = 37262
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.787ms
,D/TimaKeyStoreProvider( 3795): TimaSignature is unavailable
,D/ActivityThread( 3795): Added TimaKeyStore provider
,I/AuthZen ( 1865): Fetching signing key...
,E/SMD     (  292): DCD OFF
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 20.787ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/AuthZen ( 1865): Signing key fetched successfully!
,E/Zygote  ( 3811): MountEmulatedStorage()
E/Zygote  ( 3811): v2
I/libpersona( 3811): KNOX_SDCARD checking this for 10029
I/libpersona( 3811): KNOX_SDCARD not a persona
,I/SELinux ( 3811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/BaseAppContext( 1865): Using Auth Proxy for data requests.
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3811 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 3811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2937:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 ,
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2885/cgroup.procs: No such file or directory
I/PageBuddyNotiSvc( 3795): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/a       ( 1865): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1865): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1865): Clearing transaction cache
W/ContextImpl( 3795): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/TimaKeyStoreProvider( 3811): TimaSignature is unavailable
,D/ActivityThread( 3811): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_2906/cgroup.procs: No such file or directory
,I/PageBuddyNotiSvc( 3795): onCreate mCpBitFlag=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034113
,W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_2937/cgroup.procs: No such file or directory,
,W/ResourcesManager( 3648): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 3827): MountEmulatedStorage(),
E/Zygote  ( 3827): v2
I/libpersona( 3827): KNOX_SDCARD checking this for 10121
I/libpersona( 3827): KNOX_SDCARD not a persona
,I/SELinux ( 3827): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3827): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3827): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3827 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3827): TimaSignature is unavailable
,D/ActivityThread( 3827): Added TimaKeyStore provider
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.933750ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3648): took 6.282967ms for 0*0 texture 0
,I/GFX raster( 3648): took 10.569217ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fa8940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fa8be8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3827): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3827): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3827): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/SQLiteLog( 1865): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     ( 1621): Explicit concurrent mark sweep GC freed 2936(116KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 862us total 27.644ms
,D/QuickConnect( 3827): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.811875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fa8940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fb76d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1018): name = scon_is_running
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10121
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 3827): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3827): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/QuickConnect( 3827): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3845): MountEmulatedStorage()
,E/Zygote  ( 3845): v2
,I/libpersona( 3845): KNOX_SDCARD checking this for 10127
I/libpersona( 3845): KNOX_SDCARD not a persona
,I/SELinux ( 3845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3845 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
,I/SELinux ( 3845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3845): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2969:com.policydm/1000 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.656458ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3845): TimaSignature is unavailable
D/ActivityThread( 3845): Added TimaKeyStore provider
,E/Zygote  ( 3859): MountEmulatedStorage()
E/Zygote  ( 3859): v2
I/libpersona( 3859): KNOX_SDCARD checking this for 10030
I/libpersona( 3859): KNOX_SDCARD not a persona
,I/SELinux ( 3859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3859): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3859 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2989:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/GFX generate_partition_tables( 3648): took 7.758281ms for 0*0 texture 0
I/GFX raster( 3648): took 11.337135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fb3fe0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fb40d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/TimaKeyStoreProvider( 3859): TimaSignature is unavailable
,D/ActivityThread( 3859): Added TimaKeyStore provider
,I/Icing   ( 1865): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 3845): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3845): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3845): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3845): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 1.766093ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fb17f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fb1960 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/GCoreUlr( 1668): DispatchingService.onCreate()
,D/GCM     ( 1668): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2969/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10146/pid_2989/cgroup.procs: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.841511ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be2e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8be3080 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 3845): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ManifestProvider( 3845): onCreate()
,E/NetworkSettingsReceiver( 3845): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.637760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8cf1980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.689792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f7ab50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f97d80 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3859): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3859): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3859): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/System.err( 3845): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 3845): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 3845): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 3845): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 3845): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 3845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 3845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3845): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3845): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3845): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3845): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/GCoreUlr( 1668): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/SBrowserFeatureFlag( 3845): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1f71442d
D/SBrowserFeatureFlag( 3845): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 3845): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,W/ResourcesManager( 3859): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3859): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 3081:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3859): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3859): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3648): took 0.561510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f4fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,E/Zygote  ( 3888): MountEmulatedStorage()
E/Zygote  ( 3888): v2
I/libpersona( 3888): KNOX_SDCARD checking this for 10131,
I/libpersona( 3888): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3888 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3133:com.fmm.dm/1000 (adj 15): empty #31
,I/SELinux ( 3888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034113
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.810677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be3080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f97d80 counterpartCT=4 counterpartW=96 counterparth=96
,W/GCoreFlp( 1668): No location to return for getLastLocation()
,W/FusedLocationProvider( 1668): location=null
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3888): TimaSignature is unavailable
,D/ActivityThread( 3888): Added TimaKeyStore provider
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/libprocessgroup( 1018): failed to open /acct/uid_10090/pid_3081/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3133/cgroup.procs: No such file or directory
,W/GCoreFlp( 1668): No location to return for getLastLocation()
W/FusedLocationProvider( 1668): location=null
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.857239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be3080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f97250 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/Auth    ( 1668): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.602292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f97d80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.617760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fb17f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f97250 counterpartCT=4 counterpartW=96 counterparth=96
,D/PersistentNotificationBroadcastReceiver( 1668): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.819270ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be2e40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/System.out( 3619): INFO:Resource not found:/Common.properties Using default values
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1668): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3924): MountEmulatedStorage()
,E/Zygote  ( 3924): v2
I/libpersona( 3924): KNOX_SDCARD checking this for 10026
I/libpersona( 3924): KNOX_SDCARD not a persona
,I/SELinux ( 3924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3924): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3924 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3924): TimaSignature is unavailable
,D/ActivityThread( 3924): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.751614ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8cf1980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f97250 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 3941): MountEmulatedStorage()
E/Zygote  ( 3941): v2
I/libpersona( 3941): KNOX_SDCARD checking this for 10037
I/libpersona( 3941): KNOX_SDCARD not a persona
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 3941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/GFX raster( 3648): took 0.731875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f7ab50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 3941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3941 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3941): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3648): took 0.649427ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f4fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f97250 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 3941): TimaSignature is unavailable
,D/ActivityThread( 3941): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,E/Zygote  ( 3957): MountEmulatedStorage(),
E/Zygote  ( 3957): v2
I/libpersona( 3957): KNOX_SDCARD checking this for 10135,
I/libpersona( 3957): KNOX_SDCARD not a persona
,I/SELinux ( 3957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3957 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/AMMetaDataParserService( 3648): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034112
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.660834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fb17f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1668): Unbound from all location providers
,W/ResourcesManager( 3941): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,I/GCoreUlr( 1668): Place inference reporting - stopped
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31906(1830KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/33MB, paused 2.428ms total 185.453ms
,D/TimaKeyStoreProvider( 3957): TimaSignature is unavailable
,D/ActivityThread( 3957): Added TimaKeyStore provider
,I/GCoreUlr( 1668): DispatchingService.onDestroy()
I/GCoreUlr( 1668): Stopping handler for UlrDispSvcFast
,W/ResourcesManager( 3957): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3957): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3957): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3957): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3957): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Process ( 3859): Sending signal. PID: 3859 SIG: 9
,I/GCoreUlr( 1668): Unbound from all location providers
I/GCoreUlr( 1668): Place inference reporting - stopped
,I/CalendarProvider2( 3941): CalendarProvider2.onCreate() called
,I/ActivityManager( 1018): Process com.sec.android.app.sns3 (pid 3859)(adj 0) has died(25,680)
,I/ActivityManager( 1018): Killing 3149:com.sec.factory.camera/1000 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3973): MountEmulatedStorage()
,E/Zygote  ( 3973): v2
I/libpersona( 3973): KNOX_SDCARD checking this for 10031
I/libpersona( 3973): KNOX_SDCARD not a persona
,I/SELinux ( 3973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3973 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3982): MountEmulatedStorage(),
I/libpersona( 3982): KNOX_SDCARD checking this for 10141
E/Zygote  ( 3982): v2,
I/libpersona( 3982): KNOX_SDCARD not a persona
I/SELinux ( 3982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3982 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 3982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.676824ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fb17f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f967b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/TimaKeyStoreProvider( 3982): TimaSignature is unavailable
,D/ActivityThread( 3982): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3973): TimaSignature is unavailable
,D/ActivityThread( 3973): Added TimaKeyStore provider
,W/ResourcesManager( 3811): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 3982): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3982): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3982): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3149/cgroup.procs: No such file or directory
,I/Icing   ( 1865): Internal init done: storage state 0
,I/Icing   ( 1865): Post-init done
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.712083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f967b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fb5ef0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ResourcesManager( 3811): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3811): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3811): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4011): MountEmulatedStorage(),
I/libpersona( 4011): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4011): v2
I/libpersona( 4011): KNOX_SDCARD not a persona
I/SELinux ( 4011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.639115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8cf1980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dd6080 counterpartCT=4 counterpartW=96 counterparth=96
,E/SELinux ( 4011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/art     (  310): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 22.393ms
,D/TimaKeyStoreProvider( 4011): TimaSignature is unavailable
D/ActivityThread( 4011): Added TimaKeyStore provider
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 21.345ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.717ms
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4011): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4011): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 4011): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4011): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4011): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,D/Finsky  ( 3924): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/DBG_POLICYDM( 4011): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1668): Explicit concurrent mark sweep GC freed 18914(1264KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 9MB/16MB, paused 1.142ms total 113.794ms,
,E/Zygote  ( 4035): MountEmulatedStorage()
E/Zygote  ( 4035): v2
,I/libpersona( 4035): KNOX_SDCARD checking this for 10032,
I/libpersona( 4035): KNOX_SDCARD not a persona
,I/SELinux ( 4035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4035): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4035 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 3178:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4035): TimaSignature is unavailable
,D/ActivityThread( 4035): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4011): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 4011): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 4011): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/libprocessgroup( 1018): failed to open /acct/uid_10095/pid_3178/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 2929): disable()
,E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
,E/SPPClientService( 4035): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
E/SPPClientService( 4035): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4035): [PushClientApplication] Push log off : This is Ship build version
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: false pid=2929, uid=10334
,D/SettingsProvider( 1018): name = wifi_on
,I/jxcore-log( 2929): ****TEST TOOK:  5081  ms ****
I/jxcore-log( 2929): 
,I/jxcore-log( 2929): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2929): 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 4035): PushLog.txt file is not deleted.
,D/SPPClientService( 4035): PushLog.txt file is not deleted.
D/SPPClientService( 4035): ============PushLog. stop!
,E/Zygote  ( 4073): MountEmulatedStorage()
E/Zygote  ( 4073): v2
I/libpersona( 4073): KNOX_SDCARD checking this for 10068
I/libpersona( 4073): KNOX_SDCARD not a persona
I/SELinux ( 4073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4073 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/SELinux ( 4073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4073): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4073): TimaSignature is unavailable
,D/ActivityThread( 4073): Added TimaKeyStore provider
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1180 (0x0)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4073): onCreate
D/BadgeProvider( 4073): DatabaseHelper
,I/GAV2    ( 3114): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 1018): SIOP:: AP = 400
,D/BadgeProvider( 4073): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 4073): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4073): sendNotify, [notify] : null
D/BadgeProvider( 4073): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4073): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4073): update, [UpdateCount] : 1
,D/Launcher.Model( 1477): reloadBadges entered.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/Zygote  ( 4094): MountEmulatedStorage(),
E/Zygote  ( 4094): v2
I/libpersona( 4094): KNOX_SDCARD checking this for 10036,
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4094 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 4094): KNOX_SDCARD not a persona
D/Finsky  ( 3924): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/SELinux ( 4094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 3243:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
E/SELinux ( 4094): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/ActivityManager( 1018): Killing 3289:com.fmm.ds/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3319:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4094): TimaSignature is unavailable
,D/ActivityThread( 4094): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4117): MountEmulatedStorage()
,E/Zygote  ( 4117): v2
I/libpersona( 4117): KNOX_SDCARD checking this for 10142
I/libpersona( 4117): KNOX_SDCARD not a persona
,I/SELinux ( 4117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4117 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 4117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3029:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4117): TimaSignature is unavailable
,D/ActivityThread( 4117): Added TimaKeyStore provider
,D/AndroidRuntime( 4088): 
D/AndroidRuntime( 4088): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4088): CheckJNI is OFF
,D/AndroidRuntime( 4088): readGMSProperty: start
D/AndroidRuntime( 4088): readGMSProperty: already setted!!
D/AndroidRuntime( 4088): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4088): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4088): readGMSProperty: end
D/AndroidRuntime( 4088): addProductProperty: start
,W/ResourcesManager( 4117): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 3982): Sending signal. PID: 3982 SIG: 9
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_3243/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3289/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_3319/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_3029/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Settings( 3924): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3924): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Zygote  ( 4141): MountEmulatedStorage()
,E/Zygote  ( 4141): v2
I/libpersona( 4141): KNOX_SDCARD checking this for 1000
I/libpersona( 4141): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 4141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Process com.android.email (pid 3982)(adj 9) has died(33,658)
,I/SA      ( 4094): [SSP] onCreated
,E/AffinityControl( 4088): AffinityControl: registerfunction enter
,D/TimaKeyStoreProvider( 4141): TimaSignature is unavailable
,D/ActivityThread( 4141): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Volley  ( 3924): [591] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3924): [598] DiskBasedCache.clear: Cache cleared.
,D/AndroidRuntime( 4088): Calling main entry com.android.commands.pm.Pm
,D/Ads     ( 3924): Skipping gmscore version check
,E/Zygote  ( 4162): MountEmulatedStorage()
E/Zygote  ( 4162): v2
I/libpersona( 4162): KNOX_SDCARD checking this for 10141
I/libpersona( 4162): KNOX_SDCARD not a persona
,I/SELinux ( 4162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4162 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SA      ( 4094): [TPM] There is no property file
I/ActivityManager( 1018): Killing 3343:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3359:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #32
,I/SA      ( 4094): [SCU] isHaveSA() - false
I/SA      ( 4094): [TPM] getModelProperty : null
I/SA      ( 4094): [TPM] getCSCProperty : null
,I/SA      ( 4094): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4094): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4094): [DM] TFT FEATURE: false
,D/TimaKeyStoreProvider( 4162): TimaSignature is unavailable
,D/ActivityThread( 4162): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3195:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/GAV2    ( 3269): Thread[GAThread,5,main]: No campaign data found.,
V/AlarmManager( 1018): waitForAlarm result :8
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserServi,ce( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131034113
,I/AMMetaDataParserService( 3648): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3648): took 0.905938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be3080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f7bac0 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4094): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4094): [DM] init START
I/SA      ( 4094): [DM] This device is not a Vodafone
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3648): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
W/ResourcesManager( 4162): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4162): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4162): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4162): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4180): MountEmulatedStorage()
I/libpersona( 4180): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4180): v2
I/libpersona( 4180): KNOX_SDCARD not a persona
,I/SELinux ( 4180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3410:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{117048714}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.827396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8be3080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fa1b38 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 4180): TimaSignature is unavailable
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/ActivityThread( 4180): Added TimaKeyStore provider
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3648): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/PackageManager( 1018): !@killApplicatoin: 10334, uninstall pkg
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10334 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 2929:com.example.hello/u0a334 (adj 0): stop com.example.hello cause uninstall pkg
,W/ResourceType( 4094): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4094): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1018): failed to open /acct/uid_10013/pid_3343/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10056/pid_3359/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_3195/cgroup.procs: No such file or directory
,W/ResourceType( 4094): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4094): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4094): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/WindowState( 1018): WIN DEATH: Window{3f98e3ca u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1018): Focus left window: 2929
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,W/PackageSettings( 1018): Skipping PackageSetting{2d6ee466 com.test.thalitest/10326} due to missing metadata
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101,
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.671300ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f6da78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa9580 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SA      ( 4094): [SCU] isHaveSA() - false
,I/SA      ( 4094): support phone number id : false
I/SA      ( 4094): [DM] Supports Ref Jpn : true
I/SA      ( 4094): [DM] init END
W/ActivityManager( 1018): Force removing ActivityRecord{13e9536f u0 com.example.hello/.MainActivity t2}: app died, no saved state,
,D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.641771ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f90848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fb6000 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/AMMetaDataParserService( 3648): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/libprocessgroup( 1018): failed to open /acct/uid_10058/pid_3410/cgroup.procs: No such file or directory
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 1.134687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f4fd28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8be2e40 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): Spurious death for ProcessRecord{3c865c4 2929:com.example.hello/u0a334}, curProc for 2929: null
I/AMMetaDataParserService( 3648): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/Launcher( 1477): onRestart, Launcher: 527516717
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10334 user=0: pkg removed
,D/Finsky  ( 3924): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3924): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.651250ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8fa9580 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f7ab50 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher( 1477): onStart, Launcher: 527516717
D/Launcher.HomeView( 1477): onStart
D/Launcher( 1477): onResume, Launcher: 527516717
D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/Launcher.HomeView( 1477): onResume
I/GFX raster( 3648): took 0.691458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f97d80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fb6000 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher( 1477): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/SecurityLogAgent( 4180): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4180): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4180): StateMachine : Current State = 1
D/SecurityLogAgent( 4180): BootReceiver : completed task. Failed to return wakelock . 
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3648): took 0.525677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8cf1980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8be2e40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3648): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,E/SamsungIME( 1769): mOCRHelper is null
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1668): Ignoring removeGeofence because network location is disabled.
,D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/SMD     (  292): DCD OFF
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SA      ( 4094): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4094): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/art     ( 4162): Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 109.367ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MenuAppsGridFragment( 1477): onResume
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4094): [OR] onReceive END
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648,): Resource data:2131165203
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/BadgeProvider( 4073): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ResourcesManager( 3648): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3648): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 3.677344ms for 0*0 texture 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/InputDispatcher( 1018): Focus entered window: 1477
,I/SA      ( 4094): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4094): [ODM] queryOpenData(key= GEO_IP )
,E/Zygote  ( 4210): MountEmulatedStorage()
I/libpersona( 4210): KNOX_SDCARD checking this for 10148
E/Zygote  ( 4210): v2
I/libpersona( 4210): KNOX_SDCARD not a persona
,I/SELinux ( 4210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4210 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1477): log_dcs ThreadedRenderer::initialize entered! 
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/ActivityManager( 1018): Killing 2183:com.android.defcontainer/u0a3 (adj 15): empty #31
I/SELinux ( 4210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4210): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CalendarProvider2( 3941): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/Launcher( 1477): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/GFX generate_partition_tables( 3648): took 17.296145ms for 0*0 texture 0
I/GFX raster( 3648): took 21.562706ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f96380 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb9167c98 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3648): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/SA      ( 4094): getMccForGalaxyJpn step2 GEO_IP MCC : 260
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
I/SA      ( 4094): [LBE] REF_JPN : true
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
I/SA      ( 4094): [BDC] create
V/EnterpriseBillingPolicy( 1018): uID is 10334
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,I/GFX construct_block_size_descriptor_2d second part( 3648): took 2.540208ms for 0*0 texture 0
D/TaskPersister( 1018): removeObsoleteFile: deleting file=2_task.xml
,I/GFX generate_partition_tables( 3648): took 5.284687ms for 0*0 texture 0
,I/GFX raster( 3648): took 8.927603ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f80ce8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8f80d90 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/BadgeProvider( 4073): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4073): sendNotify, [notify] : null
D/BadgeProvider( 4073): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4073): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4073): update, [UpdateCount] : 1
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,I/AMMetaDataParserService( 3648): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1018): uID is 10334,
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0,
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/TimaKeyStoreProvider( 4210): TimaSignature is unavailable
,D/ActivityThread( 4210): Added TimaKeyStore provider
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
,D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb94071b0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3648): took 0.686146ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f80ce8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9167298 counterpartCT=4 counterpartW=80 counterparth=80
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3648): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/ActivityManager( 1018): Killing 3462:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 2929 uid 10334
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1439): empty dynamic service
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/SamsungIME( 1769): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX raster( 3648): took 0.753125ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f80ce8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9167298 counterpartCT=4 counterpartW=80 counterparth=80
,I/Process ( 4117): Sending signal. PID: 4117 SIG: 9
,I/AMMetaDataParserService( 3648): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/OpenGLRenderer( 1477): SFEffectCache::get: create texture(0xa2175724): name, size, mSize = 34, 84660, 215432
,D/Finsky  ( 3924): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3648): took 0.638334ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f8f0d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9167298 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3648): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/System.out( 3924): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3924): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3924): (HTTPLog)-Static: isShipBuild true
I/System.out( 3924): (HTTPLog)-Thread-603-925940633: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3924): (HTTPLog)-Static: isSBSettingEnabled false
,E/        ( 3648): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3648): took 0.639115ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3648): Bitmap=0xb8f8f0d0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb9167298 counterpartCT=4 counterpartW=80 counterparth=80
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10026
,I/AMMetaDataParserService( 3648): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 36072(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 22MB/33MB, paused 34.358ms total 485.308ms
,I/art     ( 1018): WaitForGcToComplete blocked for 126.538ms for cause Explicit
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/PackageManager( 1018): delete codoeFile: 
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10334, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10334 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{117048714}
,E/SQLiteLog( 4210): (284) automatic index on shooting_modes(title_id)
,D/AndroidRuntime( 4088): Shutting down VM
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Process com.android.exchange (pid 4117)(adj 13) has died(54,652)
,I/ActivityManager( 1018): Displayed Component not be shown by security: +625ms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/Finsky  ( 3924): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3648): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
,I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging,
W/ResourcesManager( 3648): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
W/ResourcesManager( 3648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3648): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3648): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4237): MountEmulatedStorage(),
I/libpersona( 4237): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4237): v2
I/libpersona( 4237): KNOX_SDCARD not a persona,
I/SELinux ( 4237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4237 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 9804(507KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 5.229ms total 207.517ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4237): TimaSignature is unavailable
,I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityThread( 4237): Added TimaKeyStore provider
,D/SensorService( 1018): [SO] currT = 40991208000, prevT = 40541088000, diff = 450120000, [-0.383 0.057 9.902]
,D/SensorService( 1018): [SO] -0.383 0.057 9.902
D/SensorService( 1018): [SO] [100 -> 255]
,I/SA      ( 4094): [DBMV2] getEmailID
,I/SA      ( 4094): [DBMV2] getDataV02ForItems
,I/SA      ( 4094): [SSP] query invoked
,I/SA      ( 4094): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3648): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4094): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4094): [BDC] destroy
,I/ActivityManager( 1018): Killing 3481:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/AMMetaDataParserService( 3648): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3648): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3648): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3648): getResourcePackageName:assistant
I/AMMetaDataParserService( 3648): Resource data:2131099648
I/AMMetaDataParserService( 3648): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3648): getResourceTypeNamexml
,W/art     ( 4088): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/AMMetaDataParserService( 3648): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 3269:com.google.android.gm/u0a99 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3648): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3004): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3648): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SQLiteLog( 3648): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3648): (3850) statement aborts at 19: [INSERT INTO AMData(actname,amicon,appname,id,amtitle,amstate,amintent,amlabel) VALUES (?,?,?,?,?,?,?,?)] disk I/O error,
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SQLiteDatabase( 3648): Error inserting actname=com.android.mms.ui.ComposeMessageMms amicon=[B@5b1d48a appname=com.android.mms id=1451921645105 amtitle=Add from contacts amstate=1 amintent=com.android.mms.ui.composemessagefragment.attachcontacts amlabel=2131493291
E/SQLiteDatabase( 3648): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3648): 	,at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3648): ,	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3648): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3648): 	at android.os.HandlerThread.run(HandlerThread.java:61),
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/FileUtils( 2674): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 3114): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3114): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3648): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
E/SQLiteLog( 3648): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,E/SQLiteDatabase( 3648): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3648): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3648): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/System.err( 3648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.,err( 3648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3648): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3648): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3648): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3648): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3648): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/IcingCorporaProvider( 3114): Exception thrown from registerCorpora
E/IcingCorporaProvider( 3114): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 3114): 	at beg.a(PG:301)
E/IcingCorporaProvider( 3114): 	at bed.a(PG:171)
E/IcingCorporaProvider( 3114): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.b(PG:415)
E/IcingCorporaProvider( 3114): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.k(PG:369)
E/IcingCorporaProvider( 3114): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:286)
E/IcingCorporaProvider( 3114): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/IcingCorporaProvider( 3114): 	at android.content.ContentResolver.update(ContentResolver.java:1386)
E/IcingCorporaProvider( 3114): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 3114): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 3114): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 3114): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 3114): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 3114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 3114): 	at android.os.Looper.loop(Looper.java:145)
E/IcingCorporaProvider( 3114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 3114): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/IcingCorporaProvider( 3114): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/IcingCorporaProvider( 3114): 	at bea.a(PG:382)
E/IcingCorporaProvider( 3114): 	at beg.i(PG:325)
E/IcingCorporaProvider( 3114): 	at bef.call(PG:156)
E/IcingCorporaProvider( 3114): 	at beg.a(PG:299)
E/IcingCorporaProvider( 3114): 	... 14 more
W/IcingCorporaProvider( 3114): Corpora registration failed
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextW,rapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/ActivityManager( 1018): Killing 3526:com.google.android.talk/u0a102 (adj 15): empty #31
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)

```
