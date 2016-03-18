#### Test 62548124b8ccb9f_thali03_samsung-SM-N910C Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 8703): TimaSignature is unavailable
D/ActivityThread( 8703): Added TimaKeyStore provider
D/ResourcesManager( 8703): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
D/TMNetworkReceiver( 8703): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() Exit 
D/TMNetworkReceiver( 8703): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
D/TMSLogRemovalReceiver( 8703): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 8703): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 8703): TMLogRemovalReceiver.onReceive() Exit
--------- beginning of system
I/ActivityManager( 3527): Killing 7209:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
V/UserPresentBroadcastReceiver( 4673): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/BluetoothNotiBroadcastReceiver( 8030): onReceive
D/AuthorizationBluetoothService( 4673): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8725): MountEmulatedStorage()
I/libpersona( 8725): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8725): v2
I/libpersona( 8725): KNOX_SDCARD not a persona
I/SELinux ( 8725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=8725 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 8725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 2882): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 754us total 12.323ms
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/TimaKeyStoreProvider( 8725): TimaSignature is unavailable
D/ActivityThread( 8725): Added TimaKeyStore provider
I/System.out( 3527): AsyncTask #3 calls detatch()
W/System.err( 3527): java.io.IOException: Not Found
W/System.err( 3527): 	at a.d.b(Unknown Source)
W/System.err( 3527): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3527): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3527): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3527): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 850us total 11.410ms
D/ResourcesManager( 8725): creating new AssetManager and set to /system/priv-app/DeviceTest/DeviceTest.apk
W/ResourcesManager( 8725): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 310us total 9.282ms
D/FactoryTestApp( 8725): [ProtectedFactoryTestBroadcastReceiver$onReceive](8725) onReceive action=android.intent.action.SECPHONE_READY
I/FactoryTestApp( 8725): [ProtectedFactoryTestBroadcastReceiver$onReceive](8725) android.intent.action.SECPHONE_READY
D/FactoryTest( 8725): User mode
I/KLMS-2.4.521: ( 8166): KLMSAbstractReciever(): onReceive(): Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.listner.ContainerReceiver (has extras) } | timestamp: Fri Mar 18 17:15:29 GMT+01:00 2016
I/KLMS-2.4.521: ( 8166): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: ( 8166): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: ( 8166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: ( 8166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: ( 8166): KLMSIntentService(): onHandleIntent().START: Intent { act=com.samsung.action.knox.kap.KAP_NOTIFICATION flg=0x10 pkg=com.samsung.klmsagent cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: ( 8166): KLMSIntentService(): RP_MODE_NOTIFY
I/KLMS-2.4.521: ( 8166): B2C-ContainerStateImpl(): uploadRPMode().Start.
D/QuickSNote( 7428): PenGestureReceiver onReceive - Pen Insert Action : true.
I/KLMS-2.4.521: ( 8166): B2C-ContainerStateImpl(): checkKNOXLicenseStatus().No activation record is found when container license check came.
D/TimaService( 3527): BroadcastReceiver - action:  com.samsung.action.knox.klms.KLMS_RP_NOTIFICATION
D/TimaService( 3527): handleLicenseStatus - notiTrigger: 3, licenseStatus: false
I/KLMS-2.4.521: ( 8166): KLMSIntentService(): onDestroy()
D/QuickSNote( 7428): PenGestureReceiver onReceive - PenInsert recieved.
I/ActivityManager( 3527): Killing 7361:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
E/TLC_TZ_KEYSTORE: ( 3527): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 3527): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 3527): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 3527): root = 0, root_strlen = 1
I/TLC_TZ_KEYSTORE: ( 3527): process = ffffffff000000000000000000000013, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): input max_sendmsg_size = 1080
I/TZ: mc_tlc_communication( 3527): input max_recvmsg_size = 1080
I/TZ: mc_tlc_communication( 3527): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3527): process = ffffffff000000000000000000000013, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): aligned max_sendmsg_size = 1088
I/TZ: mc_tlc_communication( 3527): aligned max_recvmsg_size = 1088
I/TZ: mc_tlc_communication( 3527): device_id = 0x0
I/TZ: mc_tlc_communication( 3527): tlc_open() was called
I/TZ: mc_tlc_communication( 3527): Opening MobiCore device
I/TZ: mc_tlc_communication( 3527): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 3527): Opening the session
I/PageBuddyNotiSvc( 4916): Intent received : action=com.samsung.pen.INSERT
I/PageBuddyNotiSvc( 4916): service running
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/TZ: mc_tlc_communication( 3527): tlc_open() succeeded
I/TLC_TZ_KEYSTORE: ( 3527): ctx = 0x99f3d470, comm = 0xaeea8460, sendmsg = 0xb4ec6a00, recvmsg = 0xb4ec6e40
I/TZ_init: ( 3527): TZ_init: sending initialization request...
E/TZ_init: ( 3527): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 3527): trustlet initialization failed
I/TZ_init: ( 3527): TZ_init_START...
I/TZ_init: ( 3527): TZ_init_with_data: sending initialization request...
E/Zygote  ( 8743): MountEmulatedStorage()
E/Zygote  ( 8743): v2
I/libpersona( 8743): KNOX_SDCARD checking this for 10161
I/libpersona( 8743): KNOX_SDCARD not a persona
I/SELinux ( 8743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.sec.android.app.SPenKeeper for broadcast com.sec.android.app.SPenKeeper/.SPenKeeperReceiver: pid=8743 uid=10161 gids={50161, 9997, 1028} abi=armeabi-v7a
I/SELinux ( 8743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/TZ_init: ( 3527): TZ_init: successful initialization
I/TZ: mc_tlc_communication( 3527): tlc_close() was called
I/TZ: mc_tlc_communication( 3527): Closing the session
I/TZ: mc_tlc_communication( 3527): Freeing message buffer
I/TZ: mc_tlc_communication( 3527): Closing MobiCore device
D/TimaKeyStoreProvider( 8743): TimaSignature is unavailable
D/ActivityThread( 8743): Added TimaKeyStore provider
I/TZ: mc_tlc_communication( 3527): tlc_close() succeeded
E/TLC_TZ_KEYSTORE: ( 3527): Count : 1, Ret : 0
I/TLC_TZ_KEYSTORE: ( 3527): TZ_KEYSTORE_set_license_status
I/TLC_TZ_KEYSTORE: ( 3527): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 3527): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 3527): root = 0, root_strlen = 1
I/TLC_TZ_KEYSTORE: ( 3527): process = ffffffff000000000000000000000013, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): input max_sendmsg_size = 1080
I/TZ: mc_tlc_communication( 3527): input max_recvmsg_size = 1080
I/TZ: mc_tlc_communication( 3527): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3527): process = ffffffff000000000000000000000013, process_strlen = 32
I/TZ: mc_tlc_communication( 3527): aligned max_sendmsg_size = 1088
I/TZ: mc_tlc_communication( 3527): aligned max_recvmsg_size = 1088
I/TZ: mc_tlc_communication( 3527): device_id = 0x0
I/TZ: mc_tlc_communication( 3527): tlc_open() was called
I/TZ: mc_tlc_communication( 3527): Opening MobiCore device
I/TZ: mc_tlc_communication( 3527): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 3527): Opening the session
D/ResourcesManager( 8743): creating new AssetManager and set to /system/app/SPenKeeper/SPenKeeper.apk
I/TZ: mc_tlc_communication( 3527): tlc_open() succeeded
I/TLC_TZ_KEYSTORE: ( 3527): ctx = 0x99f3d470, comm = 0xaeea8460, sendmsg = 0xb4ec6a00, recvmsg = 0xb4ec6e40
I/TLC_TZ_KEYSTORE: set_license_status: ( 3527): TZ_KEYSTORE_set_license_status_START
I/TLC_TZ_KEYSTORE: set_license_status: ( 3527): TZ_KEYSTORE_set_license_status_END
I/TZ: mc_tlc_communication( 3527): tlc_close() was called
I/TZ: mc_tlc_communication( 3527): Closing the session
I/TZ: mc_tlc_communication( 3527): Freeing message buffer
I/TZ: mc_tlc_communication( 3527): Closing MobiCore device
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
I/TZ: mc_tlc_communication( 3527): tlc_close() succeeded
E/Zygote  ( 8758): MountEmulatedStorage()
I/libpersona( 8758): KNOX_SDCARD checking this for 10056
E/Zygote  ( 8758): v2
I/libpersona( 8758): KNOX_SDCARD not a persona
I/SELinux ( 8758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 8758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8758 uid=10056 gids={50056, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
E/SELinux ( 8758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Killing 8074:com.sec.pcw.device/1000 (adj 13): bgCount ##31
D/ResourcesManager( 8184): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/TimaKeyStoreProvider( 8758): TimaSignature is unavailable
D/ActivityThread( 8758): Added TimaKeyStore provider
D/ResourcesManager( 8758): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 8758): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8758): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8758): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8758): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8758): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/TranscodeReceiver( 8758): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/videowall-Global( 8758): core_num = 8
W/System.err( 8758): Fail to load library. Disable videowall.
I/ActivityManager( 3527): Killing 8090:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
D/daemonapp( 3780): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3780): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 3780): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3780): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3780): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3780): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1458339300000
D/daemonapp( 3780): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1458317730215
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 3780): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 3780): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3780): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3780): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 3780): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 3780): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
W/ContextImpl( 8030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/AndroidRuntime( 8740): 
D/AndroidRuntime( 8740): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8740): CheckJNI is OFF
D/AndroidRuntime( 8740): readGMSProperty: start
D/AndroidRuntime( 8740): readGMSProperty: already setted!!
D/AndroidRuntime( 8740): readGMSProperty: end
D/AndroidRuntime( 8740): addProductProperty: start
D/LocalBluetoothProfileManager( 8030): Adding local A2DP profile
D/LocalBluetoothProfileManager( 8030): Adding local HEADSET profile
E/BluetoothHeadset( 8030): BTStateChangeCB is registed
E/BluetoothHeadset( 8030): BluetoothHeadset service is binded
W/ContextImpl( 8030): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 8030): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 8030): PANU : true
D/LocalBluetoothProfileManager( 8030): Adding local MAP profile
D/BluetoothMap( 8030): Create BluetoothMap proxy object
W/LocalBluetoothProfileManager( 8030): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 8030): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 8030): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 8030): onReceive
D/BluetoothA2dp( 8030): Proxy object connected
D/A2dpProfile( 8030): Bluetooth service connected
D/BluetoothAdapterService( 5622): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24451695
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
D/HeadsetProfile( 8030): Bluetooth service connected
D/Bluetoothsap( 8030): BluetoothSAP Proxy object connected
D/SapProfile( 8030): Bluetooth service connected
D/Bluetoothsap( 8030): getConnectedDevices()
D/AuthorizationBluetoothService( 4673): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/BluetoothInputDevice( 8030): Proxy object connected
D/HidProfile( 8030): Bluetooth service connected
E/Zygote  ( 8783): MountEmulatedStorage()
I/libpersona( 8783): KNOX_SDCARD checking this for 10135
E/Zygote  ( 8783): v2
I/libpersona( 8783): KNOX_SDCARD not a persona
I/SELinux ( 8783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 8783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8783): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=8783 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BluetoothPan( 8030): BluetoothPAN Proxy object connected
D/PanProfile( 8030): Bluetooth service connected
D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothMap( 8030): Proxy object connected
D/MapProfile( 8030): Bluetooth service connected
D/BluetoothPbap( 8030): Proxy object connected
D/PbapServerProfile( 8030): Bluetooth service connected
D/TimaKeyStoreProvider( 8783): TimaSignature is unavailable
D/ActivityThread( 8783): Added TimaKeyStore provider
W/BluetoothAdapter( 5622): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 5622): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 5622): bindListen(), new LocalSocket 
D/BluetoothSocket( 5622): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5622): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1827765e
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/AffinityControl( 8740): AffinityControl: registerfunction enter
D/AndroidRuntime( 8740): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3527): inState():  stateMachine is null !!
I/PersonaManagerService( 3527): PersonaId don't exist
I/ActivityManager( 3527): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3527): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService( 3527): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3527  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3527): mDVFSHelper.acquire()
D/FocusedStackFrame( 3527): Set to : 0
E/libEGL  ( 4005): call to OpenGL ES API with no current context (logged once per thread)
D/Launcher.HomeView( 4005): onPause
D/AndroidRuntime( 8740): Shutting down VM
D/Launcher( 4005): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 2851): id=11 createSurf (1x1),1 flag=404, uhalitest
I/art     ( 3527): Explicit concurrent mark sweep GC freed 147154(8MB) AllocSpace objects, 3(1812KB) LOS objects, 24% free, 49MB/65MB, paused 2.070ms total 120.448ms
D/BluetoothSocket( 5622): channel: 12
I/BtOppRfcommListener( 5622): Accept thread started.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 8783): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  ( 8805): MountEmulatedStorage()
E/Zygote  ( 8805): v2
I/libpersona( 8805): KNOX_SDCARD checking this for 10208
I/libpersona( 8805): KNOX_SDCARD not a persona
I/SELinux ( 8805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=8805 uid=10208 gids={50208, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 8805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8805): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/MicrophoneInputStream( 4056): mic_close gfk@248595ca
I/WifiStateMachine( 3527): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine( 3527): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3527): CMD_RSSI_POLL : out!
E/MTPJNIInterface( 8667): Status for mount/Unmount :removed
E/MTPJNIInterface( 8667): SDcard is not available
V/ActivityThread( 4005): updateVisibility : ActivityRecord{46c84d2 token=android.os.BinderProxy@82a8e94 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 8805): TimaSignature is unavailable
D/ActivityThread( 8805): Added TimaKeyStore provider
V/AudioPolicyManager( 2859): stopInput() input 17
V/AudioPolicyManager( 2859): releaseInput() 17
V/AudioPolicyManager( 2859): closeInput(17)
I/HotwordRecognitionRnr( 4056): Hotword detection finished
I/HotwordRecognitionRnr( 4056): Stopping hotword detection.
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager( 3527): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3527): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/AudioHardwareTinyALSA( 2859): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2859): Close mHandle:ae8320c0
I/AudioHardwareTinyALSA( 2859): closeInputStream +
D/TinyUCM ( 2859): Disable Input dev(0x80000004)
D/Launcher.HomeView( 4005): onStop
V/ActivityThread( 4005): updateVisibility : ActivityRecord{46c84d2 token=android.os.BinderProxy@82a8e94 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
E/        ( 8667): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
D/TinyUCM ( 2859): set channel: None
D/AudioHardwareTinyALSA( 2859): Entering AudioStreamInALSA standby mode
V/AudioPolicyManager( 2859): releaseInput() exit
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/AutomaticBrightnessController( 3527): mCallbacks.updateBrightness()
D/DisplayPowerController( 3527): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3527): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/MTPJNIInterface( 8667): Status for mount/Unmount :removed
E/MTPJNIInterface( 8667): SDcard is not available
E/SQLiteLog( 8667): (21) API call with NULL database connection pointer
E/SQLiteLog( 8667): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 8667): (21) API call with NULL database connection pointer
E/SQLiteLog( 8667): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 8667): (21) API call with NULL database connection pointer
E/SQLiteLog( 8667): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 8667): (21) API call with NULL database connection pointer
E/SQLiteLog( 8667): (21) misuse at line 105958 of [9491ba7d73]
W/MTPRx   ( 8667): notification from stack 2
D/        ( 8667): [mtp_init_device] Library open with 32 bits.
D/        ( 8667): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 8667): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 8667): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 8667):  [sua_support_present:1277] returning false 
D/        ( 8667): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
D/ResourcesManager( 8805): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk

```
