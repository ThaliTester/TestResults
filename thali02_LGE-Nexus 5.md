#### Test 61703351a2a4153_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/bt_hwcfg( 2328): Chipset BCM4335C0
D/bt_hwcfg( 2328): Target name = [BCM4335C0]
I/bt_hwcfg( 2328): Found patchfile: /vendor/firmware//bcm4335c0.hcd
W/DriveInitializer( 1711): Awaiting to be initialized
V/OneTimeInitializerReceiver( 2450): OneTimeInitializerReceiver.onReceive
W/DriveInitializer( 1711): Background init thread started
V/OneTimeService( 2450): OneTimeService.onHandleIntent
D/TelephonyNetworkFactory( 1241): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/DctController( 1241): [DctController] EVENT_PHONE1_RADIO_OFF.
D/TelephonyDebugService( 1241): TelephonyDebugService()
,--------- beginning of system
D/WifiService(  760): New client listening to asynchronous messages
I/ActivityManager(  760): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2487 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 181us total 13.472ms
D/BluetoothHeadset( 1241): Proxy object connected
D/DctController( 1241): [DctController] DataStateReceiver: phoneId= 0
D/DctController( 1241): [DctController] DataStateReceiver: ignore invalid subId=-1
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 9.025ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 184us total 7.745ms
D/GpsLocationProvider(  760): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
D/GpsLocationProvider(  760): SIM MCC/MNC is still not available
D/GpsLocationProvider(  760): received SIM realted action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/MmsService( 1241): mReceiver action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/Telephony( 1241): : SUBINFO_RECORD_UPDATED : 4.
D/GpsLocationProvider(  760): SIM MCC/MNC is still not available
I/MmsService( 1241): MmsConfigManager.loadInBackground(): mcc/mnc: 0/0
E/PhoneInterfaceManager( 1241): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
E/MmsService( 1241): MmsConfigManager.load -- empty getActiveSubInfoList
I/Telephony( 1241): PstnIncomingCallNotifier: Registering: Handler (com.android.internal.telephony.gsm.GSMPhone) {1add0f20}
I/ActivityManager(  760): Killing 1950:com.google.android.music:main/u0a60 (adj 15): empty #17
I/art     ( 1474): Explicit concurrent mark sweep GC freed 3053(119KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 2.810ms total 24.268ms
I/art     ( 1711): Explicit concurrent mark sweep GC freed 46274(3MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 21MB/36MB, paused 1.156ms total 72.366ms
W/SQLiteConnectionPool( 1711): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/AndroidRuntime( 2504): 
D/AndroidRuntime( 2504): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2504): CheckJNI is OFF
W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_1950/cgroup.procs: No such file or directory
I/RlzPingService( 1494): Setting next ping for 1457698897161
I/bt_hwcfg( 2328): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2328): Settlement delay -- 100 ms
I/bt_hwcfg( 2328): Setting fw settlement delay to 100 
W/DriveInitializer( 1711): Background init thread ended
D/AndroidRuntime( 2504): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2504): Shutting down VM
I/bt_hwcfg( 2328): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2328): Setting local bd addr to 34:FC:EF:11:AE:67
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2538 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  760): Killing 1809:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
I/bt_hwcfg( 2328): vendor lib fwcfg completed
I/bt-btu  ( 2328): btu_task received preload complete event
I/        ( 2328): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2328): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2328): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2328): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2328): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2328): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2328): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2328): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2328): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2328): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2328): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2328): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2328): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2328): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2328): BTE_InitTraceLevels -- TRC_BTIF
W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_1809/cgroup.procs: No such file or directory
I/ContactAccountLoggerTas( 1348): canRun() : Opted Out
D/MtpService(  913): updating state; isCurrentUser=true, mMtpLocked=false
I/ActivityManager(  760): Killing 2072:com.android.musicfx/u0a15 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2072/cgroup.procs: No such file or directory
E/SQLiteLog(  913): (283) recovered 75 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
I/MicrophoneInputStream( 1348): mic_close gfk@9b47537
I/WebViewFactory( 2538): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2560 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/LibraryLoader( 2538): Time to load native libraries: 1 ms (timestamps 5720-5721)
I/LibraryLoader( 2538): Expected native library version number "",actual native library version number ""
W/MediaScanner(  913): Error opening directory '/oem/media/', skipping: No such file or directory.
V/WebViewChromiumFactoryProvider( 2538): Binding Chromium to main looper Looper (main, tid 1) {3b68cfde}
I/LibraryLoader( 2538): Expected native library version number "",actual native library version number ""
I/chromium( 2538): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/bt-btm  ( 2328): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 2328): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
I/BrowserStartupController( 2538): Initializing chromium process, singleProcess=true
I/HotwordRecognitionRnr( 1348): Hotword detection finished
W/art     ( 2538): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2538): ApplicationContext is null in ApplicationStatus
I/HotwordRecognitionRnr( 1348): Stopping hotword detection.
W/chromium( 2538): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2538): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2538): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2538): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1c96:true
I/iu.UploadsManager( 1711): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/art     ( 2538): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2538): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2538): CordovaWebView is running on device made by: LGE
E/UpdateRequestReceiver( 2560): ignoring update request
W/art     ( 2538): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2538): Attempt to remove local handle scope entry from IRT, ignoring
E/UpdateRequestReceiver( 2560): ignoring update request
E/UpdateRequestReceiver( 2560): ignoring update request
I/art     (  760): Explicit concurrent mark sweep GC freed 11674(534KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 933us total 56.473ms
D/OpenGLRenderer( 2538): Render dirty regions requested: true
D/Atlas   ( 2538): Validating map...
E/UpdateRequestReceiver( 2560): ignoring update request
W/chromium( 2538): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/UpdateRequestReceiver( 2560): ignoring update request
E/bt-btif ( 2328): Calling BTA_HhEnable
E/bt-btif ( 2328): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2328): Address is:34:FC:EF:11:AE:67
E/UpdateRequestReceiver( 2560): ignoring update request
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
I/iu.UploadsManager( 1711): End new media; added: 0, uploading: 0, time: 109 ms
D/BluetoothAdapterProperties( 2328): Name is: Nexus 5
W/bt-smp  ( 2328): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2328): Plain text(LSB ~ MSB) = a8 3e 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2328): Encrypted text(LSB ~ MSB) = b8 cb b9 64 44 fb bb be eb ec af af f1 0e 3d 4e 
W/bt-btm  ( 2328): Stopping oneshot timer
D/BluetoothAdapterProperties( 2328): Scan Mode:20
D/BluetoothAdapterProperties( 2328): Discoverable Timeout:120
D/bte_conf( 2328): Device ID record 1 : primary
D/bte_conf( 2328):   vendorId            = 000f
D/bte_conf( 2328):   vendorIdSource      = 0001
D/bte_conf( 2328):   product             = 1200
D/bte_conf( 2328):   version             = 1436
D/bte_conf( 2328):   clientExecutableURL = 
D/bte_conf( 2328):   serviceDescription  = 
D/bte_conf( 2328):   documentationURL    = 
D/bte_conf( 2328): bte_load_did_conf no section named DID2.
W/BroadcastQueue(  760): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/BluetoothAdapterState( 2328): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2328): ScanMode =  20
D/BluetoothAdapterProperties( 2328): State =  11
D/BluetoothAdapterProperties( 2328): Setting state to 12
I/BluetoothAdapterState( 2328): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  760): Message: 60
I/BluetoothAdapterState( 2328): Entering On State
D/BluetoothPanServiceJni( 2328): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=true
D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=true
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 2328): onReceive
D/BluetoothManagerService(  760): Message: 40
D/BluetoothMapService( 2328): STATE_ON
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothMapService( 2328): Handler(): got msg=1
D/BluetoothAdapterProperties( 2328): Scan Mode:21
D/BluetoothAdapterProperties( 2328): Discoverable Timeout:120
D/BluetoothMapMasInstance( 2328): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 2328): MAS initSocket()
D/BluetoothMapMasInstance( 2328):   masId = 00
D/BluetoothMapMasInstance( 2328):   msgTypes = 0e
D/BluetoothMapMasInstance( 2328):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2328):   SDP string = 000eSMS/MMS
I/Telecom ( 1204): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2328): getBluetoothService() called with no BluetoothManagerCallback
D/HeadsetStateMachine( 2328): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2328): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2328): mNumber:  mType: 128
D/HeadsetStateMachine( 2328): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2328): terminateScoUsingVirtualVoiceCall:No present call to terminate
I/GoogleHttpClient( 1474): GMS http client unavailable, use old client
V/MediaScanner(  913): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@34cd02a7
V/MediaScanner(  913): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@34cd02a7
V/BluetoothMapMasInstance( 2328): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2328): Accepting socket connection...
E/bt_h4   ( 2328): vendor lib postload completed
I/OpenGLRenderer( 2538): Initialized EGL, version 1.4
D/OpenGLRenderer( 2538): Enabling debug mode 0
I/ActivityManager(  760): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2630 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +591ms (total +14s239ms)
W/BindingManager( 2538): Cannot call determinedVisibility() - never saw a connection for the pid: 2538
W/ResourcesManager( 2630): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2630): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/chromium( 2538): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  760): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2650 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  760): Killing 2127:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,D/JsMessageQueue( 2538): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2538): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2127/cgroup.procs: No such file or directory
,D/QcrilMsgTunnelAutoboot( 2650): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 2650): onCreate method
,D/QcrilMsgTunnelIfaceManager( 2650): : Instantiated
,V/QcrilMsgTunnelSocket( 2650): Starting QcRil Sender & Receiver threads
,D/QcrilMsgTunnelIfaceManager( 2650):  Registered for UNSOL OEM HOOK Responses to deliver external apps
,I/QcrilMsgTunnelSocket( 2650): Connected to 'qmux_radio/rild_oem0' socket
,D/jxcore_app_log( 2538): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
,W/jxcore-log( 2538): Initializing JXcore engine
W/jxcore-log( 2538): JXcore engine is ready
,W/Thread-246( 2672): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9419]" dev="sockfs" ino=9419 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-246( 2672): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-246( 2672): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8532]" dev="sockfs" ino=8532 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-246( 2672): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16104]" dev="sockfs" ino=16104 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,D/FileApkUtils( 1711): Spent 29ms computing apk sha1.
,D/FileApkUtils( 1711): Module already staged or being staged:chimera-modules/MapsModule.apk
,W/jxcore-log( 2538): Starting JXcore engine
I/art     ( 1711): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/InstanceID/Rpc( 1711): Found 10008
,D/DexOptUtils( 1711): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1711): Keeping up-to-date module: module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3
D/GmsModuleFndr( 1711): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1711): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 1711): Beginning module configuration check
,D/ChimeraCfgMgr( 1711): Module APKs unchanged, check complete
,D/GCM     ( 1711): COMPAT: Multi user ser=0 current=0
,D/GCM     ( 1619): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1711): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 1711): Checkin interval check for package: unspecified last checkin: 1457078428929 min interval config: 0 actual interval: 15669352
,W/jxcore-log( 2538): Platform android
W/jxcore-log( 2538): 
W/jxcore-log( 2538): Process ARCH arm
W/jxcore-log( 2538): 
,I/GCoreUlr( 1619): DispatchingService.onCreate()
,I/CheckinService( 1711): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 1711): onCreate
,D/SystemUpdateService( 1711): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1711): active receiver: enabled
,I/SystemUpdateService( 1711): showing system update notification
D/ChimeraCfgMgr( 1711): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/jxcore-log( 2538): JXcore Cordova bridge is ready!
I/jxcore-log( 2538): 
W/jxcore-log( 2538): JXcore engine is started
,I/CheckinService( 1711): Checking schedule, now: 1457094098324 next: 1457120595901
I/CheckinService( 1711): active receiver: disabled
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BootCompletedReceiver( 1711): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1711): Got an BootCompleted event.
,D/BootCompletedReceiver( 1711): Will NOT schedule AdAttestation signal task because it's disabled.
,V/AuthZen ( 1711): Handling intent: android.intent.action.BOOT_COMPLETED
,E/jxcore-log( 2538): >> LGE-Nexus 5
E/jxcore-log( 2538): 
,I/jxcore-log( 2538): Total memory 1946181632
I/jxcore-log( 2538): 
I/jxcore-log( 2538): Free memory 368398336
I/jxcore-log( 2538): 
I/jxcore-log( 2538): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2538): 
I/jxcore-log( 2538): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2538): 
,I/jxcore-log( 2538): userPath [ 'www', 'www' ]
I/jxcore-log( 2538): 
,D/AuthZenEventHandler( 1711): Handling event: android.intent.action.BOOT_COMPLETED
,I/jxcore-log( 2538): Size 1080 1776
I/jxcore-log( 2538): 
,I/jxcore-log( 2538): Screen Brightness 82
I/jxcore-log( 2538): 
,E/jxcore-log( 2538): Dummy Error Log.
E/jxcore-log( 2538): 
I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1711): retry (wakeup: false) in 3599931 ms
,I/GCoreUlr( 1619): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1711): Using Auth Proxy for data requests.
,I/AuthZen ( 1711): Fetching signing key...
,D/SystemUpdateService( 1711): onDestroy
,I/AuthZen ( 1711): Signing key fetched successfully!
,W/BaseAppContext( 1711): Using Auth Proxy for data requests.
,D/a       ( 1711): Opening database auth.proximity.permit_store...
,W/GCoreFlp( 1619): No location to return for getLastLocation()
W/FusedLocationProvider( 1619): location=null
,W/Auth    ( 1619): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/GCoreFlp( 1619): No location to return for getLastLocation()
,W/FusedLocationProvider( 1619): location=null
,D/AuthZenTransactionCache( 1711): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1711): Clearing transaction cache
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1619): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1619): Unbound from all location providers
I/GCoreUlr( 1619): Place inference reporting - stopped
,I/GCoreUlr( 1619): DispatchingService.onDestroy()
I/GCoreUlr( 1619): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1619): Unbound from all location providers
I/GCoreUlr( 1619): Place inference reporting - stopped
,D/PersistentNotificationBroadcastReceiver( 1619): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2698 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2698): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2698): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2698): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 3692(162KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 250us total 18.108ms
,I/jxcore-log( 2538): getBuffer is called!!!!
I/jxcore-log( 2538): 
,W/System  ( 2698): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2698): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 2698): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 2755): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-227352880.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-227352880.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 2755): dex2oat took 38.997ms (threads: 4)
,W/InstanceID/Rpc( 2698): Found 10008
,I/art     (  760): Explicit concurrent mark sweep GC freed 19805(925KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 959us total 50.342ms
,V/Babel   ( 1993): babel boot account: thalitester@gmail.com
,I/ActivityManager(  760): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2826 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 1993): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 1993): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1993): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1993): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 1993): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 1993): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  760): Killing 2023:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,I/FitnessApp( 2826): Initializers took 0 milliseconds
,W/libprocessgroup(  760): failed to open /acct/uid_10067/pid_2023/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2186:com.android.vending/u0a16 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10016/pid_2186/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2849 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2280:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10076/pid_2280/cgroup.procs: No such file or directory
,I/Gmail   ( 2849): getAccountsCursor
,D/ActivityThread( 2849): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2872 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2849): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 2849): getAccountsCursor
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2849): Observing account changes for notifications
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2911 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Exchange( 2872): EasService.onCreate
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2235): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/Exchange( 2872): RestartPingTask
,I/GAV2    ( 2235): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1711): Google Analytics 8.4.89 is starting up.
,I/Exchange( 2872): RestartPingsTask did not start any pings.
I/Exchange( 2872): PSS stopIfIdle
I/Exchange( 2872): PSS has no active accounts; stopping service.
,E/ActivityThread( 2849): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1525e397 that was originally bound here
E/ActivityThread( 2849): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1525e397 that was originally bound here
E/ActivityThread( 2849): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2849): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2849): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2849): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2849): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2849): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2849): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2849): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2849): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2849): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2849): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2849): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2849): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2849): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2849): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/a       ( 2849): RuntimeException when trying to unbind from service
E/a       ( 2849): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@1525e397
E/a       ( 2849): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2849): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2849): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2849): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2849): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2849): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2849): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2849): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2849): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2849): (283) recovered 32 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 29664(2MB) AllocSpace objects, 34(544KB) LOS objects, 25% free, 22MB/30MB, paused 553us total 43.690ms
,I/Gmail   ( 2849): notifyAccountChanged
I/Gmail   ( 2849): getAccountsCursor
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2849): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2849): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/Finsky  ( 2911): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 2849): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2849): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/Finsky  ( 2911): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Gmail   ( 2849): getAccountsCursor
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 2911): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2911): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  760): Killing 2351:com.google.android.dialer/u0a10 (adj 15): empty #17
,D/Volley  ( 2911): [271] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2911): [278] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 2911): Skipping gmscore version check
,I/ActivityManager(  760): Killing 2378:com.android.keychain/1000 (adj 15): empty #18
,W/libprocessgroup(  760): failed to open /acct/uid_10010/pid_2351/cgroup.procs: No such file or directory
I/SystemBroadcastReceiver( 1078): Boot has been completed
,I/SystemBroadcastReceiver( 1078): toggleAppIcon() : FLAG_SYSTEM = true
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2378/cgroup.procs: No such file or directory
,D/Finsky  ( 2911): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2911): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2911): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2911): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/UserPresentBroadcastReceiver( 1619): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2977 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1371:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_1371/cgroup.procs: No such file or directory
,D/WifiService(  760): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2996 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 187us total 8.945ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 8.374ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 10.115ms
,D/CellBroadcastReceiver( 2996): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2996): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2996): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  760): Killing 2450:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10012/pid_2450/cgroup.procs: No such file or directory
,D/SIP     ( 1241): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  760): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3019 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 3019): Database version: 120
,I/art     (  760): Explicit concurrent mark sweep GC freed 8619(449KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/41MB, paused 910us total 49.139ms
,W/ResourcesManager( 3019): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3019): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3019): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3019): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f77517c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3019): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3019): GMSCore installation verified
,I/ConfigStore( 3019): Config Database version: 1
,I/MediaRouter( 3019): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 3019): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3019): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 3019): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3019): Using platform SSLCertificateSocketFactory
,W/ContextImpl( 2977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f07bd1:true
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2328): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 2977): Adding local A2DP profile
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2977): Adding local HEADSET profile
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2977): Adding local MAP profile
D/BluetoothMap( 2977): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2977): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2977): finishStartingService: stopping service
,D/BluetoothA2dp( 2977): Proxy object connected
D/A2dpProfile( 2977): Bluetooth service connected
,D/BluetoothHeadset( 2977): Proxy object connected
,D/HeadsetProfile( 2977): Bluetooth service connected
,D/BluetoothInputDevice( 2977): Proxy object connected
D/HidProfile( 2977): Bluetooth service connected
,D/BluetoothPan( 2977): BluetoothPAN Proxy object connected
D/PanProfile( 2977): Bluetooth service connected
D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMap( 2977): Proxy object connected
D/MapProfile( 2977): Bluetooth service connected
D/BluetoothMap( 2977): getConnectedDevices()
,V/BluetoothMapService( 2328): getConnectedDevices()
,D/BluetoothPbap( 2977): Proxy object connected
,D/PbapServerProfile( 2977): Bluetooth service connected
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2328): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2328): Accept thread started.
,W/GCoreFlp( 1619): No location to return for getLastLocation()
,W/FusedLocationProvider( 1619): location=null
,D/GCM     ( 1619): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 3019): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  760): Killing 2487:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10014/pid_2487/cgroup.procs: No such file or directory
,E/SQLiteLog( 2261): (284) automatic index on view_events(_id)
,W/ResourcesManager( 1993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 1993): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 1993): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1993): Installed default security provider GmsCore_OpenSSL
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15c62488 mBinding = false
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
,D/BluetoothAdapterState( 2328): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2328): Setting state to 13
I/BluetoothAdapterState( 2328): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2328): onBluetoothDisable()
,I/BluetoothAdapterState( 2328): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2328): Scan Mode:20
,D/BluetoothAdapterState( 2328): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2328): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2328): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2328): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2328): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2328): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2328): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2328): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2328): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2328): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2328): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2328): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2328): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  760): Message: 60
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2328): onReceive
D/BluetoothMapService( 2328): STATE_TURNING_OFF
V/BluetoothMapService( 2328): Handler(): got msg=4
D/BluetoothMapService( 2328): MAP Service closeService in
D/BluetoothMapMasInstance( 2328): MAP Service shutdown
V/BluetoothMapService( 2328): MAP Service closeService out
,I/BtOppRfcommListener( 2328): stopping Accept Thread
,I/BtOppRfcommListener( 2328): BluetoothSocket listen thread finished
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: false pid=2538, uid=10278
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2538): ****TEST TOOK:  5151  ms ****
I/jxcore-log( 2538): 
I/jxcore-log( 2538): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2538): 
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/DockEventReceiver( 2977): finishStartingService: stopping service
,D/bt_userial( 2328): RX termination
W/bt_userial( 2328): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2328): Leaving userial_read_thread()
D/bt_userial( 2328): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2328): hw_epilog_process
,I/bt_userial_vendor( 2328): device fd = 53 close
,W/bt-btif ( 2328): ag scb idx 1 not allocated
E/bt-btif ( 2328): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2328): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2328): L2CAP - PSM: 0x0017 not found for deregistration
,I/GKI_LINUX( 2328): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2328): GKI_exit_task 0 done
I/GKI_LINUX( 2328): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2328): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterState( 2328): Stopping profile services that were post enabled
D/HeadsetService( 2328): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
D/HeadsetStateMachine( 2328): Exit Disconnected: -1
D/BluetoothHeadset(  760): Proxy object disconnected
D/BluetoothHeadset( 1204): Proxy object disconnected
D/BluetoothHeadset( 1204): Proxy object disconnected
D/A2dpService( 2328): Received stop request...Stopping profile...
D/A2dpStateMachine( 2328): Exit Disconnected: -1
D/BluetoothHeadset( 1241): Proxy object disconnected
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
,D/BluetoothA2dp(  760): Proxy object disconnected
D/HidService( 2328): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
D/HealthService( 2328): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
D/PanService( 2328): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
D/BtGatt.DebugUtils( 2328): handleDebugAction() action=null
D/BtGatt.GattService( 2328): Received stop request...Stopping profile...
D/BtGatt.GattService( 2328): stop()
D/BtGatt.AdvertiseManager( 2328): advertise clients cleared
D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
,D/BluetoothMapService( 2328): Received stop request...Stopping profile...
D/BluetoothMapService( 2328): stop()
,D/BluetoothMapEmailAppObserver( 2328): deinitObservers()
D/BluetoothMapEmailAppObserver( 2328): removeReceiver()
,D/BluetoothAdapterService( 2328): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eaa55bf
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/HeadsetStateMachine( 2328): Unbinding service...
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/BluetoothHeadsetServiceJni( 2328): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 2328): Cleaning up Bluetooth Handsfree callback object
,I/GKI_LINUX( 2328): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2328): GKI_exit_task 2 done
I/GKI_LINUX( 2328): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2328): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2328): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2328): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2328): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2328): Cleaning up Bluetooth Health object
V/BluetoothMapService( 2328): Handler(): got msg=4
D/BluetoothMapService( 2328): MAP Service closeService in
V/BluetoothMapService( 2328): MAP Service closeService out
W/BluetoothPanServiceJni( 2328): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2328): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 2328): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2328): Setting state to 10
I/BluetoothAdapterState( 2328): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 2328): cleanup()
D/BluetoothMapService( 2328): MAP Service closeService in
V/BluetoothMapService( 2328): MAP Service closeService out
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 2328): Entering OffState
V/NativeCrypto( 1619): Read error: ssl=0xb3b8ae00: I/O error during system call, Connection timed out
V/NativeCrypto( 1619): SSL shutdown failed: ssl=0xb3b8ae00: I/O error during system call, Broken pipe
E/WifiStateMachine(  760): scanCount==0 - aborting
D/WifiScanningService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): SCAN_AVAILABLE : 1
D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  760): StartedState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  760): DefaultState
D/RttService(  760): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/BluetoothPbap( 2977): onBluetoothStateChange: up=false
D/BluetoothMap( 2977): onBluetoothStateChange: up=false
D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2977): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=false
D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2977): onBluetoothStateChange: up=false
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1711): CM callback handler got msg 524292
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1241): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/BluetoothInputDevice( 2977): onBluetoothStateChange: up=false
D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15c62488 mBinding = false
D/BluetoothManagerService(  760): Sending unbind request.
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  897): 224845872: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 224845872: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 224845872: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1619): 842199842: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1619): 842199842: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 2328): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2328): GKI_exit_task 1 done
I/GKI_LINUX( 2328): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2328): cleanupNative: return from cleanup
I/art     ( 2328): System.exit called, status: 0
I/AndroidRuntime( 2328): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  760): Process com.android.bluetooth (pid 2328) has died
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/AndroidRuntime( 3124): 
D/AndroidRuntime( 3124): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3124): CheckJNI is OFF
,D/AndroidRuntime( 3124): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2538:com.example.hello/u0a278 (adj 0): stop com.example.hello
,W/PackageSettings(  760): Skipping PackageSetting{26bd2263 com.test.thalitest/10270} due to missing metadata
I/WindowState(  760): WIN DEATH: Window{2820d746 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,D/Tethering(  760): InitialState.processMessage what=4
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager(  760): Force removing ActivityRecord{169d292f u0 com.example.hello/.MainActivity t218}: app died, no saved state
,W/ActivityManager(  760): Spurious death for ProcessRecord{1fdd0134 2538:com.example.hello/u0a278}, curProc for 2538: null
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/Settings( 1993): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  760): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1078): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1619): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1078): run()
,I/Decoder ( 1078): createOrResetDecoder
,I/ConfigService( 1619): onCreate
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/ContextImpl( 2977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  760): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3179 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 2977): finishStartingService: stopping service
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=218_task.xml
,I/art     (  760): Explicit concurrent mark sweep GC freed 30472(1712KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 817us total 104.529ms
,I/MicrophoneInputStream( 1348): mic_starting gfk@1d86269c
,I/HotwordRecognitionRnr( 1348): Starting hotword detection.
,D/AndroidRuntime( 3124): Shutting down VM
,I/AudioFlinger(  183): AudioFlinger's thread 0xb37b9000 ready to run
,I/MicrophoneInputStream( 1348): mic_started gfk@1d86269c,
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): run()
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
,D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,W/ResourcesManager( 3179): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1078): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1078): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1078): run()
I/StatsUtilsManager( 1078): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1078): shouldRecordStats() = Too Soon
,D/AdapterServiceConfig( 3179): Adding HeadsetService
D/AdapterServiceConfig( 3179): Adding A2dpService
,D/AdapterServiceConfig( 3179): Adding HidService
D/AdapterServiceConfig( 3179): Adding HealthService
D/AdapterServiceConfig( 3179): Adding PanService
D/AdapterServiceConfig( 3179): Adding GattService
D/AdapterServiceConfig( 3179): Adding BluetoothMapService
,D/BluetoothAdapter( 2977): 66503568: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 2977): 66503568: getState() :  mService = null. Returning STATE_OFF
,I/HotwordWorker( 1348): onReady
,I/ActivityManager(  760): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3216 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,W/ResourcesManager( 1263): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1263): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/VoicemailCleanupService( 3216): Cleaning up data for package: com.example.hello
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3239 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ContactLocale( 3216): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/SQLiteLog( 3216): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 3216): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 3216): Process: android.process.acore, PID: 3216
E/AndroidRuntime( 3216): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3216): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3216): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3216): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3216): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3216): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 3216): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime( 3216): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:209)
E/AndroidRuntime( 3216): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 3216): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 3216): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 3216): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 3216): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 3216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3216): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  760): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  760): 	... 5 more
,W/OpenGLRenderer( 1263): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1263): Incorrectly called buildLayer on View: adg, destroying layer...
,D/OpenGLRenderer(  760): Render dirty regions requested: true
,D/Atlas   (  760): Validating map...
,E/SQLiteLog( 3216): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
I/Process ( 3216): Sending signal. PID: 3216 SIG: 9
,I/UpdateIcingCorporaServi( 1348): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/Launcher( 1263): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1eaa55bf new=com.google.android.velvet.VelvetApplication@1eaa55bf
,E/SQLiteLog( 1263): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/Adreno-EGL(  760): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  760): Initialized EGL, version 1.4
,D/OpenGLRenderer(  760): Enabling debug mode 0
,E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  171): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configureLowRes: commit failed for low res panel
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  171): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  171): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  171): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  171): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  171): Ctrl commit failed set overlay
E/qdhwcomposer(  171): configure: commit fails
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  171): MdpCtrl close error in unset
,E/SQLiteLog( 1348): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3265 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Process android.process.acore (pid 3216) has died
,W/ActivityManager(  760): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,I/ActivityManager(  760): Killing 2560:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10036/pid_2560/cgroup.procs: No such file or directory

```
