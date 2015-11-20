#### Test 50388019aa1a16d_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WifiService(  907): New client listening to asynchronous messages
--------- beginning of /dev/log/main
D/SyncApplication( 3738): Overriding preferences with custom values
D/SyncApplication( 3738): Updating preferences succeeded
E/SyncApplication( 3738): Application created.
D/VolumeInfo( 3738): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3738): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3738): Found 0 mount point(s)
V/VolumeInfo( 3738): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3738): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3738): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3738): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3738): getNewCalendarAuthority()...
D/SyncApplication( 3738): enableAppOperation()+
D/SyncApplication( 3738): enableAppOperation()-
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3738, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3738, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3738): isNeorSinged() + 
D/HTCUtilities( 3738): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
W/Settings( 3549): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/HTCUtilities( 3738): isNeorSinged() return false
D/CDMountReceiver( 3738): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3738): USB connected to PC
I/ActivityManager(  907): Recipient 3494
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/FOTAReceiver( 3738): onReceive() enter 
D/FOTAReceiver( 3738): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/Process (  907): killProcessQuiet, pid=3290
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3766 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3290:com.htc.calendar/u0a13 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3290
I/CheckinTask( 1228): Sending checkin request (9172 bytes)
,D/HtcFingerPrintQuickLaunchProvider( 3766): -onCreate()
V/Settings:HtcSettingsApplication( 3766): [3766/3766] onCreate()
W/ActivityThread( 1228): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/TetherSettings( 3766): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3766): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3766): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3766): Cust_ConnectToPC   : spcsc>false
D/        ( 3766): Cust_ConnectToPC   : IPT>true
D/        ( 3766): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3766): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3766): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3766): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3766): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3766): Cust_ConnectToPC   : spcsc>false
D/        ( 3766): Cust_ConnectToPC   : IPT>true
D/        ( 3766): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3766): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3766): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3766): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3766): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3766): usb_cable_connect = 1
D/SmartNS_Utility( 3766): usb_denied = 0
I/SmartNS_NSReceiver( 3766): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3766): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3766): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3766): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3766): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3766):  defaultType:0
I/SmartNS_PSService( 3766): fail notificaiton:false
D/SmartNS_Utility( 3766): usb_cable_connect = 1
D/SmartNS_Utility( 3766): usb_denied = 0
I/SmartNS_PSService( 3766): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/libc    ( 1228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
D/libc    ( 1228): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =867 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3766/1000)
D/SmartNS_Utility( 3766): usb_cable_connect = 1
D/SmartNS_Utility( 3766): usb_denied = 0
I/SmartNS_PSService( 3766): usb notificaiton:true
D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/RemoteViews( 1120): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1120): com.android.settings 2 1 10
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
V/Tethering(  907): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 3766): usb_cable_connect = 1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3766/1000)
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/ActivityManager(  907): Resuming delayed broadcast
D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3766): usb_denied = 0
I/RemoteViews( 1120): com.android.settings (true,33751552)
I/SmartNS_PSService( 3766): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3766): USB Plugged, Set USBPlugged=  truePSenabled:false
I/RemoteViews.Performance( 1120): com.android.settings 2 1 10
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/ActivityManager(  907): Resuming delayed broadcast
W/WeatherUtility( 3399): can't get weather sync account
D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1271): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1271): com.google.android.googlequicksearchbox 2 1 5
W/WeatherRequest( 3399): request cur loc, but there is no sys cur
W/Settings( 3399): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1271): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1271): pl.k2.droidoaudioteka 2 0 8
D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  907): Resuming delayed broadcast
D/SMSBackup( 3683): Got a database change event
I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 7 17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
V/AlarmManager(  907): sending alarm PendingIntent{41dce9d0: PendingIntentRecord{427ff548 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1448020203223, Int=0
I/ActivityManager(  907): Resuming delayed broadcast
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1228/10028)
D/libc    ( 1228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1228/10028)
D/PMS     (  907): acquireWL(42502650): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 1228 10028 null
E/cutils-trace( 3778): Error opening trace file: No such file or directory (2)
D/PMS     (  907): releaseWL(42502650): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  907): sending alarm PendingIntent{41f2ea30: PendingIntentRecord{41cf73c8 com.google.android.gms startService}}, i=null, t=0, cnt=17051, w=84918423, Int=84918423
I/ActivityManager(  907): Resuming delayed broadcast
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1228/10028)
I/AdsMeasurementBroadcastReceiver( 1228): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1228): Unauthorized to start the main service
D/WIFI_ICON( 1120): WifiActivity: 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/SnetService( 1228): snet destroyed
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3805 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/CustomizationManager( 3778): ====startRecUseTime====
D/htc.customization.log.level( 3778):  is 
W/CustomizationLogLevel( 3778): Level value is invalid, use default level 2
I/HtcModeClient( 1498): handler message = 4011
E/HtcModeClient( 1498): Check connection and retry 5 times.
D/CustomizationManager( 3778):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3778): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3778): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3778): Parsing tag category name = system
I/CustomizationCIDLoader( 3778): Parsing tag category name = application
I/CustomizationCIDLoader( 3778): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3778): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3778): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3778): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3778): Parsing tag category name = Settings
D/CustomizationManager( 3778):  Read CID file spent 0.100 (s)
D/CustomizationManager( 3778):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 3778): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3778): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3778): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3778): Fail to get flag for type 'language', use default value: -1
W/ContextImpl( 3805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3805): call getInstance()
D/PowerUsageList:PowerUsageHelper( 3805): MY_DEBUG = false
W/BatSI   (  907): Couldn't get kernel wake lock stats
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3778
D/PMS     (  907): acquireHCC(422f7f08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
W/asset   (  907): Copying FileAsset 0x69331e60 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1110880272
D/PMS     (  907): acquireHCC(41e785f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4226d250
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  907): acquireWL(42456168): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3820 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 3820): Copying FileAsset 0x5c7d0428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1271): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3820): Binding Chromium to main looper Looper (main, tid 1) {41aa4368}
I/LibraryLoader( 3820): Expected native library version number "",actual native library version number ""
I/chromium( 3820): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3820): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(4230b428): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(42578c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  907): releaseWL(4230b428): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425b44b0:true
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/PMS     (  907): releaseWL(42578c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3820): 1101767064: getState(). Returning 12
I/Adreno-EGL( 3820): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3820): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3820): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3820): Local Branch: 
I/Adreno-EGL( 3820): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3820): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3820):                  aa63bbd948f41d15fc72f585e
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=26 [15][4][0]
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1228/10028)
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1228/10028)
W/GLSUser ( 1370): GoogleAccountDataService.getToken()
W/chromium( 3820): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3820): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3820): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/dalvikvm( 3820): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3820): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3820): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3820): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3820): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3820): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3820): CordovaWebView is running on device made by: HTC
,I/RemoteViews( 1120): com.google.android.gms (false,0)
D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 1228): awaiting user notification for token
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41bf1e58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1120): com.google.android.gms 0 8 3 12
I/CheckinTask( 1228): Sending checkin request (2419 bytes)
W/AwContents( 3820): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1271
W/ResourceType( 3820): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3820): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41aeb608, mServedView=org.apache.cordova.engine.SystemWebView{41ab14b8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=3820
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +313ms
W/AwContents( 3820): nativeOnDraw failed; clearing to background color.
D/PMS     (  907): releaseWL(42456168): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/PMS     (  907): releaseWL(426114d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=3594
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3594:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3594
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=3168
I/chromium( 3820): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/AndroidProtocolHandler( 3820): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  907): Killing 3168:com.android.settings:remote/1000 (adj 15): empty #17
D/PMS     (  907): acquireWL(424df4d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3805 1000 null
W/WeatherUtility( 1120): can't get weather sync account
D/WeatherUtility( 1421): Weather sync is On
I/ActivityManager(  907): Recipient 3168
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WSP     ( 1421): [Receiver] auto sync agent, auto sync is enabled, reset schedule
W/WeatherUtility( 3399): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3869 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/JsMessageQueue( 3820): Set native->JS mode to OnlineEventsBridgeMode
W/WeatherRequest( 3399): request cur loc, but there is no sys cur
W/Settings( 3399): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 9 17
D/PMS     (  907): acquireWL(4284b478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  907): releaseWL(4284b478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1228/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=20 [5][1][0]
D/jxcore_app_log( 3820): JniHelper::setJavaVM(0x4157b048), pthread_self() = 1657569960
D/JX-Cordova( 3820): jxcore cordova android initializing
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1228/10028)
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
W/GLSUser ( 1370): GoogleAccountDataService.getToken()
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/jxcore-log( 3820): Initializing JXcore engine
W/jxcore-log( 3820): JXcore engine is ready
D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/jxcore-log( 3820): Starting JXcore engine
W/CheckinRequestBuilder( 1228): awaiting user notification for token
I/RemoteViews( 1120): com.google.android.gms (false,0)
D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e79228 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1120): com.google.android.gms 0 8 3 12
I/CheckinTask( 1228): Checkin success: https://android.clients.google.com/checkin (2 requests sent)
W/GoogleHttpClient( 1228): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1228/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1228/10028)
D/PMS     (  907): releaseWL(425ff7d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1228): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b36450 that was originally bound here
E/ActivityThread( 1228): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b36450 that was originally bound here
E/ActivityThread( 1228): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1228): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1228): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1228): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1228): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1228): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1228): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1228): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1228): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1228): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1228): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1228): 	at bks.a(SourceFile:298)
E/ActivityThread( 1228): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1228): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1228): 	at java.lang.Thread.run(Thread.java:864)
W/jxcore-log( 3820): Platform android
W/jxcore-log( 3820): 
W/jxcore-log( 3820): Process ARCH arm
W/jxcore-log( 3820): 
I/jxcore-log( 3820): JXcore Cordova bridge is ready!
I/jxcore-log( 3820): 
W/jxcore-log( 3820): JXcore engine is started
E/jxcore-log( 3820): >> HTC-HTC Desire 820
E/jxcore-log( 3820): 
I/jxcore-log( 3820): Total memory 1964650496
I/jxcore-log( 3820): 
I/jxcore-log( 3820): Free memory 610549760
I/jxcore-log( 3820): 
I/jxcore-log( 3820): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3820): 
I/jxcore-log( 3820): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3820): 
I/jxcore-log( 3820): userPath [ 'www' ]
I/jxcore-log( 3820): 
I/jxcore-log( 3820): Size 720 1184
I/jxcore-log( 3820): 
I/jxcore-log( 3820): Screen Brightness 10
I/jxcore-log( 3820): 
E/jxcore-log( 3820): Dummy Error Log.
E/jxcore-log( 3820): 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3887 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/MusicStore( 3887): Database version: 95
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3887): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3887): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3887): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3887): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3887, uid=10154, userID:0
V/AlarmManager(  907): sending alarm PendingIntent{4278dda8: PendingIntentRecord{4240fdb8 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448020205220, Int=0
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.music (pid 3887): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3887): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/NetworkMonitor( 3887): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3887/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3627): onHandleIntent
I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
,I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
I/jxcore-log( 3820): getBuffer is called!!!!
I/jxcore-log( 3820): 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 3887): getSelectedRoute
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 3887): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3887/10154)
,I/ActivityManager(  907): Resuming delayed broadcast
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3887, uid=10154, userID:0
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3909 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3609
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 3609:com.qualcomm.timeservice/1000 (adj 15): empty #17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3609
D/WIFI_ICON( 1120): WifiActivity: 1
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3909/10051)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3909/10051)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42561f70 u0 ReceiverList{424ba230 3909 com.htc.musicenhancer/10051/u0 remote:4235dad0}}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3909): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(422f7f08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(41e785f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/PMS     (  907): releaseWL(424df4d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SensorManager(  907): mEventCount = 451
,D/Process (  907): killProcessQuiet, pid=3645
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3928 uid=10080 gids={50080, 5001, 1028, 1015}
I/ActivityManager(  907): Killing 3645:com.htc.stock/u0a81 (adj 15): empty #17
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3928): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3928): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3928): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3928): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6,
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7,
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92,
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9,
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Recipient 3645
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4275e2c8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3627): onHandleIntent
,I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
,I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3928): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3928): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3928): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3928): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42626a88): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1498 10014 null
I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(42626a88): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3627): onHandleIntent
I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3928): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3928): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3928): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3928): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5,
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86,
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8,
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/AutoSetting( 1421): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1421): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1421): service - requestNLP() NetworkLocationProvider not enabled
,I/MediaStoreImporter( 3887): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3953 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3627): onHandleIntent
I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
,I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/EASAppSvc( 3953): [ NA ]- onCreate()
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3953): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3579): put()
,I/EASAppSvc( 3953): [ NA ]- onDestroy()
,I/EASAppSvc( 3953): [ NA ]> uninitEASService
,D/WifiService(  907): New client listening to asynchronous messages
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3928): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3953/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3953/10063)
,I/SoundPicker( 3928): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3928): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3928): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3928): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3928): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3928): MODE_GSM access default DB
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3953/10063)
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3928): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3928): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3928): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3928): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3887): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/TelephonyReceiver( 1247): bind: true
I/ActivityManager(  907): Resuming delayed broadcast
,D/TelephonyReceiver( 1247): bind: false
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/GenericMessagesProvider( 2760): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2760): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 2760): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2760): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2760): DB info: errno = 2, errno message = No such file or directory
,D/PMS     (  907): acquireWL(425efcd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
E/SQLiteDatabase( 2760): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2760): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2760): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2760): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2760): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2760): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2760): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2760): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2760): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2760): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2760): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2760): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2760): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2760): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2760): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,I/EASRequestController( 3953): [ NA ]release
I/EASAppSvc( 3953): [ NA ]< uninitEASService
,I/EASAppSvc( 3953): [ NA ]- onCreate()
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/PMS     (  907): releaseWL(425efcd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/EASAppSvc( 3953): [ NA ]> onUpgrade: version = 63
,D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=41 rxSum=36} preTxRxSum={txSum=0 rxSum=0}
,D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19432 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19433 delay=15s
,D/Process (  907): killProcessQuiet, pid=3657
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/SocialFeedProvider( 1271): +disConnect socialManager
,I/SocialFeedProvider( 1271): disconnect socialManager
I/ActivityManager(  907): Killing 3657:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3657
,I/SocialFeedProvider( 1271): -disConnect socialManager
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3953/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3953/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3953/10063)
D/ORMLib  ( 3579): put()
,D/PackageBroadcastService( 1228): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/EASAppSvc( 3953): [ NA ]- onDestroy()
,I/EASAppSvc( 3953): [ NA ]> uninitEASService
,I/EASRequestController( 3953): [ NA ]release
,I/EASAppSvc( 3953): [ NA ]< uninitEASService
,I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3998 uid=10067 gids={50067, 3003, 5012}
,D/PMS     (  907): acquireWL(42796898): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(42796898): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1228): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1228, uid=10028, userID:0
,D/Process (  907): killProcessQuiet, pid=3695
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3695:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3695
,D/ORMLib  ( 3579): put()
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3711
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3711:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3711
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4017 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3725:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3725
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1421): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Recipient 3725
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4033 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,V/AlarmManager(  907): sending alarm PendingIntent{41db7238: PendingIntentRecord{4245b560 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=57794, Int=0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4033, uid=10073, userID:0
,D/Finsky  ( 4033): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4033/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4033/10073)
,D/Finsky  ( 4033): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4033): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4033): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4033, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3532
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Killing 3532:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Finsky  ( 4033): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4033): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2926): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Finsky  ( 4033): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{425444a8 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  907): acquireWL(42441720): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,I/ActivityManager(  907): Recipient 3532
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42441720): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(41cebff8): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): releaseWL(41cebff8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(424bdae0): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(424bdae0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(41bfaf58): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(41bfaf58): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(423e9250): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): releaseWL(423e9250): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(424e9b50): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(424e9b50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/HtcModeClient( 1498): handler message = 4011
,E/HtcModeClient( 1498): Check connection and retry 6 times.
,D/PMS     (  907): acquireWL(423cd708): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(423cd708): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(41e87940): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(41e87940): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42364948): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(42364948): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4232a8c0): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,D/PMS     (  907): releaseWL(4232a8c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4069 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{42169f28: PendingIntentRecord{421a7f20 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448020208774, Int=0
,W/asset   ( 2926): Copying FileAsset 0x635eaa18 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2926): UpdateCorporaTask done [took 441 ms] updated apps [took 441 ms] 
,D/Finsky  ( 4033): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4082 uid=10098 gids={50098, 3003, 5012}
,I/ImageRamCache( 4069): create image Cache, size: 31457280.
I/ImageRamCache( 4069): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4069): create image Cache, size: 12582912.
,I/FeedSettings( 4069): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4069): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4069): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4069): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4069): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4069): loadGridSize() with Alternative
,I/DeviceManagement( 4082): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4082 dbg=false s=true
I/SocialManager[SocialBiLogHelper]( 4069): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4069): last commit ulog time 1448013037762
,I/SocialManager[SocialBiLogHelper]( 4069): skip commit this time
,I/DeviceManagement( 4082): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4099 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3738
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  907): killProcessQuiet, pid=3766
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3738:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  907): Killing 3766:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3738
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Recipient 3766
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  907): sending alarm PendingIntent{4237b748: PendingIntentRecord{425392d0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448020209297, Int=0
,I/ActivityManager(  907): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4099/10100)
,W/GAV2    ( 4099): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4099/10100)
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4033): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4033): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4033): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4033): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4033): [1] DailyHygiene.reschedule: Scheduling new run in 93 minutes (failures=3)
,I/ActivityManager(  907): Resuming delayed broadcast
,W/GAV2    ( 4099): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  907): killProcessQuiet, pid=3670
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4126 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3670:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3670
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@424b88a0 mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1485
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	,at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	,at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264),
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): ,	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  907): Sending off request.
D/BluetoothAdapterState( 1587): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 1587): Setting state to 13
I/BluetoothAdapterState( 1587): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1587): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1587): onBluetoothDisable()
,I/bt-btm  ( 1587): BTM_SetDiscoverability,
I/bt-btm  ( 1587): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1587): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1587): br_edr_supported=0x0
,I/bt-btm  ( 1587): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1587): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1587): btm_ble_update_adv_flag new=0x4
,D/bt-btm  ( 1587): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1587): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1587): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1587): BTM_SetConnectability,
I/bt-btm  ( 1587): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1587): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1587): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800,
I/BluetoothAdapterState( 1587): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiManager( 3820): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 12 -> 13
,E/BTIF_CORE( 1587): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1587): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothRemoteDevices( 1587): Wake lock Aquired
I/bt-btif ( 1587): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 1587): adapterPropertyChangedCallback with type:7 len:4
,V/BluetoothPbapReceiver( 1587): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1120): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,V/BluetoothPbapReceiver( 1587): ***********state = 13
,D/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  907): New client listening to asynchronous messages
D/PMS     (  907): acquireWL(426395a0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1587 1002 null
D/WifiService(  907): setWifiEnabled: false pid=3820, uid=10355
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/htcbackup-core( 4126): ModelRegistry: Loading model meta data from resources...
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1751): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41aca1f0
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1751): onDeInitialized
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1106
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
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
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1751): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1751): getNotificationManager
D/BluetoothMasReceiver( 1587): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1587): SapReceiver onReceive 
V/BluetoothSapReceiver( 1587): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1587):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1587): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterProperties( 1587): Scan Mode:20
,D/BluetoothAdapterState( 1587): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,I/bt-btif ( 1587): BTA_JvDeleteRecord
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 1587): BTA_JvRfcommStopServer
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1587): BTM_SEC_CLR[13]: id 52
D/bt-btm  ( 1587): BTM_FreeSCN 
I/bt-btif ( 1587): BTA_JvDeleteRecord
I/bt-btif ( 1587): BTA_JvRfcommStopServer
D/bt-btm  ( 1587): BTM_FreeSCN 
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1587): BTM_SEC_CLR[14]: id 53
I/bt-btif ( 1587): BTA_JvDeleteRecord
I/bt-btif ( 1587): BTA_JvRfcommStopServer
D/bt-btm  ( 1587): BTM_FreeSCN 
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:13
,I/bt-btif ( 1587): BTA_JvDeleteRecord
I/bt-btif ( 1587): BTA_JvRfcommStopServer
D/bt-btm  ( 1587): BTM_FreeSCN 
I/bt-btif ( 1587): BTA_JvDeleteRecord
I/bt-btif ( 1587): BTA_JvRfcommStopServer
D/bt-btm  ( 1587): BTM_FreeSCN 
,I/bt-btif ( 1587): BTA_JvDeleteRecord
I/bt-btif ( 1587): BTA_JvRfcommStopServer
D/bt-btm  ( 1587): BTM_FreeSCN 
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1587): BTM_SEC_CLR[15]: id 54
,D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1587): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
,I/bt-btm  ( 1587): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1587): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1587): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:9
,I/bt-btm  ( 1587): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1587): Write Extended Inquiry Response to controller
I/bt-btm  ( 1587): Write Extended Inquiry Response to controller
I/bt-btm  ( 1587): Write Extended Inquiry Response to controller
,I/bt-btm  ( 1587): Write Extended Inquiry Response to controller
I/bt-btm  ( 1587): BTM_SetDiscoverability
I/bt-btm  ( 1587): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1587): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1587): br_edr_supported=0x0
,I/bt-btm  ( 1587): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1587): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1587): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1587): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1587): evt_type=0x3 p-cb->evt_type=0x3 
,I/bt-btm  ( 1587): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1587): BTM_SetConnectability
I/bt-btm  ( 1587): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1587): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1587): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
,I/bt-btm  ( 1587): BTM_IsInquiryActive
I/bt-btm  ( 1587): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1587): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1587): BTM_FreeSCN 
,I/bt-btm  ( 1587): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1587): BTM_FreeSCN 
I/bt-btm  ( 1587): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1587): AVRC_Close handle:0
,E/BtOppRfcommListener( 1587): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1587): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1587): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1587): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1587): GATT_Deregister gatt_if=3
,I/bt-att  ( 1587): GATT_Deregister gatt_if=4
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4141 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/BluetoothSapService( 1587): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/ContextImpl( 4126): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,V/BluetoothPbapService( 1587): Pbap Service closeService in
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
V/BluetoothPbapService( 1587): successfully stopped pbap service
V/BluetoothPbapService( 1587): Pbap Service closeService out
V/BluetoothSapService( 1587): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1587): state: 13
D/BluetoothAdapter( 1587): 1101805920: getState(). Returning 13
V/BluetoothSapService( 1587): Stopping SAP server process
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1751): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1751):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1751): writeLinkLossAlertLevelAll: 0, false
I/DeviceManagement( 4082): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1751): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1751): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1751):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1751): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1751): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1751): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1751): shutdownStateMachine
D/BluetoothManagerService(  907): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  907): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424945a8:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1751): Exit IdleState
I/DeviceManagement( 4082): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.keychain, com.htc.android.htcloglevel, com.htc.drive.activator, com.htc.home.personalize, com.htc.backup, com.android.CSDFunctionG, com.htc.cirmodule, com.qualcomm.privinit, com.htc.checkinprovider, com.htc.feedback, com.htc.smartdim, com.htc.backupreset, com.htc.guide, android, com.htc.lockscreen, com.htc.autobot.cargps.provider, com.android.providers.settings, com.android.location.fused, com.qualcomm.timeservice, com.htc.usage, com.android.inputdevices, com.htc.htcpowermanager, com.htc.android.htcsetupwizard, com.htc.mirrorlinkserver, com.android.settings]
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1751): init: null
I/QuickSettingBluetooth( 1120): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1751): setPendingRequestAlarm: false, mContext = null, null
D/PhoneStatusBar( 1120): removeIcon slot=bluetooth index=12 viewIndex=0
I/jxcore-log( 3820): ****TEST TOOK:  5143  ms ****
I/jxcore-log( 3820): 
I/jxcore-log( 3820): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3820): 
D/WirelessDisplayService(  907): getMirrorDisplayStatus:falsecurState:1
,I/DeviceManagement( 4082): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
D/Process (  907): killProcessQuiet, pid=3683
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
I/DeviceManagement( 4082): WorkflowService: Starting workflow service
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
I/DeviceManagement( 4082): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ada7e8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 4082): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4158 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  907): Killing 3683:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(4256ea68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/DeviceManagement( 4082): ModelRegistry: Loading model meta data from resources...
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
V/BluetoothSapService( 1587): Sap Service closeSapService in
V/BluetoothSapService( 1587): Close listen Socket : 
V/BluetoothSapService( 1587): Close rfcomm Socket : 
V/BluetoothSapService( 1587): Close sapd  Socket : 
V/BluetoothSapReceiver( 1587): BluetoothSapReceiver deinit
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapService( 1587): successfully stopped Sap service
V/BluetoothSapService( 1587): Sap Service closeSapService out
D/HtcFingerPrintQuickLaunchProvider( 4141): -onCreate()
I/BtOppRfcommListener( 1587): stopping Accept Thread
I/BtOppRfcommListener( 1587): BluetoothSocket listen thread finished
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19433 mDataStallAlarmIntent=PendingIntent{423f1500: PendingIntentRecord{423d4ac0 android broadcastIntent}}
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
V/BluetoothPbapService( 1587): Pbap Service onDestroy
V/BluetoothPbapService( 1587): Pbap Service closeService in
V/BluetoothPbapService( 1587): Pbap Service closeService out
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
V/BluetoothSapService( 1587): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41afbf70
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
V/BluetoothSapService( 1587): Sap Service closeSapService in
V/BluetoothSapService( 1587): Close listen Socket : 
V/BluetoothSapService( 1587): Close rfcomm Socket : 
V/BluetoothSapService( 1587): Close sapd  Socket : 
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
V/Settings:HtcSettingsApplication( 4141): [4141/4141] onCreate()
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  907):    returned null
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
,I/DeviceManagement( 4082): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/DeviceManagement( 4082): SessionStateController: Checking invariants...
D/WifiStateMachine(  907): Call handleNetworkDisconnect() in SupplicantStoppingState
I/ActivityManager(  907): Recipient 3683
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pDisablingState
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  907): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  907): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  907): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): p2p socket connection lost
D/WifiP2pService(  907): P2pDisabledState
D/WifiP2pService(  907): P2pDisabledState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
,D/HtcEffectManager(  907): convertEffect after=902
V/BluetoothSapService( 1587): Sap Service closeSapService out
,V/BluetoothSapService( 1587): ***onDestroyed***
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  907): updateConnection
I/WifiDisplayController(  907): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  907): updateConnection enter step 4
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/PMS     (  907): acquireWL(427663c8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4141 1000 null
D/WifiP2pService(  907): P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  907): Failed to set WFD info with reason 2.
D/WifiP2pService(  907): DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiNative-p2p0(  907): doBoolean: TERMINATE
W/WifiHW  (  907): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1161): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiNative-p2p0(  907):    returned true
D/wpa_supplicant( 1161): TDLS: Tear down peers
I/wpa_supplicant( 1161): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/IntentController( 1120): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1120): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1161): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1161): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1161): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2462
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7ca3bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
E/wpa_supplicant( 1161): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1161): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1161): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/libc    (  365): [NET] entry_id:5   entry:0xb8c03d20  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8bff548  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8c04030  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8bfac20  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8c03e30  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8bff4b0  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
D/PMS     (  907): acquireWL(4280c3b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1120): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/PMS     (  907): releaseWL(4280c3b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/bt-btif ( 1587): ag scb idx 1 not allocated
,W/bt-btif ( 1587): ag scb idx 2 not allocated
E/bt-btif ( 1587): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1587): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1587): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1587): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1587): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1587): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1587): L2CAP - PSM: 0x0017 not found for deregistration
,D/WifiService(  907): New client listening to asynchronous messages
,D/PMS     (  907): releaseWL(427663c8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(42811dc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,W/System.err(  907): java.lang.Throwable: stack dump
,D/PMS     (  907): acquireWL(427f76b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4141 1000 null
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42629b28:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 4141): new LocationAgent instance!!
D/PMS     (  907): acquireWL(4278f5c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/HtcTagManager( 4141): HtcTagManager construction complete
D/BluetoothAdapter( 4141): 1101801624: getState(). Returning 13
E/bt_userial_mct( 1587): userial_close userial_thread_created userial_running is 1 
D/BluetoothInputDevice( 4141): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 7
D/BluetoothAdapter( 4141): 1101801624: getState(). Returning 13
D/BluetoothInputDevice( 4141): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4141): Bluetooth service connected
,W/BluetoothInputDevice( 4141): Proxy not attached to service
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4184 uid=10037 gids={50037, 3002, 3001}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  907): releaseWL(4278f5c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1370/10028)
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/BluetoothPan( 4141): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 8
D/BluetoothAdapter( 4141): 1101801624: getState(). Returning 13
D/BluetoothPan( 4141): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4141): Bluetooth service connected
,D/BluetoothMap( 4141): Create BluetoothMap proxy object
D/HtcCupdReceiver(Provider)( 4158):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 9
,I/DeviceManagement( 4082): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/PMS     (  907): releaseWL(42811dc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
,I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
E/BluetoothMap( 4141): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 4141): BluetoothSap() call bindService
,D/BluetoothManagerService(  907): Registered receivers: 10
,D/BluetoothPbap( 4141): BluetoothPbap()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 11
,W/ContextImpl( 4141): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 4141): 1101801624: getState(). Returning 13
D/BluetoothPbap( 4141): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4141): Bluetooth service connected
D/LocalBluetoothProfileManager( 4141): LocalBluetoothProfileManager construction complete
,D/HtcBtWidget_BTWidgetProvider( 4184): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4184): updateWidget(context) for widget: 
,D/Process (  907): killProcessQuiet, pid=3805
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DockEventReceiver( 4141): finishStartingService: stopping service
I/ActivityManager(  907): Killing 3805:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1587): Shutdown
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
,D/BluetoothMasReceiver( 1587): Bluetooth STATE CHANGED to 13
D/PMS     (  907): releaseWL(427f76b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,E/wpa_supplicant( 1161): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1161): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1161): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1751): Received state change = 13
,I/DeviceManagement( 4082): SessionStateController: Checking invariants...
,D/Process (  907): killProcessQuiet, pid=3399
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1751): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41aca1f0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): onDestroy() called...
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3805
,I/ActivityManager(  907): Killing 3399:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1751): deinitLeServices: null
,E/cutils-trace( 4175): Error opening trace file: No such file or directory (2)
I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4207 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  907): Killing 3579:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3579
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1161): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1161): nl80211: Unsubscribe mgmt frames handle 0xb7ca4718 (mode change)
I/wpa_supplicant( 1161): htc_wext_command_deinit +
I/wpa_supplicant( 1161): htc_wext_command_deinit -
E/wpa_supplicant( 1161): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1161): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1161): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1161): TDLS: Tear down peers
I/wpa_supplicant( 1161): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x5fc8d670
,I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x5fc8d758
W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  907): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 0
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  907):    returned false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  907): WIFI Trun OFF
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
,I/IntentController( 1120): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1120): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/DeviceManagement( 4082): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/Settings:HtcSettingsApplication( 4207): [4207/4207] onCreate()
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 6 { when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
I/DeviceManagement( 4082): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ada7e8]
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/ActivityManager(  907): Recipient 3579
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(4257fdf8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/DeviceManagement( 4082): WorkflowService: Stopping workflow service
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Recipient 3399
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4219 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/Process (  907): killProcessQuiet, pid=3627
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiService(  907): New client listening to asynchronous messages
I/ActivityManager(  907): Killing 3627:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/QuickSettingWifi( 1120): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,I/ActivityManager(  907): Recipient 3627
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,D/Process (  907): killProcessQuiet, pid=3953
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3953:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,D/CustomizationManager( 4175): ====startRecUseTime====
D/htc.customization.log.level( 4175):  is 
,W/CustomizationLogLevel( 4175): Level value is invalid, use default level 2
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Recipient 3953
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/bt-btif ( 1587): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1587): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1587): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 1587): Stopping profile services that were post enabled
,D/BluetoothHeadset(  907): Proxy object disconnected
,D/BluetoothHeadset( 1247): Proxy object disconnected
,D/BluetoothHeadset( 1120): Proxy object disconnected
I/QuickSettingMiniLite( 1120): btListener.disconnect:HEADSET
D/BluetoothHeadset( 1247): Proxy object disconnected
D/BluetoothPhoneService( 1247): BluetoothHeadset onServiceDisconnected
D/A2dpService( 1587): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1587): doQuit
,D/A2dpStateMachine( 1587): Exit Disconnected: -1
,D/BluetoothA2dp(  907): Proxy object disconnected
,D/HidService( 1587): Received stop request...Stopping profile...
,D/HealthService( 1587): Received stop request...Stopping profile...
,D/PanService( 1587): Received stop request...Stopping profile...
D/PanService( 1587): stop
,D/PanService( 1587): stop: mTetherAc send disconnect
,D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  907): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  907): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 1587): handleDebugAction() action=null
,D/BtGatt.GattService( 1587): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1587): stop()
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/BluetoothAdapterService( 1587): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1587): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1587): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1587): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 1587): cleanup
D/Avrcp   ( 1587): Unregistering previous receiver
D/BluetoothAdapterService( 1587): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1587): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1587): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1587): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1587): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1587): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1587): Cleaning up Bluetooth Health object
D/PanService( 1587): CMD_CHANNEL_DISCONNECTED
D/PanService( 1587): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1587): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1587): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1587): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1587): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1587): Setting state to 10
I/BluetoothAdapterState( 1587): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1587): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  907): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 1587): Entering OffState
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,D/BluetoothHeadset( 1120): onBluetoothStateChange: up=false
,D/PMS     (  907): acquireWL(42365bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4219 10160 null
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
D/BluetoothPbap( 4141): onBluetoothStateChange: up=false
E/BluetoothPbap( 4141): 
E/BluetoothPbap( 4141): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41ad90d0
E/BluetoothPbap( 4141): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 4141): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 4141): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 4141): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 4141): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 4141): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 4141): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothSap( 4141): onBluetoothStateChange on: false
D/BluetoothMap( 4141): onBluetoothStateChange: up=false
,E/BluetoothMap( 4141): 
E/BluetoothMap( 4141): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41ad2fb8
E/BluetoothMap( 4141): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 4141): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 4141): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 4141): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 4141): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4141): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 4141): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothPan( 4141): 
E/BluetoothPan( 4141): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41ad1c38
E/BluetoothPan( 4141): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 4141): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 4141): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 4141): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 4141): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 4141): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 4141): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothInputDevice( 4141): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 4141): 
E/BluetoothInputDevice( 4141): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41ad06a0
E/BluetoothInputDevice( 4141): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 4141): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 4141): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 4141): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 4141): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 4141): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 4141): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): releaseWL(42365bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
D/BluetoothHeadset(  907): onBluetoothStateChange: up=false
D/BluetoothA2dp(  907): onBluetoothStateChange: up=false
D/BluetoothManagerService(  907): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1795): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bf2390
D/BluetoothAdapter( 1795): onBluetoothServiceDown: done
D/BluetoothAdapter( 1247): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cc0128
D/BluetoothAdapter( 1247): onBluetoothServiceDown: done
D/BluetoothAdapter( 1120): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e856d0
D/BluetoothAdapter( 1120): onBluetoothServiceDown: done
D/BluetoothAdapter(  907): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424b88a0
D/BluetoothAdapter(  907): onBluetoothServiceDown: done
D/BluetoothAdapter( 1587): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ac1dd0
D/BluetoothDevice( 1587): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1587): onBluetoothServiceDown: done
D/BluetoothAdapter( 1434): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bfef98
,D/BluetoothAdapter( 1434): onBluetoothServiceDown: done
,D/PMS     (  907): acquireWL(42515828): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4219 10160 null
D/BluetoothAdapter( 1259): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b7b9c8
D/BluetoothAdapter( 1259): onBluetoothServiceDown: done
D/BluetoothAdapter( 3820): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41abac00
D/BluetoothAdapter( 3820): onBluetoothServiceDown: done
D/BluetoothAdapter( 1751): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41acaac0
D/BluetoothAdapter( 1751): onBluetoothServiceDown: done
D/BluetoothAdapter( 4141): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ac3300
D/BluetoothAdapter( 4141): onBluetoothServiceDown: done
D/BluetoothManagerService(  907): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@424b88a0 mBinding = false
D/BluetoothManagerService(  907): Sending unbind request.
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1120): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NfcHandover( 1259): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 4141): setBluetoothStateOff
,D/HtcTagManager( 4141): stopProxy
,W/BluetoothEventManager( 4141): unregister mProfileBroadcastReceiver fail
,D/CustomizationManager( 4175):  Read ACC file spent 0.060 (s)
,D/PMS     (  907): releaseWL(426395a0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4175): Parsing tag item name = HTC__031
D/BluetoothAdapterService( 1587): Cleaning up adapter native....
I/bt-btif ( 1587): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 1587): Done cleaning up adapter native....
V/CustomizationCIDLoader( 4175): full path : /system/customize/CID/HTC__032.xml
D/BluetoothAdapterService(1101787744)( 1587): ****onDestroy()********
D/TetherPref( 4141): persistRestoreBluetoothState false
I/CustomizationCIDLoader( 4175): Parsing tag category name = system
D/BtGatt.GattService( 1587): cleanup()
W/bt-btif ( 1587): GATTC Module not enabled/already disabled
W/bt-btif ( 1587): GATTS Module not enabled/already disabled
D/BluetoothMasReceiver( 1587): Bluetooth STATE CHANGED to 10
I/CustomizationCIDLoader( 4175): Parsing tag category name = application
V/BluetoothMasService( 1587): onDestroy: mIsEmailEnabled: true
I/CustomizationCIDLoader( 4175): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4175): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4175): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4175): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4175): Parsing tag category name = Settings
D/CustomizationManager( 4175):  Read CID file spent 0.111 (s)
,D/CustomizationManager( 4175):  All configurations done spent 0.112 (s)
D/PMS     (  907): acquireWL(4251ca28): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4141 1000 null
,W/ContextImpl( 4141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
W/HtcNativeFlag( 4175): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4175): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4175): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4175): Fail to get flag for type 'language', use default value: -1
,D/HtcBtWidget_BTWidgetProvider( 4184): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4184): updateWidget(context) for widget: 
,D/DockEventReceiver( 4141): finishStartingService: stopping service
D/PMS     (  907): releaseWL(4251ca28): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  907): acquireWL(4236d3b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4141 1000 null
,D/PMS     (  907): releaseWL(4236d3b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothMasReceiver( 1587): Bluetooth STATE CHANGED to 10
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1751): Received state change = 10
,W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41f412a0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4207): new LocationAgent instance!!
,D/HtcTagManager( 4207): HtcTagManager construction complete
W/BluetoothHeadset( 1120): Proxy not attached to service
,I/QuickSettingMiniLite( 1120): updateLiteState:no connect device!
,D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1120): 1104483632: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1120): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothInputDevice( 4207): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4207): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4207): Bluetooth service connected
,W/BluetoothInputDevice( 4207): Proxy not attached to service
,D/BluetoothPan( 4207): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
D/PMS     (  907): acquireWL(42482fe0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4219 10160 null
,D/PMS     (  907): releaseWL(42515828): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4207): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 4207): Bluetooth service connected
D/BluetoothMap( 4207): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
E/BluetoothMap( 4207): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 14
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothSap( 4207): BluetoothSap() call bindService
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 15
,D/BluetoothPbap( 4207): BluetoothPbap()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4207): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4207): Bluetooth service connected
D/LocalBluetoothProfileManager( 4207): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4207): 1101773920: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4207): setBluetoothStateOff
D/HtcTagManager( 4207): stopProxy
D/BluetoothManagerService(  907): Registered receivers: 16
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4219/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4219/10160)
,W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/BluetoothEventManager( 4207): unregister mProfileBroadcastReceiver fail
,D/Process (  907): killProcessQuiet, pid=3928
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3928:com.htc.sdm/u0a80 (adj 15): empty #17
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4175, uid=2000 user=0
,I/ActivityManager(  907): Recipient 3928
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42482fe0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3887
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/asset   (  907): Copying FileAsset 0x6bd160e8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): killProcessQuiet, pid=3820
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3887:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 3820:com.example.hello/u0a355 (adj 0): stop com.example.hello
,W/ActivityManager(  907): Force removing ActivityRecord{424b2950 u0 com.example.hello/.MainActivity t2}: app died, no saved state
I/ActivityManager(  907): Recipient 3887
,D/MediaRouterService(  907): Client com.google.android.music (pid 3887): Died!
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{421ee348 com.test.thalitest/10348} due to missing metadata
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  907): WIN DEATH: Window{423e5660 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/FeedHostManager( 1271): [onResume]
,I/FeedProviderManager( 1271): onResume
I/SocialFeedProvider( 1271): +onResume
I/SocialFeedProvider( 1271): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1271): -onResume
,D/PackageBroadcastService( 1228): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/Settings:HtcWirelessFeatureFlags( 4141): id/is att sku: 99/false
,W/SystemReader( 4141): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1862): Unregistering com.example.hello
E/acms    ( 1862): Could not unregister removed application com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
W/BroadcastQueue(  907): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  907): android.os.DeadObjectException
W/BroadcastQueue(  907): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  907): 	at android.content.IIntentReceiver$Stub$Proxy.performReceive(IIntentReceiver.java:124)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  907): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/PMS     (  907): acquireWL(4277f9d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1434 10028 null
,W/GeofencerStateMachine( 1434): Ignoring removeGeofence because network location is disabled.
,I/ConnectivityHelper( 1271): [getCurrentConnectionType] no network connection
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1271/10075)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PeopleContactsSync( 1228): CP2 sync disabled
W/SystemReader( 4141): Cannot find support_harman, use default value instead
,W/SystemReader( 4141): Cannot find effect_manager_id, use default value instead
I/Prism.ItemManager( 4069): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4069): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
V/AlarmManager(  907): sending alarm PendingIntent{42525208: PendingIntentRecord{4256b540 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1448020210882, Int=0
D/PMS     (  907): releaseWL(4277f9d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1228, uid=10028, userID:0
D/PMS     (  907): acquireWL(426395a0): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/Settings:HtcWrapHeaderInfo( 4141): no such activity!
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): releaseWL(426395a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4141): The wrap header doesn't exist in header list.
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,E/Settings:HtcWrapHeaderInfo( 4141): updateDevelopment, bPrefShow = true
I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1421): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3820 uid 10355
I/InputMethodManagerService(  907): Enable input method client, pid=1271
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  907): Resuming delayed broadcast
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/Settings:HtcUmcWidgetEnabler( 4141): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]support         :false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,W/FingerprintManager( 4141): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1862/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4099/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1434/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4099/10100)
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2926): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,E/Settings:HtcVoWifiWidgetEnabler( 4141): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4141): Failed to find provider info for com.htc.vowifi
,W/Netd    (  365): No subsystem found in netlink event
,V/Tethering(  907): remove iface:wlan0
D/Tethering(  907): interfaceRemoved wlan0
,E/Tethering(  907): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,I/IcingCorporaProvider( 2926): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  907): acquireWL(428280e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4219 10160 null
D/PMS     (  907): releaseWL(428280e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4263 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4277 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=2760
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2760:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3869
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3869:com.htc.mediamanager/u0a32 (adj 15): empty #17
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4141): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4141): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 4141): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportRecentAppsButton]support         :false
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
I/ActivityManager(  907): Recipient 2760
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/Tethering(  907): [isWifi] getHotspotEnabled: false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4141): [supportHomeButton]support         :false
,W/FingerprintManager( 4141): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4141): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4141): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  907): Recipient 3869
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key backup_uri_string
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:180)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key download_sdcard
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:181)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_prompt_version
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:182)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_prompt_feature
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:183)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_prompt_size
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:184)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_force_update
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:185)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_notify_download
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:186)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,W/GAV2    ( 4277): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_need_token
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:189)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_reserve_data_size
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putInt(FOTASettings.java:238)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:194)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_package_download_via_wifi
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:200)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_prompt_message
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:202)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Netd    (  365): No subsystem found in netlink event
,V/Tethering(  907): remove iface:p2p0
,D/Tethering(  907): interfaceRemoved p2p0
,E/Tethering(  907): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  907): acquireWL(4281d0d8): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,E/SharedPreferencesImpl( 4277): Couldn't rename file /data/data/com.google.android.gm/shared_prefs/MailAppProvider.xml to backup file /data/data/com.google.android.gm/shared_prefs/MailAppProvider.xml.bak
E/SQLiteLog( 4263): (3850) statement aborts at 24: [UPDATE settings SET _name=?,_value=? WHERE _name=?] disk I/O error
,E/SQLiteDBG( 4263): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.updater/databases/fota.db, handle = 0x5c9b9ac0
,E/UpdaterAPK | FOTASettings( 4263): Can't set key fota_optional
E/UpdaterAPK | FOTASettings( 4263): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
E/UpdaterAPK | FOTASettings( 4263): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:485)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/UpdaterAPK | FOTASettings( 4263): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:282)
E/UpdaterAPK | FOTASettings( 4263): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 4263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.Looper.loop(Looper.java:157)
E/UpdaterAPK | FOTASettings( 4263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
,D/PMS     (  907): releaseWL(4281d0d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/SQLiteDatabase( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
,E/Gmail   ( 4277): Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/Gmail   ( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Gmail   ( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Gmail   ( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/Gmail   ( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/Gmail   ( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/Gmail   ( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): acquireWL(425b1648): PARTIAL_WAKE_LOCK  Icing 0x1 1228 10028 null
,E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/SQLiteDatabase( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Gmail   ( 4277): Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/Gmail   ( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Gmail   ( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Gmail   ( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/Gmail   ( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/Gmail   ( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/Gmail   ( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Resuming delayed broadcast
E/SharedPreferencesImpl( 1228): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.deleted
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1228): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1228): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1228): Writing status failed
,E/Icing   ( 1228): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1228): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1228): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1228): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1228): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1228): 	at ghk.a(SourceFile:192)
E/Icing   ( 1228): 	at gga.n(SourceFile:1223)
E/Icing   ( 1228): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1228): 	at ger.run(SourceFile:301)
E/Icing   ( 1228): 	at ght.a(SourceFile:259)
E/Icing   ( 1228): 	at ghz.d(SourceFile:73)
E/Icing   ( 1228): 	at ghu.run(SourceFile:250)
E/Icing   ( 1228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1228): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1228): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1228): 	at ghy.run(SourceFile:50)
E/Icing   ( 1228): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1228): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1228): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1228): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1228): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1228): 	... 17 more
,E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/SQLiteDatabase( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Gmail   ( 4277): Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/Gmail   ( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Gmail   ( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Gmail   ( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Gmail   ( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/Gmail   ( 4277): 	at com.google.android.gm.provider.MailEngine.K(SourceFile:909)
E/Gmail   ( 4277): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:96)
E/Gmail   ( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/Gmail   ( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
D/PMS     (  907): releaseWL(425b1648): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4309 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  907): killProcessQuiet, pid=3998
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3998:com.htc.task.gtask/u0a67 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3998
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  907): Unable to load service info ResolveInfo{424fafb0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/dalvikvm( 4309): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4309): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 4309): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4309): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4309): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/Babel   ( 4309): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4309): MmsConfig.loadMmsSettings
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4309, uid=10111, userID:0
,W/Settings( 4309): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4332 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4309, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4309, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4309, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4309, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4309, uid=10111, userID:0
,D/PMS     (  907): acquireWL(4280b568): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4309 10111 null
,D/MessageFrequencyProvider( 4332): onCreate
,V/GetPrviateResource( 4332): GetPrviateResource
,V/GetPrviateResource( 4332): GetPrviateResource
,D/MmsCustomizationProvider( 4332): query uri: content://htc-mms-customization/mms-ua/ua_string
,E/SQLiteDatabase( 4309): Failed to open database '/data/data/com.google.android.talk/databases/babel1.db'.
E/SQLiteDatabase( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.content.t.<init>(SourceFile:297)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/SQLiteDatabase( 4309): 	at java.lang.Thread.run(Thread.java:864)
W/Babel   ( 4309): [EsDatabaseHelper] getWritableDatabase threw exception: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/dalvikvm( 4309): threadid=15: thread exiting with uncaught exception (group=0x41673e30)
,E/Babel   ( 4309): Uncaught exception in background thread Thread[Thread-462,5,main]
,E/Babel   ( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Babel   ( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Babel   ( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Babel   ( 4309): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/Babel   ( 4309): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/Babel   ( 4309): 	at com.google.android.apps.babel.content.t.<init>(SourceFile:297)
E/Babel   ( 4309): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/Babel   ( 4309): 	at java.lang.Thread.run(Thread.java:864)
,D/Process (  907): killProcessQuiet, pid=3549
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/MmsCustomizationProvider( 4332): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4309): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4309): MmsConfig.loadFromDatabase
I/ActivityManager(  907): Killing 3549:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,E/AndroidRuntime( 4309): FATAL EXCEPTION: Thread-462
E/AndroidRuntime( 4309): Process: com.google.android.talk, PID: 4309
E/AndroidRuntime( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4309): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/AndroidRuntime( 4309): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/AndroidRuntime( 4309): 	at com.google.android.apps.babel.content.t.<init>(SourceFile:297)
E/AndroidRuntime( 4309): 	at com.google.android.apps.babel.phone.cn.run(SourceFile:328)
E/AndroidRuntime( 4309): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4309): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4309): 	at cr.dT(SourceFile:414)
E/SQLiteDatabase( 4309): 	at cr.e(SourceFile:384)
E/SQLiteDatabase( 4309): 	at cs.run(SourceFile:211)
W/dalvikvm( 4309): threadid=13: thread exiting with uncaught exception (group=0x41673e30)
E/Babel   ( 4309): Uncaught exception in background thread Thread[Thread-458,5,main]
E/Babel,   ( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Babel   ( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Babel   ( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Babel   ( 4309): 	at cr.dT(SourceFile:414)
E/Babel   ( 4309): 	at cr.e(SourceFile:384)
E/Babel   ( 4309): 	at cs.run(SourceFile:211)
,E/ActivityManager(  907): App crashed! Process: com.google.android.talk
I/ActivityManager(  907): Recipient 3549
E/SQLiteDatabase( 4309): Failed to open database '/data/data/com.google.android.talk/databases/babel1.db'.
E/SQLiteDatabase( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.service.au.<init>(SourceFile:101)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.service.au.aV(SourceFile:65)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.phone.EsApplication.L(SourceFile:607)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:187)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:165)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.t(SourceFile:3147)
E/SQLiteDatabase( 4309): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:691)
E/SQLiteDatabase( 4309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4309): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Babel   ( 4309): [EsDatabaseHelper] getWritableDatabase threw exception: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/dalvikvm( 4309): threadid=14: thread exiting with uncaught exception (group=0x41673e30)
,E/Babel   ( 4309): Uncaught exception in background thread Thread[IntentService[RealTimeChatService],5,main]
,E/Babel   ( 4309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/Babel   ( 4309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/Babel   ( 4309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Babel   ( 4309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Babel   ( 4309): 	at com.google.android.apps.babel.content.ao.getWritableDatabase(SourceFile:3088)
E/Babel   ( 4309): 	at com.google.android.apps.babel.content.ao.hW(SourceFile:3108)
E/Babel   ( 4309): 	at com.google.android.apps.babel.service.au.<init>(SourceFile:101)
E/Babel   ( 4309): 	at com.google.android.apps.babel.service.au.aV(SourceFile:65)
E/Babel   ( 4309): 	at com.google.android.apps.babel.phone.EsApplication.L(SourceFile:607)
E/Babel   ( 4309): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:187)
E/Babel   ( 4309): 	at com.google.android.apps.babel.realtimechat.bn.a(SourceFile:165)
E/Babel   ( 4309): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.t(SourceFile:3147)
E/Babel   ( 4309): 	at com.google.android.apps.babel.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:691)
E/Babel   ( 4309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Babel   ( 4309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Babel   ( 4309): 	at android.os.Looper.loop(Looper.java:157)
E/Babel   ( 4309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ProviderInstaller( 4309): Installed default security provider GmsCore_OpenSSL
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
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
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,D/MessageCustFlag( 4332): sense_version=6.0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/BTAccessoryUtil( 4332): createReceiver
D/BTAccessoryUtil( 4332): registerReceiver return intent = null
D/MessageCustFlag( 4332): sku_id=99
W/SystemReader( 4332): Cannot find message_ambs_application_id, use default value instead
E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/SQLiteDatabase( 4277): 	at com.google.android.gm.provider.as.run(SourceFile:933)
E/SQLiteDatabase( 4277): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4277): threadid=15: thread exiting with uncaught exception (group=0x41673e30)
W/GAV2    ( 4277): Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/ActivityManager(  907): App crashed! Process: com.google.android.gm
,E/AndroidRuntime( 4277): FATAL EXCEPTION: MailEngine creation
E/AndroidRuntime( 4277): Process: com.google.android.gm, PID: 4277
E/AndroidRuntime( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4277): 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1156)
E/AndroidRuntime( 4277): 	at com.google.android.gm.provider.MailEngine.J(SourceFile:876)
E/AndroidRuntime( 4277): 	at com.google.android.gm.provider.as.run(SourceFile:933)
E/AndroidRuntime( 4277): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4277): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Messaging( 4332): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4332): networkCode: 
D/MessageCustFlag( 4332): sku_id=99
D/MmsConfig( 4332): SIE smsPri: null
,D/MmsConfig( 4332): networkCode: 
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/HtcTelephonyCapability( 4332): traditional single GSM/CDMA/World-phone
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
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
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(42763950): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/PMS     (  907): releaseWL(42763950): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/HtcTelephonyCapability( 4332): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4332): getRATByHtcTelephonyCapability:1
W/SystemReader( 4332): Cannot find qct_8960_interface, use default value instead
I/RemoteViews( 1120): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41f24df0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.updater 2 6 1 10
,I/RemoteViews( 1120): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41f2fbd8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.updater 1 6 1 10
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4361 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(42830880): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4361 10070 null
D/PMS     (  907): acquireWL(428008e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4361 10070 null
D/PMS     (  907): acquireWL(42801270): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4361 10070 null
I/ActivityManager(  907): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  907): releaseWL(42830880): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4361): java.lang.NullPointerException
W/System.err( 4361): java.lang.NullPointerException
W/System.err( 4361): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4361): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4361): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4361): stopSelfResult true
D/PMS     (  907): acquireWL(428008e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4361 10070 null
D/PMS     (  907): releaseWL(42801270): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(428008e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
E/TodoTaskNotifyService( 4361): java.lang.NullPointerException
,W/System.err( 4361): java.lang.NullPointerException
W/System.err( 4361): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4361): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4361): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): acquireWL(42803e68): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4361 10070 null
D/PMS     (  907): acquireWL(4283eb20): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4361 10070 null
D/PMS     (  907): releaseWL(42803e68): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(4283eb20): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4361): stopSelfResult true
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.uploader.UploaderAlarmReceiver
,E/SharedPreferencesImpl( 1228): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml.bak
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/AlarmManager(  907): sending alarm PendingIntent{4248ce78: PendingIntentRecord{427ff548 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1448020211957, Int=0
I/ActivityManager(  907): Resuming delayed broadcast
,I/GCM     ( 1370): GCM config loaded
,D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1370): [NET] getaddrinfo-, 1
,D/libc    ( 1370): [NET] getaddrinfo_proxy+
,D/PMS     (  907): acquireWL(427b3270): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1370 10028 null
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7285 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/libc    (  365): [NET]Querying server xid =7285 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  365): [NET]res_nsend:ECONNREFUSED
D/libc    (  365): [NET] -----res_nsend exit-1: xid=7285, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  365): [NET]res_queryN: exit 2
D/libc    (  365): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 1370): [NET] getaddrinfo_proxy-
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1370): [NET] getaddrinfo-, 1
D/libc    ( 1370): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2262 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/libc    (  365): [NET]Querying server xid =2262 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  365): [NET]res_nsend:ECONNREFUSED
D/libc    (  365): [NET] -----res_nsend exit-1: xid=2262, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  365): [NET]res_queryN: exit 2
D/libc    (  365): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 1370): [NET] getaddrinfo_proxy-
,I/WSP     ( 1421): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1421): Weather sync is On
D/PMS     (  907): acquireWL(427b3270): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1370 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1370/10028)
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
D/PMS     (  907): releaseWL(427b3270): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4388 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
,I/WSP     ( 1421): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Nov 20 13:50:12 CET 2015
,W/WSP     ( 1421): [Receiver] can't get active network info
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1421/10053)
,V/WSP     ( 1421): [SyncService] no data connection, stop sync service
,E/SQLiteLog(  907): (3850) statement aborts at 46: [INSERT INTO system(value,name) VALUES (?,?)] disk I/O error
,E/SQLiteDBG(  907): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.settings/databases/settings.db, handle = 0x6272bb98
,E/SQLiteDatabase(  907): Error inserting ...
E/SQLiteDatabase(  907): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase(  907): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase(  907): 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1408)
E/SQLiteDatabase(  907): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:689)
E/SQLiteDatabase(  907): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase(  907): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:312)
E/SQLiteDatabase(  907): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1421/10053)
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5d7db010
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverImageDBNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5d7db010
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5d7db010
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverBurstFlagNotReady2]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryExternalCoverCount2(BurstScannUtil.java:190)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:47)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryExternalCoverCount2(BurstScannUtil.java:190)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:47)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05568
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05878
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][isCoverZoeFlagNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryExternalCoverCount2(ZoeScanUtil.java:268)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:213)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryExternalCoverCount2(ZoeScanUtil.java:268)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:213)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05a88
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][queryExternalCoverCount2]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteDatabase( 4388): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteOpenHelper( 4388): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
,E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05b90
,W/System.err( 4388): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 4388): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 4388): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4388): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 4388): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
W/System.err( 4388): 	at andro,id.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4388): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
,W/System.err( 4388): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05da0
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverImageDBNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca038b0
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca038b0
,E/MediaManager( 4388): [BurstScannUtil],	[MediaCacheService][isCoverBurstFlagNotReady2]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
,E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829),
,E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	,at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76),
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca05568
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca07410
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][isCoverZoeFlagNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca07518
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x63570f90
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverImageDBNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x635711a0
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x635713b0
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverBurstFlagNotReady2]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca15008
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19110
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][isCoverZoeFlagNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19320
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.isCoverBurstFlagNotReady(BurstScannUtil.java:710)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:84)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19530
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverImageDBNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount(BurstScannUtil.java:285)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.doBrustDBUpdate(BurstScannUtil.java:94)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:109)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19740
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.isCoverBurstFlagNotReady2(BurstScannUtil2.java:103)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:35)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19950
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][isCoverBurstFlagNotReady2]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil.queryCoverCount2(BurstScannUtil.java:236)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.BurstScannUtil2.doBrustDBUpdate2(BurstScannUtil2.java:51)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:110)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19b60
,E/MediaManager( 4388): [BurstScannUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.isCoverZoeFlagNotReady(ZoeScanUtil.java:373)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:202)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca19d70
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][isCoverZoeFlagNotReady]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.queryCoverCount2(ZoeScanUtil.java:314)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdate(ZoeScanUtil.java:217)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:111)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x63571d78
,E/MediaManager( 4388): [ZoeScanUtil]	[MediaCacheService][queryCoverCount1]android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
,E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdateV2(ZoeScanUtil.java:47)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:116)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdateV2(ZoeScanUtil.java:47)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:116)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x63571f88
W/MediaManager( 4388): [ZoeScanUtil]	failed during doZeoDBUpdateV2
W/System.err( 4388): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 4388): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 4388): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4388): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
,W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 4388): 	at com.htc.mediamanager.updatefavorite.ZoeScanUtil.doZeoDBUpdateV2(ZoeScanUtil.java:47)
W/System.err( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:116)
W/System.err( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
,W/System.err( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4388): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4388): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.,
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212),
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.c.a(SelfieRecovery.java:43)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:117)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
,E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61),
E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224),
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	,at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.c.a(SelfieRecovery.java:43)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:117)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157),
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file,
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x63572198
W/System.err( 4388): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 4388): ,	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 4388): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4388): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
,W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
,W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 4388): 	at com.htc.mediamanager.updatefavorite.c.a(SelfieRecovery.java:43)
W/System.err( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:117)
W/System.err( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
W/System.err( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4388): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4388): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4388): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.updatefavorite.DualLensScanUtil.scanDualLensContents(DualLensScanUtil.java:125)
E/SQLiteDatabase( 4388): ,	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:126)
E/SQLiteDatabase( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteDatabase( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4388): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 4388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4388): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.updatefavorite.DualLensScanUtil.scanDualLensContents(DualLensScanUtil.java:125)
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:126),
E/SQLiteOpenHelper( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
E/SQLiteOpenHelper( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4388): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4388): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 4388): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 4388): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
E/SQLiteDBG( 4388): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x635723a8
,W/System.err( 4388): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 4388): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 4388): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 4388): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
,W/System.err( 4388): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 4388): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 4388): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 4388): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
,W/System.err( 4388): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4388): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:476)
W/System.err( 4388): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 4388): 	at com.htc.mediamanager.updatefavorite.DualLensScanUtil.scanDualLensContents(DualLensScanUtil.java:125)
W/System.err( 4388): 	at com.htc.mediamanager.IntentServiceMedia.onHandleIntent(IntentServiceMedia.java:126)
,W/System.err( 4388): 	at com.htc.mediamanager.IntentService$ServiceHandler.handleMessage(IntentService.java:76)
W/System.err( 4388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4388): 	at android.os.Looper.loop(Looper.java:157)

```
