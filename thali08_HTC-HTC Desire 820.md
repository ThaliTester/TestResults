#### Test 50388019831b9e1_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/MdScBoot( 3249): [848.1.] 30@-163326 -> 40@-163353
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process (  907): killProcessQuiet, pid=2560
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
--------- beginning of /dev/log/system
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 2560:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2999
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2999:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Recipient 2560
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 2999
D/MediaRouterService(  907): Client com.google.android.youtube (pid 2999): Died!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3278 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  907): killProcessQuiet, pid=2957
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2957:com.android.settings/1000 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2957
E/dalvikvm( 3278): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3278): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3278): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3278): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/Babel   ( 3278): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3278): MmsConfig.loadMmsSettings
D/MmsCustomizationProvider( 2021): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2021): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3278): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3278): MmsConfig.loadFromDatabase
E/Babel   ( 3278): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3278): MmsConfig.loadFromResources
E/Babel   ( 3278): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3278): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3278, uid=10111, userID:0
W/Settings( 3278): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3278, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3278, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3278, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3278, uid=10111, userID:0
D/Process (  907): killProcessQuiet, pid=3054
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3278, uid=10111, userID:0
I/ActivityManager(  907): Killing 3054:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1756/10178)
I/ActivityManager(  907): Recipient 3054
D/MtpReceiver( 2513): [MTP][MtpReceiver][onReceive]+
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpReceiver( 2513): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2513): [MTP][handleMessage][startService]
D/MtpReceiver( 2513): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2513): [MTP][handleMessage]-
I/ProviderInstaller( 3278): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/MtpService( 2513): [MTP] startForeground
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2513): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2513): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 0 1 10
I/RemoteViews( 1107): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1107): com.android.providers.media 1 1 15
D/MtpService( 2513): [isMtpConnected] connected: true
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3308 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/SyncApplication( 3308): Loading default preferences
W/Resources( 3308): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  907): New client listening to asynchronous messages
D/SyncApplication( 3308): Overriding preferences with custom values
D/CustomizationManager( 3298): ====startRecUseTime====
D/htc.customization.log.level( 3298):  is 
W/CustomizationLogLevel( 3298): Level value is invalid, use default level 2
D/SyncApplication( 3308): Updating preferences succeeded
E/SyncApplication( 3308): Application created.
D/VolumeInfo( 3308): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3308): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3308): Found 0 mount point(s)
V/VolumeInfo( 3308): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3308): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3308): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3308): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3308): getNewCalendarAuthority()...
D/SyncApplication( 3308): enableAppOperation()+
D/SyncApplication( 3308): enableAppOperation()-
D/HTCUtilities( 3308): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3308, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3308, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3308): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3308): isNeorSinged() return false
D/CDMountReceiver( 3308): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3308): USB connected to PC
D/FOTAReceiver( 3308): onReceive() enter 
D/FOTAReceiver( 3308): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3334 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  907): killProcessQuiet, pid=3093
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3093:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3093
D/CustomizationManager( 3298):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3298): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3298): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3298): Parsing tag category name = system
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CustomizationCIDLoader( 3298): Parsing tag category name = application
I/CustomizationCIDLoader( 3298): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3298): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3298): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3298): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3298): Parsing tag category name = Settings
D/CustomizationManager( 3298):  Read CID file spent 0.108 (s)
D/CustomizationManager( 3298):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3298): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3298): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3298): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3298): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3298
D/PMS     (  907): acquireHCC(4277c6b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
W/asset   (  907): Copying FileAsset 0x6f31c898 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1115269816
D/PMS     (  907): acquireHCC(4277a420): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
E/cutils-trace( 3298): Error opening trace file: No such file or directory (2)
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d4e620
D/PMS     (  907): acquireWL(4276eba0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
D/HtcFingerPrintQuickLaunchProvider( 3334): -onCreate()
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3348 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
V/Settings:HtcSettingsApplication( 3334): [3334/3334] onCreate()
D/TetherSettings( 3334): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3334): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3334): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3334): Cust_ConnectToPC   : spcsc>false
D/        ( 3334): Cust_ConnectToPC   : IPT>true
D/        ( 3334): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3334): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/TrimMemoryManager( 1247): [trimMemory] 20
D/TetherSettings( 3334): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3334): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3334): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3334): Cust_ConnectToPC   : spcsc>false
D/        ( 3334): Cust_ConnectToPC   : IPT>true
D/        ( 3334): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3334): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3334): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3334): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3334): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
W/asset   ( 3348): Copying FileAsset 0x5c758420 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/SmartNS_Utility( 3334): usb_cable_connect = 1
D/SmartNS_Utility( 3334): usb_denied = 0
I/SmartNS_NSReceiver( 3334): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3334): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3334): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3334): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3334): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3334):  defaultType:0
I/SmartNS_PSService( 3334): fail notificaiton:false
D/SmartNS_Utility( 3334): usb_cable_connect = 1
W/ContextImpl( 3334): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3334): usb_denied = 0
I/SmartNS_PSService( 3334): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
V/WebViewChromiumFactoryProvider( 3348): Binding Chromium to main looper Looper (main, tid 1) {41aea1f8}
I/LibraryLoader( 3348): Expected native library version number "",actual native library version number ""
I/chromium( 3348): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3348): Initializing chromium process, renderers=0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3334/1000)
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3334): usb_cable_connect = 1
D/SmartNS_Utility( 3334): usb_denied = 0
I/SmartNS_PSService( 3334): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
I/RemoteViews( 1107): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1107): com.android.settings 2 0 10
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3334/1000)
D/PMS     (  907): acquireWL(42432c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(4242b5b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42345380:true
D/SmartNS_Utility( 3334): usb_cable_connect = 1
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/SmartNS_Utility( 3334): usb_denied = 0
D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/BluetoothAdapter( 3348): 1102052336: getState() :  mService = null. Returning STATE_OFF
I/RemoteViews( 1107): com.android.settings (true,33751552)
I/SmartNS_PSService( 3334): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3334): USB Plugged, Set USBPlugged=  truePSenabled:false
I/RemoteViews.Performance( 1107): com.android.settings 0 1 10
D/PMS     (  907): releaseWL(42432c48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3348): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3348): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3348): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3348): Local Branch: 
I/Adreno-EGL( 3348): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3348): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3348):                  aa63bbd948f41d15fc72f585e
W/WeatherUtility( 3164): can't get weather sync account
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1247): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1247): com.google.android.googlequicksearchbox 1 0 5
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1247): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1247): pl.k2.droidoaudioteka 2 1 8
I/ActivityManager(  907): Resuming delayed broadcast
W/chromium( 3348): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
W/dalvikvm( 3348): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3348): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3348): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3348): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3348): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3348): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3348): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3348): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3348): CordovaWebView is running on device made by: HTC
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
W/WeatherRequest( 3164): request cur loc, but there is no sys cur
W/Settings( 3164): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 9 17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  907): sending alarm PendingIntent{41b34c58: PendingIntentRecord{41e818e8 com.google.android.gms startService}}, i=null, t=0, cnt=17097, w=84918423, Int=84918423
I/ActivityManager(  907): Resuming delayed broadcast
W/AwContents( 3348): nativeOnDraw failed; clearing to background color.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
I/InputMethodManagerService(  907): Disable input method client, pid=1247
W/ResourceType( 3348): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3348): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b30f38, mServedView=org.apache.cordova.engine.SystemWebView{41af6f10 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=3348
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +285ms
W/AwContents( 3348): nativeOnDraw failed; clearing to background color.
I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
D/SnetService( 1203): snet destroyed
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3406 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  907): releaseWL(4276eba0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/chromium( 3348): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3348): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PowerUsageService( 3406): call getInstance()
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageList:PowerUsageHelper( 3406): MY_DEBUG = false
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/JsMessageQueue( 3348): Set native->JS mode to OnlineEventsBridgeMode
I/dalvikvm-heap(  907): Grow heap (frag case) to 16.945MB for 137284-byte allocation
D/jxcore_app_log( 3348): JniHelper::setJavaVM(0x415be048), pthread_self() = 1658633256
D/JX-Cordova( 3348): jxcore cordova android initializing
W/BatSI   (  907): Couldn't get kernel wake lock stats
W/jxcore-log( 3348): Initializing JXcore engine
W/jxcore-log( 3348): JXcore engine is ready
W/jxcore-log( 3348): Starting JXcore engine
W/BatSI   (  907): Couldn't get kernel wake lock stats
W/jxcore-log( 3348): Platform android
W/jxcore-log( 3348): 
W/jxcore-log( 3348): Process ARCH arm
W/jxcore-log( 3348): 
I/jxcore-log( 3348): JXcore Cordova bridge is ready!
I/jxcore-log( 3348): 
W/jxcore-log( 3348): JXcore engine is started
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=3105
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3105:com.htc.contacts/u0a41 (adj 15): empty #17
D/PMS     (  907): acquireWL(4276eba0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3406 1000 null
W/WeatherUtility( 1107): can't get weather sync account
D/WeatherUtility( 1397): Weather sync is On
D/WSP     ( 1397): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  907): Recipient 3105
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/WeatherUtility( 3164): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3427 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherRequest( 3164): request cur loc, but there is no sys cur
W/Settings( 3164): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/jxcore-log( 3348): >> HTC-HTC Desire 820
E/jxcore-log( 3348): 
I/jxcore-log( 3348): Total memory 1964650496
I/jxcore-log( 3348): 
I/jxcore-log( 3348): Free memory 701394944
I/jxcore-log( 3348): 
I/jxcore-log( 3348): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3348): 
I/jxcore-log( 3348): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3348): 
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/jxcore-log( 3348): userPath [ 'www' ]
I/jxcore-log( 3348): 
I/jxcore-log( 3348): Size 720 1184
I/jxcore-log( 3348): 
I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 6 17
I/jxcore-log( 3348): Screen Brightness 10
I/jxcore-log( 3348): 
E/jxcore-log( 3348): Dummy Error Log.
E/jxcore-log( 3348): 
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
I/jxcore-log( 3348): getBuffer is called!!!!
I/jxcore-log( 3348): 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3445 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3120
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3120:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3120
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/MusicStore( 3445): Database version: 95
W/ContextImpl( 3445): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3445): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3445): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3445, uid=10154, userID:0
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.music (pid 3445): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3445): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3445/10154)
D/MediaRouter( 3445): getSelectedRoute
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3445, uid=10154, userID:0
D/DFPI.PIReciver( 3178): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3178): onHandleIntent
I/DFPI.ApkInstallService( 3178): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3178): check CID = HTC__032
I/DFPI.ApkInstallService( 3178): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/HtcModeClient( 1461): handler message = 4011
E/HtcModeClient( 1461): Check connection and retry 5 times.
V/AlarmManager(  907): sending alarm PendingIntent{424bb498: PendingIntentRecord{425a3668 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1451921636184, Int=0
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3468 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=2932
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2932:com.android.settings:remote/1000 (adj 15): empty #17
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(4277c6b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  907): releaseHCC(4277a420): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3468): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3468/10051)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Recipient 2932
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(4276eba0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  907): mEventCount = 450
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3486 uid=10080 gids={50080, 5001, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3208
,I/ActivityManager(  907): Killing 3208:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3208
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3486): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3486): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3486): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3486): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3486): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(4242b5b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null,
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3178): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3178): onHandleIntent
,I/DFPI.ApkInstallService( 3178): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3178): check CID = HTC__032
,I/DFPI.ApkInstallService( 3178): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3221
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  907): Killing 3221:com.htc.stock:remote/u0a81 (adj 15): empty #17
W/ContextImpl( 3486): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3486): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3486): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3486): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3486): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  907): Recipient 3221
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SocialFeedProvider( 1247): +disConnect socialManager
,I/SocialFeedProvider( 1247): disconnect socialManager
,I/SocialFeedProvider( 1247): -disConnect socialManager
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(427ea680): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1461 10014 null
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(427ea680): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,V/AlarmManager(  907): sending alarm PendingIntent{42094398: PendingIntentRecord{424b8090 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1451921639656, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SocialManager[SocialBiLogHelper]( 3233): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3233): last commit ulog time 1451886909157
,I/SocialManager[SocialBiLogHelper]( 3233): skip commit this time
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3510 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3178): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3178): onHandleIntent
,I/DFPI.ApkInstallService( 3178): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3178): check CID = HTC__032
,I/DFPI.ApkInstallService( 3178): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3510): [ NA ]- onCreate()
,I/EASAppSvc( 3510): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3193): put()
,I/EASAppSvc( 3510): [ NA ]- onDestroy()
,I/EASAppSvc( 3510): [ NA ]> uninitEASService
D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3510/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3510/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3510/10063)
,I/ClockThread( 1107): now=1451921640008 next=59992
V/AlarmManager(  907): sending alarm PendingIntent{41c35898: PendingIntentRecord{41c295d8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=56335, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,I/EASRequestController( 3510): [ NA ]release
,I/EASAppSvc( 3510): [ NA ]< uninitEASService
,I/EASAppSvc( 3510): [ NA ]- onCreate()
,I/EASAppSvc( 3510): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3510/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3510/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3510/10063)
,D/ORMLib  ( 3193): put()
,I/EASAppSvc( 3510): [ NA ]- onDestroy()
,I/EASAppSvc( 3510): [ NA ]> uninitEASService
,I/EASRequestController( 3510): [ NA ]release
,I/EASAppSvc( 3510): [ NA ]< uninitEASService
I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3543 uid=10067 gids={50067, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3138
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3138:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1453
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms),
I/ActivityManager(  907): Recipient 3138
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/ORMLib  ( 3193): put()
,D/WifiManager( 3348): setWifiEnabled: Base Package Name=com.example.hello, uid=10356
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1451
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: false pid=3348, uid=10356
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 4(ms)
I/jxcore-log( 3348): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 3348): 
I/jxcore-log( 3348): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3348): 
,E/cutils-trace( 3564): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3564): ====startRecUseTime====
D/htc.customization.log.level( 3564):  is 
,W/CustomizationLogLevel( 3564): Level value is invalid, use default level 2
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3151
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3486): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/ActivityManager(  907): Killing 3151:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3486): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3486): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3486): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3486): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  907): Recipient 3151
I/ActivityManager(  907): Waited long enough for: ServiceRecord{42658030 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,D/CustomizationManager( 3564):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3564): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3564): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3564): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3564): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3564): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3564): Parsing tag category name = system
,I/CustomizationCIDLoader( 3564): Parsing tag category name = application
I/CustomizationCIDLoader( 3564): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 3564): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3564): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3564): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3564): Parsing tag category name = Settings
D/CustomizationManager( 3564):  Read CID file spent 0.107 (s)
,D/CustomizationManager( 3564):  All configurations done spent 0.107 (s)
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
W/HtcNativeFlag( 3564): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3564): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3564): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3564): Fail to get flag for type 'language', use default value: -1
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/MediaStoreImporter( 3445): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3564, uid=2000 user=0
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3178): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 3178): onHandleIntent
,I/DFPI.ApkInstallService( 3178): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3178): check CID = HTC__032
,I/DFPI.ApkInstallService( 3178): There is no Demo.apk in sd card or phone storage
D/Process (  907): killProcessQuiet, pid=3348
,W/asset   (  907): Copying FileAsset 0x64385c18 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 3348:com.example.hello/u0a356 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{423384b0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{42274910 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=0: pkg removed
,W/InputDispatcher(  907): channel '42582418 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '42582418 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '42582418 com.example.hello.MainActivity (s)'
I/acms    ( 1775): Unregistering com.example.hello
E/acms    ( 1775): Could not unregister removed application com.example.hello
,W/GeofencerStateMachine( 1417): Ignoring removeGeofence because network location is disabled.
D/WifiService(  907): Client connection lost with reason: 4
I/WindowManager(  907): WINDOW DIED Window{42582418 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  907): acquireWL(42328758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
,W/AccTypeManager( 1306): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1306): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3233): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3233): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  907): releaseWL(42328758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@41eec650 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  907): WIN DEATH: null
,D/AccTypeManager( 1306): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/HtcModeClient( 1461): handler message = 4011
,E/HtcModeClient( 1461): Check connection and retry 6 times.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,E/ExternalAccountType( 1306): Unsupported attribute readOnly
,I/FeedHostManager( 1247): [onResume]
I/SoundPicker( 3486): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/FeedProviderManager( 1247): onResume
W/ContextImpl( 3486): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SocialFeedProvider( 1247): +onResume
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1247): -onResume
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1247/10075)
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/SoundPicker( 3486): SoundPickerReceiver [onReceive] startService
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/SoundPicker( 3486): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3486): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3486): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3486): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3486): MODE_GSM access default DB
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3486): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3486): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/SoundPicker( 3486): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3486): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/ActivityManager(  907): Resuming delayed broadcast
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3348 uid 10356
,W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  907): Enable input method client, pid=1247
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3445): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  907): Resuming delayed broadcast
D/TelephonyReceiver( 1219): bind: true
D/TelephonyReceiver( 1219): bind: false
D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
D/GenericMessagesProvider( 2021): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2021): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2021): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2021): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2021): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 2021): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2021): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2021): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2021): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2021): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2021): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2021): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2021): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2021): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2021): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
D/AutoSetting( 1397): service - mRequestRunnable: screen on delay 10s, request NLP now
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1397): service - requestNLP() NetworkLocationProvider not enabled
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2021): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2021): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2021): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2021): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2021): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2021): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2021): 	a,t android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2021): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2021): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2021): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2021): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
E/Icing   ( 1203): Package com.example.hello not found
D/PMS     (  907): acquireWL(426e9cb0): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/PMS     (  907): releaseWL(426e9cb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
,W/PackageManager(  907): Unable to load service info ResolveInfo{425f1e98 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 1203): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1203): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 1203): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 1203): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 1203): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 1203): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 1203): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 1203): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 1203): 	at dug.c(SourceFile:3081)
E/SQLiteDatabase( 1203): 	at ezc.a(SourceFile:24)
E/SQLiteDatabase( 1203): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 1203): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 1203): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1203): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1203): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 1203): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1203): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 1203): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 1203): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 1203): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 1203): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 1203): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 1203): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 1203): 	at dug.c(SourceFile:3081)
E/SQLiteOpenHelper( 1203): 	at ezc.a(SourceFile:24)
E/SQLiteOpenHelper( 1203): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 1203): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 1203): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1203): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1203): 	at java.lang.Thread.run(Thread.java:864)
,W/SQLiteOpenHelper( 1203): Opened games_3a3529a.db in read-only mode
,W/dalvikvm( 1203): threadid=10: thread exiting with uncaught exception (group=0x416b6e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1203): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1203): Process: com.google.android.gms, PID: 1203
E/AndroidRuntime( 1203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 1203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 1203): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 1203): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 1203): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 1203): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 1203): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 1203): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 1203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1203): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1203): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,V/AlarmManager(  907): sending alarm PendingIntent{42657d18: PendingIntentRecord{42845178 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1451921642097, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3594 uid=10031 gids={50031, 3003, 5012}
,I/Prism.ItemManager( 3233): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3233): loadItems() com.htc.launcher.pageview.WidgetManager@41b56ea8 +
,I/Prism.WidgetManager( 3233): onLoadItems() +
I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver

```
