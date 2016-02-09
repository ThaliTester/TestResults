#### Test 58751238ee11130_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 3 1 10
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 1 2 15
D/MtpService( 2368): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2368): TotalSize=1918604,MediaCacheLimit=6000
I/WVCdm   (  374): CdmEngine::OpenSession
I/WVCdm   (  374): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  374): CdmEngine::GenerateKeyRequest
--------- beginning of /dev/log/system
D/PMS     (  908): acquireWL(42f88da0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3613 10160 null
D/PMS     (  908): acquireWL(42d657d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2183 10029 null
D/MtpService( 2368): [isMtpConnected] connected: true
D/SyncApplication( 3789): Loading default preferences
D/WVCdm   (  374): PrepareKeyRequest: nonce=460508829
,W/Resources( 3789): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  908): releaseWL(42f88da0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
D/Process (  908): killProcessQuiet, pid=2900
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2900:com.android.defcontainer/u0a19 (adj 15): empty #17
I/iu.UploadsManager( 2183): End new media; added: 0, uploading: 0, time: 113 ms
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42d657d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/WifiService(  908): New client listening to asynchronous messages
I/ActivityManager(  908): Recipient 2900
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SyncApplication( 3789): Overriding preferences with custom values
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
D/SyncApplication( 3789): Updating preferences succeeded
E/SyncApplication( 3789): Application created.
I/WVCdm   (  374): CdmEngine::CloseSession
D/VolumeInfo( 3789): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3789): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3789): Found 0 mount point(s)
V/VolumeInfo( 3789): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
D/VolumeInfo( 3789): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3789): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3789): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3789): getNewCalendarAuthority()...
D/SyncApplication( 3789): enableAppOperation()+
D/SyncApplication( 3789): enableAppOperation()-
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3789, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3789, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3789): isNeorSinged() + 
D/HTCUtilities( 3789): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3789): isNeorSinged() return false
D/CDMountReceiver( 3789): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3789): USB connected to PC
D/FOTAReceiver( 3789): onReceive() enter 
D/FOTAReceiver( 3789): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/Process (  908): killProcessQuiet, pid=3540
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3822 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 3540:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3540
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Adreno-EGL( 3625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3625): Local Branch: 
I/Adreno-EGL( 3625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3625):                  aa63bbd948f41d15fc72f585e
I/Adreno-EGL( 3625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3625): Local Branch: 
I/Adreno-EGL( 3625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3625):                  aa63bbd948f41d15fc72f585e
D/HtcFingerPrintQuickLaunchProvider( 3822): -onCreate()
I/Adreno-EGL( 3625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3625): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3625): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3625): Local Branch: 
I/Adreno-EGL( 3625): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3625): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3625):                  aa63bbd948f41d15fc72f585e
V/Settings:HtcSettingsApplication( 3822): [3822/3822] onCreate()
D/TetherSettings( 3822): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3822): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3822): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3822): Cust_ConnectToPC   : spcsc>false
D/        ( 3822): Cust_ConnectToPC   : IPT>true
D/        ( 3822): Cust_ConnectToPC   : Singel_USB>false
E/cutils-trace( 3817): Error opening trace file: No such file or directory (2)
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3822): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3822): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3822): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3822): Cust_ConnectToPC   : spcsc>false
D/        ( 3822): Cust_ConnectToPC   : IPT>true
D/        ( 3822): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3822): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3822): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3822): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3822): usb_cable_connect = 1
D/SmartNS_Utility( 3822): usb_denied = 0
I/SmartNS_NSReceiver( 3822): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3822): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3822): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3822): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3822):  defaultType:0
I/SmartNS_PSService( 3822): fail notificaiton:false
D/SmartNS_Utility( 3822): usb_cable_connect = 1
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3822): usb_denied = 0
I/SmartNS_PSService( 3822): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  908): bSetPropertyMultiRAB:false
I/CheckinRequestBuilder( 2183): Classify the device as Phone.
I/RemoteViews( 1117): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1117): com.android.settings 1 0 10
D/SmartNS_Utility( 3822): usb_cable_connect = 1
D/SmartNS_Utility( 3822): usb_denied = 0
I/SmartNS_PSService( 3822): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3822/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3822/1000)
V/Tethering(  908): bSetPropertyMultiRAB:false
D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3822): usb_cable_connect = 1
D/SmartNS_Utility( 3822): usb_denied = 0
D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherUtility( 3430): can't get weather sync account
I/SmartNS_PSService( 3822): KeyGuard locked:falseKeyGuard is secured:false
I/RemoteViews( 1117): com.android.settings (true,33751552)
D/SmartNS_PSService( 3822): USB Plugged, Set USBPlugged=  truePSenabled:false
I/RemoteViews.Performance( 1117): com.android.settings 0 1 10
I/ActivityManager(  908): Resuming delayed broadcast
D/AppWidgetHostView( 1275): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1275): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1275): com.google.android.googlequicksearchbox 1 0 5
W/WeatherRequest( 3430): request cur loc, but there is no sys cur
D/SMSBackup( 3709): Got a database change event
W/Settings( 3430): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1275): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1275): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1275): com.htc.widget.weatherclock 0 6 17
I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3850 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  908): acquireWL(42e90d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =ab42 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 3817): ====startRecUseTime====
D/htc.customization.log.level( 3817):  is 
W/CustomizationLogLevel( 3817): Level value is invalid, use default level 2
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 291
D/libc    (  366): [NET]res_nsend:resplen=84
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
D/PMS     (  908): releaseWL(42e90d88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
W/ContextImpl( 3850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PowerUsageService( 3850): call getInstance()
D/PowerUsageList:PowerUsageHelper( 3850): MY_DEBUG = false
I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
W/BatSI   (  908): Couldn't get kernel wake lock stats
D/CustomizationManager( 3817):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3817): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3817): full path : /system/customize/CID/HTC__032.xml
I/CheckinTask( 2183): Sending checkin request (12130 bytes)
I/CustomizationCIDLoader( 3817): Parsing tag category name = system
I/CustomizationCIDLoader( 3817): Parsing tag category name = application
I/CustomizationCIDLoader( 3817): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3817): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3817): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3817): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3817): Parsing tag category name = Settings
D/CustomizationManager( 3817):  Read CID file spent 0.102 (s)
D/CustomizationManager( 3817):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 3817): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3817): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3817): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3817): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3817
W/BatSI   (  908): Couldn't get kernel wake lock stats
I/SensorManager(  908): mEventCount = 300
W/BatSI   (  908): Couldn't get kernel wake lock stats
I/ActivityManager(  908): Resuming delayed broadcast
D/Process (  908): killProcessQuiet, pid=3553
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3553:com.android.chrome/u0a96 (adj 15): empty #17
D/PMS     (  908): acquireWL(42d9edc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3850 1000 null
W/WeatherUtility( 1117): can't get weather sync account
D/WeatherUtility( 1345): Weather sync is On
D/WSP     ( 1345): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  908): Recipient 3553
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3871 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3430): can't get weather sync account
W/WeatherRequest( 3430): request cur loc, but there is no sys cur
W/Settings( 3430): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1275): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1275): com.htc.widget.weatherclock (true,33751552)
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/RemoteViews.Performance( 1275): com.htc.widget.weatherclock 1 7 17
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=11 [17][2][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/CheckinRequestBuilder( 2183): Classify the device as Phone.
I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2183): Checking schedule, now: 1455027644593 next: 1455550581590
I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
D/CheckinService( 2183): Recording last checkin time for package unspecified as 1455027644659
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
D/PMS     (  908): releaseWL(42f07958): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  908): releaseWL(4300c8b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 3738): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 3738): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3738): 
D/MmsAsyncWorkHandler( 3738): HM tk = 20001
,D/ReportIndicatorCache( 3738): MSG_QUERY_REPORTS >>
,I/Messaging( 3738): mccmnc> 
D/DraftCache( 3738): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3738): [DraftCache/1] refresh
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 3738): networkCode: 
,D/Messaging( 3738): ViewCache CreatePreloadOnlyConversationList
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3896 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3571
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/MessageCustFlag( 3738): sense_version=6.0
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
,D/Jerry   ( 3738): start to preload cursor >>>>>>>
,I/ActivityManager(  908): Killing 3571:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/PhoneStorageUtil( 3738): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3738): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3738): createReceiver
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 3738): [DraftCache/364] rebuildCache
D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1243): Update uri=content://mms, match=0
V/MmsProvider( 1243): selection=st=129 AND m_type!=134
D/Messaging( 3738): Reset downloading state: 0
V/MmsSystemEventReceiver( 3738): TransactionService is going to be woken up.
D/Messaging( 3738): mNeedToUpdateDate2: false
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 3738): ViewCache CreatePreload
,D/Messaging( 3738): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 3738): 1-Creating TransactionService
,D/Cust_MMSMS( 3738): _has_set_default_values_2=true
V/TransactionService( 3738): onStartCommand: 1
,D/MmsSystemEventReceiver( 3738): unRegisterForConnectionStateChanges
V/TransactionService( 3738): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 3738): Loading previous transactions.
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1243): URI_DRAFT
,D/MsgPreferenceUtils( 3738): def_index: 0
,D/DraftCache( 3738): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3738): [DraftCache/364] rebuildCache time: 2
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1243): device_type: 1
,D/MsgPreferenceUtils( 3738): globalIndex = 1
,D/MmsAsyncWorkHandler( 3738): 
D/MmsAsyncWorkHandler( 3738): HM tk = 20002
D/TransactionService( 3738): Force set service start id to 1
V/TransactionService( 3738): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3738): unRegisterForConnectionStateChanges
,D/TransactionService( 3738): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 3738): Destroying TransactionService
D/MsgPreferenceUtils( 3738): phone state: true
D/MsgPreferenceUtils( 3738): sd state: false
,D/MsgPreferenceUtils( 3738): vIndex = 0
I/ActivityManager(  908): Recipient 3571
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 3738): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 3738): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1243): sku_id=99
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,I/MusicStore( 3896): Database version: 95
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3896): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,V/AlarmManager(  908): sending alarm PendingIntent{4276e7f0: PendingIntentRecord{4260c798 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1455027645180, Int=0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3896): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3896): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3896, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 3896): Registered
,D/Process (  908): killProcessQuiet, pid=3410
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/MediaRouter( 3896): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/ActivityManager(  908): Killing 3410:com.htc.calendar/u0a13 (adj 15): empty #17
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/ActivityManager(  908): Recipient 3410
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1243): bind: true
,I/NetworkMonitor( 3896): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (3896/10154)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3933 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
D/GenericMessagesProvider( 3738): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3738): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 3738): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3738): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3738): DB info: errno = 2, errno message = No such file or directory
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/SQLiteDatabase( 3738): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3738): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3738): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3738): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3738): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3738): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3738): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3738): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3738): 	at andro,id.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3738): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3738): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3738): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3738): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3738): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 3738): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3896): getSelectedRoute
,I/NetworkMonitor( 3896): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3896/10154)
I/DFPI.ApkInstallService( 3933): onHandleIntent
,I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3896, uid=10154, userID:0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(431349f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(431349f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3948 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/Process (  908): killProcessQuiet, pid=3663
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  908): Killing 3663:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
I/ActivityManager(  908): Recipient 3663
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
I/HtcModeClient( 1508): handler message = 4011
E/HtcModeClient( 1508): Check connection and retry 5 times.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3948/10053)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3948/10053)
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{43154270 u0 ReceiverList{43154210 3948 com.htc.musicenhancer/10053/u0 remote:43153f18}}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3948): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/PMS     (  908): releaseWL(42d9edc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 3721): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3721): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/PackageManager(  908): Unable to load service info ResolveInfo{43200420 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  908): applying state to connected service
,D/AutoSetting( 1345): service - mRequestRunnable: screen on delay 10s, request NLP now
D/PMS     (  908): acquireWL(4325a230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4325a230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/AutoSetting( 1345): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1345): service - requestNLP() NetworkLocationProvider not enabled
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(4324bd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4324bd78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(432463e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(432463e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43197320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43197320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3969 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3122
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3122:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3122
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3969): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3969): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3969): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
D/WifiNative-wlan0(  908):    returned true
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=con,tent://media/internal/audio/media/262 type=3
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3933): onHandleIntent
,I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@424f4c70 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Prism.ItemManager( 3721): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3721): loadItems() com.htc.launcher.pageview.WidgetManager@424d6d38 +
,I/Prism.WidgetManager( 3721): onLoadItems() +
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@424f4c70 -
,I/Prism.WidgetManager( 3721): onLoadItems() -
,I/Prism.ItemManager( 3721): loadItems() com.htc.launcher.pageview.WidgetManager@424d6d38 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3679
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  908): Killing 3679:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3969): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3969): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3969): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,I/SoundPicker( 3969): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  908): Recipient 3679
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lil,ac.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1275): +disConnect socialManager
,I/SocialFeedProvider( 1275): disconnect socialManager
,I/SocialFeedProvider( 1275): -disConnect socialManager
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  908): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3990 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3933): onHandleIntent
,I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/EASAppSvc( 3990): [ NA ]- onCreate()
,I/EASAppSvc( 3990): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3459): put()
,I/EASAppSvc( 3990): [ NA ]- onDestroy()
,I/EASAppSvc( 3990): [ NA ]> uninitEASService
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3990/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3990/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3990/10064)
,I/EASRequestController( 3990): [ NA ]release
,I/EASAppSvc( 3990): [ NA ]< uninitEASService
,I/EASAppSvc( 3990): [ NA ]- onCreate()
,I/EASAppSvc( 3990): [ NA ]> onUpgrade: version = 63
,D/Process (  908): killProcessQuiet, pid=3721
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3721:com.htc.sense.news/u0a76 (adj 15): empty #17
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (3990/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (3990/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (3990/10064)
,D/ORMLib  ( 3459): put()
V/AlarmManager(  908): sending alarm PendingIntent{42df2b00: PendingIntentRecord{42f6ba88 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455027648991, Int=0
,I/EASAppSvc( 3990): [ NA ]- onDestroy()
,I/EASAppSvc( 3990): [ NA ]> uninitEASService
,I/EASRequestController( 3990): [ NA ]release
,I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4022 uid=10068 gids={50068, 3003, 5012}
I/EASAppSvc( 3990): [ NA ]< uninitEASService
,D/Process (  908): killProcessQuiet, pid=3756
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3756:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3721
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  908): Scheduling restart of crashed service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper in 1000ms
,I/ActivityManager(  908): Recipient 3756
,D/ORMLib  ( 3459): put()
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3770
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3770:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  908): Recipient 3770
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3969): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3969): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3969): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3896): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  908): sending alarm PendingIntent{426bf368: PendingIntentRecord{42e5fcc0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=60181, Int=0
,I/ActivityManager(  908): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4045 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ImageRamCache( 4045): create image Cache, size: 31457280.
I/ImageRamCache( 4045): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4045): create image Cache, size: 12582912.
,I/FeedSettings( 4045): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4045): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4045): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4045): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4045): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4045): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4045): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4045): last commit ulog time 1455021437164
,I/SocialManager[SocialBiLogHelper]( 4045): skip commit this time
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 6 times.
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3933): onHandleIntent
I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42fe5d58 u0 com.google.android.gms/.gcm.GcmService}
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3969): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3969): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3969): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3969): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3969): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3969): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3969): MODE_GSM access default DB
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3969): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3969): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3969): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3969): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3896): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(43249180): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1508 10014 null
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  908): releaseWL(43249180): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1243): bind: false
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4067 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  908): acquireWL(4313c0c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/Process (  908): killProcessQuiet, pid=3613
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3613:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/PMS     (  908): releaseWL(4313c0c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=30 rxSum=23} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  908): onDataStallAlarm: tag=20804 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20805 delay=15s
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4083 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Recipient 3613
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42fa7c50): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42fa7c50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4083): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  908): acquireWL(42d73d60): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42d73d60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42d4f0e8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42d4f0e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,D/NotificationService(  908): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
,D/Process (  908): killProcessQuiet, pid=3789
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4249c940 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3789:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/RemoteViews.Performance( 1117): com.htc.updater 3 9 0 10
I/[PluginManager]RegisterService( 1345): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1345): handle notify Blinkfeed plugin client changed
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{427e6960 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.updater 1 8 0 10
,I/IcingCorporaProvider( 2834): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/Gmail   ( 4083): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4083): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4083): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4083): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/IcingCorporaProvider( 2834): UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4117 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  908): Recipient 3789
,D/WifiService(  908): Client connection lost with reason: 4
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42fd6200): PARTIAL_WAKE_LOCK  AsyncService 0x1 4117 10160 null
,D/PMS     (  908): releaseWL(42fd6200): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(430a5210): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4117 10160 null
,I/ActivityManager(  908): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  908): acquireWL(42ef1b40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4117 10160 null
,D/PMS     (  908): releaseWL(430a5210): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42ef1b40): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4145 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3696
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3696:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3696
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Settings:HtcWirelessFeatureFlags( 3822): id/is att sku: 99/false
,W/SystemReader( 3822): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3822): Cannot find support_harman, use default value instead
,W/SystemReader( 3822): Cannot find effect_manager_id, use default value instead
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/Settings:HtcWrapHeaderInfo( 3822): no such activity!
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4145, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3822): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3822): updateDevelopment, bPrefShow = true
,D/Finsky  ( 4145): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Settings:HtcUmcWidgetEnabler( 3822): isSupportMusicChannel(): false
,D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4145/10074)
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]support         :false
,W/FingerprintManager( 3822): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3822): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3822): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4145/10074)
V/AlarmManager(  908): sending alarm PendingIntent{430074a0: PendingIntentRecord{4300bf78 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455027651462, Int=0
,D/Finsky  ( 4145): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/Process (  908): killProcessQuiet, pid=3709
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Settings( 4145): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4145): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  908): Killing 3709:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4145, uid=10074, userID:0
,D/Ads     ( 4145): Skipping gmscore version check
,D/Finsky  ( 4145): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4145): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4145): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3822): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3822): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3822): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3822): [supportHomeButton]support         :false
,W/dalvikvm( 4145): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/FingerprintManager( 3822): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3822): isSupportVoWifi: null
,D/Finsky  ( 4145): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3822): Failed to find provider info for com.htc.vowifi
,D/Process (  908): killProcessQuiet, pid=3850
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3850:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3850
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3709
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4183 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  908): acquireWL(42a05e50): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42a05e50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42f9c4d0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4183): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4183): MmsConfig.loadMmsSettings
,W/dalvikvm( 2183): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2183): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2183): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2183): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,W/dalvikvm( 4183): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4183): VFY: unable to resolve instance field 36
,W/dalvikvm( 4183): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2183, uid=10029, userID:0,
,V/JNIHelp ( 4183): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3738): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/PeopleDatabaseHelper( 2183): cleanUpNonGplusAccounts done.
,D/MmsCustomizationProvider( 3738): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4183): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4183): MmsConfig.loadFromDatabase
,E/Babel   ( 4183): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4183): MmsConfig.loadFromResources
,E/Babel   ( 4183): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4183): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4183, uid=10111, userID:0
,I/ProviderInstaller( 4183): Installed default security provider GmsCore_OpenSSL
,W/Settings( 4183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4183, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4183, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4183, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4183, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4183, uid=10111, userID:0
D/PMS     (  908): acquireWL(432463e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4183 10111 null
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(432463e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(4309d790): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4183 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(4309d790): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(43035008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4183 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(43035008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3430
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3430:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/PMS     (  908): acquireWL(42ff30b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Recipient 3430
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42ff30b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42fb9ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(42fb9ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  908): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  908): acquireWL(42f89520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42f89520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
D/PMS     (  908): acquireWL(42f83cf0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  908): releaseWL(42f83cf0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42d34ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/PMS     (  908): releaseWL(42d34ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(42c5e780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(42c5e780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42cc6cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42cc6cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42ef06b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42ef06b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:60, mTXpacketCount:39, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(43032210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(43032210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(432169c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4233 uid=10041 gids={50041}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(432169c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(430842a0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3459 10071 null
,I/ActivityManager(  908): Killing 3625:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=3625
,D/PMS     (  908): acquireWL(4306f6c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3459 10071 null
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/TodoTaskNotifyService( 3459): java.lang.NullPointerException
,W/System.err( 3459): java.lang.NullPointerException
W/System.err( 3459): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3459): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3459): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3459): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  908): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  908): releaseWL(430842a0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  908): releaseWL(4306f6c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3459): stopSelfResult true
I/ActivityManager(  908): Resuming delayed broadcast
D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/LocationInitializer( 2183): Restart initialization of location
,D/AuthorizationBluetoothService( 1371): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1371): Proximity feature is not enabled.
,E/MDM     ( 1223): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(42f67c48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
D/PMS     (  908): releaseWL(42f67c48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(42fcbb10): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3459 10071 null
D/PMS     (  908): acquireWL(4308a5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3459 10071 null
E/TodoTaskNotifyService( 3459): java.lang.NullPointerException
W/System.err( 3459): java.lang.NullPointerException
W/System.err( 3459): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3459): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3459): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3459): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3459): stopSelfResult false
E/TodoTaskNotifyService( 3459): java.lang.NullPointerException
W/System.err( 3459): java.lang.NullPointerException
,W/System.err( 3459): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3459): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3459): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3459): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3459): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 3459): mStartingService is null
,W/NotifyReceiver( 3459): stopSelfResult true
D/PMS     (  908): acquireWL(4321ca78): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3459 10071 null
I/ActivityManager(  908): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  908): acquireWL(4308a5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3459 10071 null
D/PMS     (  908): releaseWL(42fcbb10): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  908): releaseWL(4321ca78): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  908): releaseWL(4308a5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/WSP     ( 1345): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1345): Weather sync is On
,I/WSP     ( 1345): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 09 16:20:52 CET 2016
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  908): acquireWL(4322b038): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4183 10111 null
I/ActivityManager(  908): Recipient 3625
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
D/PMS     (  908): releaseWL(42f9c4d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1345): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1345): handle notify Blinkfeed plugin client changed
D/PMS     (  908): releaseWL(4322b038): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1345/10055)
D/PMS     (  908): acquireWL(43122500): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1345 10055 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2834): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  908): acquireWL(42df0698): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42df0698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43209520): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43209520): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43008628): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43008628): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4305dd48): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4305dd48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43051070): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43051070): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(430a46a8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(430a46a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2834): UpdateCorporaTask done [took 237 ms] updated apps [took 237 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/SensorManager(  908): mEventCount = 450
D/PMS     (  908): acquireWL(43093df8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4117 10160 null
D/PMS     (  908): releaseWL(43093df8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
,D/PMS     (  908): acquireWL(43056d58): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3871): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/AlarmManager(  908): sending alarm PendingIntent{43005098: PendingIntentRecord{42fccec0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1455027653246, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{42cd7ac0: PendingIntentRecord{430065c0 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455027653299, Int=0
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/iu.UploadsManager( 2183): End new media; added: 0, uploading: 0, time: 84 ms
,W/MediaManager( 3871): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3459): update TASK shortcut>
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2183): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(43056d58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 7 times.
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/CheckinService( 2183): Done disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/GAV2    ( 4083): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4183): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/CalendarProvider2( 1508): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1508): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,W/MediaManager( 3871): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(42d73d60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42d08df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(42d73d60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  908): releaseWL(42d08df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  908): acquireWL(42d00380): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3896 10154 null
I/ActivityManager(  908): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3896, uid=10154, userID:0
,I/MusicLeanback( 3896): Conditions not met for autocaching.
,I/MusicLeanback( 3896): Stop autocaching.
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  908): releaseWL(42d00380): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4291 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4291): Loading default preferences
,W/Resources( 4291): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 4291): Overriding preferences with custom values
,D/SyncApplication( 4291): Updating preferences succeeded
,E/SyncApplication( 4291): Application created.
D/VolumeInfo( 4291): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4291): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4291): Found 0 mount point(s)
,V/VolumeInfo( 4291): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4291): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4291): getNewCalendarAuthority()...
,D/VolumeInfo( 4291): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4291): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4291): enableAppOperation()+
,D/SyncApplication( 4291): enableAppOperation()-
,D/HTCUtilities( 4291): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4291, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4291, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4291): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4291): isNeorSinged() return false
,D/CDMountReceiver( 4291): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4291): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4291): enable CD Auto-mount: true
,D/HTCUtilities( 4291): enable auto-mount
,D/HTCUtilities( 4291): enable auto-mount
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
I/ActivityManager(  908): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(43001560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42865320 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 13 4 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{426145c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 9 2 16
,W/MediaManager( 3871): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  908): killProcessQuiet, pid=3990
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3990:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3990
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/PMS     (  908): acquireWL(430ab670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(430ab670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4309d790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252,
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(4309d790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(4303c1f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4314 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  908): releaseWL(4303c1f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/CalendarApplication( 4314): onCreate
D/ProviderChangeReceiver( 4314): ---------------------------------------------------
,D/ProviderChangeReceiver( 4314): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4314): start to updateAlertNotification!
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4328 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 4022:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4022
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4314): No fired or scheduled alerts
,D/HtcAlertUtils( 4314): -- cancelReminderNotification --
,D/HtcAlertUtils( 4314): broadcastExistReminder!
I/ActivityManager(  908): Recipient 4022
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4328): [4328/4328] onCreate()
W/ContextImpl( 4328): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=4045
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Killing 4045:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4045
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ClockThread( 1117): now=1455027659882 next=118
,I/ClockThread( 1117): now=1455027660001 next=59999
D/PMS     (  908): acquireWL(42f85f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=70196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42f85f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4314bc68 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 8 times.
,D/PMS     (  908): acquireWL(42f69e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42f69e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  908): releaseWL(43122500): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/SensorManager(  908): mEventCount = 600
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(42aa4a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,D/Finsky  ( 4145): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4145): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  908): sending alarm PendingIntent{42ce62c0: PendingIntentRecord{42fb3870 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455027665107, Int=0
D/PMS     (  908): releaseWL(42aa4a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (4145/10074)
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-,err=8
D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4145): [NET] getaddrinfo-, 1
D/libc    ( 4145): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =d1cd +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4145): [NET] getaddrinfo_proxy-, success
I/global  ( 4145): call createSocket() return a new socket.
D/libc    ( 4145): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 9 times.
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/Finsky  ( 4145): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=52 rxSum=41} preTxRxSum={txSum=30 rxSum=23}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=20805 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20806 delay=15s
D/PMS     (  908): acquireWL(42fd2368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42eccf08: PendingIntentRecord{42dfb320 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=76032, Int=0
D/PMS     (  908): releaseWL(42fd2368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/Finsky  ( 4145): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  908): acquireWL(42fb6250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{42d62450: PendingIntentRecord{42f1e710 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455027667180, Int=0
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/PMS     (  908): acquireWL(4321bd70): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4145 10074 null
,D/Finsky  ( 4145): [443] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1223): client connected with version: 8296000
D/PMS     (  908): releaseWL(42fb6250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4145): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4145): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4145): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4145): [NET] getaddrinfo-,err=8
D/libc    ( 4145): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4145): [NET] getaddrinfo-, 1
,D/libc    ( 4145): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =c328 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  366): [NET]res_nsend:resplen=87
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4145): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  908): releaseWL(4321bd70): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=14 [75][11][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:146, mTXpacketCount:60, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 10 times.
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/AutoSetting( 1345): service - mHandler: update timezone
,D/AutoSetting( 1345): service - handleMessage() stop self
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1345): service - handleMessage() quit looper
,D/AutoSetting( 1345): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3933
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3933:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3933
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42884e48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 3 11
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/SensorManager(  908): mEventCount = 750
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 11 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times.
,D/PMS     (  908): acquireWL(43125aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=92} preTxRxSum={txSum=52 rxSum=41}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=20806 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20807 delay=15s
V/AlarmManager(  908): sending alarm PendingIntent{42cd9bf8: PendingIntentRecord{42dfb320 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=91034, Int=0
D/PMS     (  908): releaseWL(43125aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4300e300): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4300e300): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4304d4e8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4304d4e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4301ee98): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4301ee98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:147, mTXpacketCount:146, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1508): Don't start project servcice
,D/HtcModeClient( 1508): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1508): connectState: CONNECTION_READY = false
,D/SilentMusic( 1508): call stop
D/HtcModeClient( 1508): close connection
,W/HtcModeClient( 1508): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1508): read the terminate packet, so break
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43057290 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  908): acquireWL(430224e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{42f58eb0: PendingIntentRecord{42f7e8a0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455027681438, Int=0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4359 uid=10078 gids={50078}
,V/AlarmManager(  908): sending alarm PendingIntent{4304f780: PendingIntentRecord{42f4ac00 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455027686430, Int=60000
,D/PMS     (  908): releaseWL(430224e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4359): SMSBackupAgentService started
,D/SMSBackup( 4359): Checking restore status
D/SMSBackup( 4359): Restore complete
,D/SMSBackup( 4359): cancelCheckAlarm
,D/SMSBackup( 4359): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/Finsky  ( 4145): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4145): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  908): killProcessQuiet, pid=3969
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3969:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  908): Recipient 3969
,V/LightsService(  908): setLight #0: color=#3e
,V/LightsService(  908): setLight #0: color=#3b
,V/LightsService(  908): setLight #0: color=#34
,V/LightsService(  908): setLight #0: color=#2d
,V/LightsService(  908): setLight #0: color=#23
,V/LightsService(  908): setLight #0: color=#20
,V/LightsService(  908): setLight #0: color=#19
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  908): setLight #0: color=#14
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/SensorManager(  908): mEventCount = 900
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42b38858
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42b38858, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@429485a8
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42c910e8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  908): mWirelessDisplayManager is null
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 319ms
,W/PnPMgr  (  359): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42f628a8)
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
D/PMS     (  908): OOBE c monitor 11
D/PMN     (  908): wakingUp
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=1275
D/PMS     (  908): acquireWL(42f63580): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,D/NfcService( 1258): applyRouting -2
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/PMS     (  908): releaseWL(42f63580): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
D/PMS     (  908): acquireWL(42f65720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/PMS     (  908): releaseWL(42f65720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
D/MtpService( 2368): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2368): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,D/AutoSetting( 1345): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  908): acquireWL(430134f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): releaseWL(430134f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20808 delay=15s
,D/AutoSetting( 1345): service - onCreate()
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/TetherSettings( 3822): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3822): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3822): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3822): Cust_ConnectToPC   : spcsc>false
D/        ( 3822): Cust_ConnectToPC   : IPT>true
D/        ( 3822): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3822): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3822): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3822): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1345): service - AddressCache: using context: com.htc.Weather
I/wpa_supplicant( 1134): SET_SCREEN_ON:On
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1134): BG scan when screen On
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1134): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): Match BG scan, scan!
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  908):    returned true
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/PSReceiver( 3822): onReceive:android.intent.action.USER_PRESENT
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/LocationManagerService(  908): request 42e79f20 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,I/ClockThread( 1117): stop update clock
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3822): onReceive:android.intent.action.USER_PRESENT
D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3822):  defaultType:0
D/AutoSetting( 1345): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,V/SRS_Proc(  374): ParamSet string: screen_state=on
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  908): updateScreenOn: false
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4382 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(43153640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43153640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43133970): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1744): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): onScreenOn: 1455027695721
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1744): onScreenOn: 1455027695722
D/PMS     (  908): releaseWL(43133970): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@429485a8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@429485a8, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42c910e8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(43137428): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
,I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@425a0500
,I/SocialFeedProvider( 1275): +onPause
,I/SocialFeedProvider( 1275): -onPause
D/PMS     (  908): acquireWL(43137d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4382 1000 null
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/SmartSyncUtils( 4382): isEpsOn(), nState = 0
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20808 mDataStallAlarmIntent=PendingIntent{42eccc40: PendingIntentRecord{42dfb320 android broadcastIntent}}
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
D/PMS     (  908): acquireWL(4320b9c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/PMS     (  908): releaseWL(43137428): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  908): releaseWL(43137d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4382): getMobilePolicyEnabled, result = true
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1134): SET_SCREEN_ON:Off
I/wpa_supplicant( 1134): htc_wext_set_keepalive +
I/wpa_supplicant( 1134): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1134): getPrivFuncNum +	
I/wpa_supplicant( 1134): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1134): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1134): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1134): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1134): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1134): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:147, mTXpacketCount:147, avgLinkspeed:24,mAvgTxRate54,
D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  374): ParamSet string: screen_state=off
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4382): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4382): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4382): isEpsOn(), nState = 0
D/WifiService(  908): New client listening to asynchronous messages
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42c910e8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42c910e8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42c910e8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42c910e8
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42abcfc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42abcfc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  908): acquireWL(431caa88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(431caa88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431cbf10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(431cbf10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1744): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1744): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1744): onScreenOff
,D/AutoSetting( 1345): service - mHandler: cancel location update
,D/AutoSetting( 1345): service -           changes count: 0
,D/wpa_supplicant( 1134): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(4320b9c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1134): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1134): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 9
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1134): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1134): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1134): Add randomness: count=11 e,ntropy=5
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  908): doString: LIST_DONGLES
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE,
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=0
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-50
I/wpa_supplicant( 1134): tsf=0000000107855480
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-58
,I/wpa_supplicant( 1134): tsf=0000000107855505
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700,
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=2
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
,I/wpa_supplicant( 1134): level=-83
I/wpa_supplicant( 1134): tsf=0000000107855517
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
D/WirelessDisplayService(  908): getDiscoveryDongleList
,D/WifiStateMachine(  908): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,D/WifiP2pService(  908): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  908): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@431f2bb8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431f2bb8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@431f2bb8 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 107855480, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 107855505, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 107855517, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  908): add 3 to mScanResults
,V/ScoreHelper(  908): Only print Top 10 in ApScanList
V/ScoreHelper(  908):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  908):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  908):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  908):  + computeScore(NG700): 1
D/WifiStateMachine(  908): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (3) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
,D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (3) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList,
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4067
,I/ActivityManager(  908): Killing 4067:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4067
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  908): killProcessQuiet, pid=3948
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3948:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3948
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43129768 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  908): acquireWL(43251bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42fa3450: PendingIntentRecord{43041d28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122632, Int=0
,D/PMS     (  908): releaseWL(43251bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(432538f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(431d2b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(431d2b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(432538f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431d8ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(431d8ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1134): wpa_supplicant_scan enter
I/wpa_supplicant( 1134): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1134): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1134): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1134): nl80211: Event message available
,D/wpa_supplicant( 1134): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  908): acquireWL(431dcad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(4324d598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431f7458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1455027712864 tag=VacuumService
,D/PMS     (  908): releaseWL(431dcad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4324d598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431be5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(431be5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(431f7458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431b6b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(431b6b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(431968e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(431968e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43196378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(43196378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43195a10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): acquireWL(42da89c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42da89c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42c2c5f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43195a10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42d2fbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(42d2fbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1134): Change stage from stage3 to stage1
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL,
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 3691 seconds from now (1455027713619)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  366): [NET] +++++ res_nsend xid =afbc +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success,
,D/wpa_supplicant( 1134): nl80211: Event message available
D/wpa_supplicant( 1134): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1134): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1134): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1134): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1134): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1134): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): Selecting BSS from priority group 1
I/wpa_supplicant( 1134): Recent assoc_freq = 2412 rssi = -90
D/wpa_supplicant( 1134): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1134): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1134): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1134): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1134):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1134):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-90
I/wpa_supplicant( 1134): Start print parameters
I/wpa_supplicant( 1134): wpa_s->wpa_state is 9
I/wpa_supplicant( 1134): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1134): isConcurrentMode() is 0
I/wpa_supplicant( 1134): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1134): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1134): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1134): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1134): wpa_s->reassociate is 0
I/wpa_supplicant( 1134): wpa_s->is_screen_on 0
I/wpa_supplicant( 1134): wpa_s->ifname wlan0
I/wpa_supplicant( 1134): End print parameters
I/wpa_supplicant( 1134): selected network = 1
D/wpa_supplicant( 1134): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1134): nl80211: Received scan results (3 BSSes)
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1134): nl80211: Survey data missing
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1134): Sorted scan results
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
I/wpa_supplicant( 1134): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1134): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-90
D/wpa_supplicant( 1134): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1134): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1134): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1134): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_s,upplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1134): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1134): wpa_supplicant_pick_network+
I/wpa_supplicant( 1134): clear disabled list - type=1
I/wpa_supplicant( 1134): No suitable network found
W/wpa_supplicant( 1134): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1134): State: INACTIVE -> INACTIVE
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  908): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  908): getDiscoveryDongleList
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1134): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1134): reply (376) for get BSS: id=0
I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1134): freq=5220
I/wpa_supplicant( 1134): level=-50
,I/wpa_supplicant( 1134): tsf=0000000107855480
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG7005g
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=1
,I/wpa_supplicant( 1134): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-90
I/wpa_supplicant( 1134): tsf=0000000125022465
I/wpa_supplicant( 1134): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1134): ssid=NG700,
I/wpa_supplicant( 1134): ====
I/wpa_supplicant( 1134): id=2
I/wpa_supplicant( 1134): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1134): freq=2412
I/wpa_supplicant( 1134): level=-83
,I/wpa_supplicant( 1134): tsf=0000000125022478
I/wpa_supplicant( 1134): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1134): ssid=Gonzos
I/wpa_supplicant( 1134): ####
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/WifiStateMachine(  908): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -90, 0
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 107855480, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2412, timestamp: 125022465, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 125022478, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  908): add 3 to mScanResults
V/ScoreHelper(  908): Only print Top 10 in ApScanList
,V/ScoreHelper(  908):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-50], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  908):  + ScoreResult:  81, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi:  0 [-90], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  908):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  908):  + computeScore(NG700): 1
D/WifiStateMachine(  908): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (3) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (3) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4,
D/libc    ( 1223): [NET] getaddrinfo-,err=8,
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8,
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=14 [7][1][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1134): Change stage from stage1 to stage3
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(42c2c5f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4321bcf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(4321bcf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42d850e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(42d850e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42fd03b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fd03b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42ee9a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(42ee9a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(432283e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42d3e398: PendingIntentRecord{430a2038 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136650, Int=0
,D/PMS     (  908): releaseWL(432283e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,D/AutoSetting( 1345): service - handleMessage() stop self
,D/AutoSetting( 1345): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=3738
,I/ActivityManager(  908): Killing 3738:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1345): service - handleMessage() quit looper
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3738
,D/PMS     (  908): acquireWL(43034750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42f34918: PendingIntentRecord{42c5d6e0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142398, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(4300b558): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(43034750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =3132 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE,
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 44
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(4300b558): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(42fbeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42fbeee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(430715a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{42895800: PendingIntentRecord{42ef4f78 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171958, Int=0
,D/PMS     (  908): releaseWL(430715a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(42f588f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42f588f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4307cc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4307cc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42f572b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42f572b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4307dca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4307dca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4311e188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4311e188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(42d51c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d51c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42906de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=310196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42906de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(430098e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(430098e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Process (  908): killProcessQuiet, pid=4233
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4233:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4233
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4303a180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/PMS     (  908): releaseWL(4303a180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43116f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=370196, Int=0
,D/PMS     (  908): releaseWL(43116f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43207ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43207ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(43205710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43205710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43049a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=430196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43049a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43028d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43028d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4321ab00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4321ab00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4302c3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=490196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4302c3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4305ff30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4305ff30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(43015120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(43015120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43256938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=550196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43256938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431e33a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431e33a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42fe0e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42fe0e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(431e4ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=610197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(431e4ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431c4088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431c4088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete,
,D/PMS     (  908): acquireWL(43194568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=670197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43194568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431f5050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431f5050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42d63658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=730197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42d63658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43048f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(43048f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4313fde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4313fde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43012f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=790196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43012f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431e0738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431e0738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(431d7f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431d7f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4319cf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=850197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4319cf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4311bd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4311bd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43250898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43250898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43018db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=910196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43018db0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431caad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  908): n_update end
D/HtcPowerSaver(  908): updateBatteryInfo
,D/PMS     (  908): releaseWL(431caad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43254950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42709120: PendingIntentRecord{42df9950 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782805, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{42fbb820: PendingIntentRecord{43082dd8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=946283, Int=0
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4449 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{42d7fda0: PendingIntentRecord{42fb9a60 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455027802238, Int=10800000
,D/PMS     (  908): acquireWL(431bd410): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42ce1790: PendingIntentRecord{430045b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455028522608, Int=900000
,D/PMS     (  908): releaseWL(431bd410): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(43254950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageService( 4382): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4382): MY_DEBUG = false
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4449/10049)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/ActivityManager(  908): Killing 4183:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4183
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4183
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(430207a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(430207a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42f806e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1371/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1371/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024987
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025244
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025247
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026896
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360026908
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029740
,D/PMS     (  908): releaseWL(42f806e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  908): acquireWL(42df61b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=970197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42df61b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42db3ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42db3ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-,
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42a04398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/SmartSyncUtils( 4382): isEpsOn(), nState = 0
V/AlarmManager(  908): sending alarm PendingIntent{42d78048: PendingIntentRecord{4320e8a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455028596379, Int=0
D/PMS     (  908): acquireWL(4280a0e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4382 1000 null
D/PMS     (  908): releaseWL(42a04398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4382): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4382): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4382): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4382): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081137000
,D/SmartSyncScreenOnOffTimeReceiver( 4382): SettingOffTime = 1455069600000, randomSettingOffTime = 1455074822000
,D/SmartSyncScreenOnOffTimeReceiver( 4382): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4382): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4382): bNightModeTurnOffOnce = false
,D/PMS     (  908): releaseWL(4280a0e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  908): acquireWL(42d9a490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d9a490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42d4e660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1030196, Int=0
,D/PMS     (  908): releaseWL(42d4e660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42cd3938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42cd3938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42acc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1090196, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42acc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(427b4378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427b4378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42eb0dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42eb0dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
V/NotificationService(  908): batLight: plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c80000
D/qdlights(  908): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1560): [EventService] reorderNotification, total:1
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1599): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/ContextImpl( 4382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3822): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3822): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3822): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3822): Cust_ConnectToPC   : spcsc>false
,D/        ( 3822): Cust_ConnectToPC   : IPT>true
,D/        ( 3822): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3822): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3822): Index of the first 1 = -1
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,W/Settings( 3822): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3822): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3822): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3822): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3822): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  908): acquireWL(42f9d030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1150197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42f9d030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4275bed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4275bed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43011d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{426bf368: PendingIntentRecord{42e5fcc0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1186199, Int=0
,D/PMS     (  908): acquireWL(426dbff0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43011d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(430227e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=12 [127][16][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1134): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1134): nl80211: survey data missing!
E/wpa_supplicant( 1134): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1134): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(430513f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 908 1000 WorkSource{10160}
,D/PMS     (  908): acquireWL(42d783e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 908 1000 WorkSource{10029}
,D/PMS     (  908): releaseWL(426dbff0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(430227e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(4308f0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(4308f0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(431505a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(431505a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(42d9f890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42d9f890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(431c2680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(430513f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  908): releaseWL(431c2680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315361186488
,W/AlarmManager(  908): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42fcfff0: PendingIntentRecord{42ef0620 com.google.android.gms startService}}) : type=2 triggerAtTime=315361186488 win=-1 tElapsed=315361186488 maxElapsed=551881186485 interval=0 standalone=false
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(432178a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42d783e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  908): releaseWL(432178a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(4306a5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42cd23d8: PendingIntentRecord{42b08450 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1210197, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4306a5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43001608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43001608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(43217148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{426bf368: PendingIntentRecord{42e5fcc0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1216318, Int=0
,D/PMS     (  908): acquireWL(42fa08a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42f80930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43217148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): releaseWL(42fa08a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(42f80930): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(4306a1c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4306a1c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4477): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4477): ====startRecUseTime====
D/htc.customization.log.level( 4477):  is 
W/CustomizationLogLevel( 4477): Level value is invalid, use default level 2
D/CustomizationManager( 4477):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4477): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4477): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4477): Parsing tag category name = system
I/CustomizationCIDLoader( 4477): Parsing tag category name = application
I/CustomizationCIDLoader( 4477): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4477): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4477): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4477): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4477): Parsing tag category name = Settings
D/CustomizationManager( 4477):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4477):  All configurations done spent 0.152 (s)
W/HtcNativeFlag( 4477): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4477): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4477): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4477): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4477, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  908): Skipping PackageSetting{42c2dfb8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  908): Skipping PackageSetting{42c33e58 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/PackageManager(  908): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  908): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  908): acquireWL(43320ac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
D/PMS     (  908): releaseWL(43320ac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/[PluginManager]RegisterService( 1345): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  908):   Scheme: "smsto"
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1345): handle notify Blinkfeed plugin client changed
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/IcingCorporaProvider( 2834): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4491 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/IcingCorporaProvider( 2834): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  908): Unable to load service info ResolveInfo{431eedc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4491): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4491): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4491): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4491): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4491): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4491): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4491): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4491): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4491): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4491): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4491): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4491): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4491): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4491): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4491): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4491): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4491): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4491): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4491): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4491): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4491): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4491): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4491): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4491): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4491): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4491): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4491): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4491): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4491): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4491): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4491): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4491): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4491): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4491): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4491): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4491): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4491): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4491): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4491): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4491): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4491): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4491): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4491): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4491): threadid=11: thread exiting with uncaught exception (group=0x42031e30)
E/AndroidRuntime( 4491): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4491): Process: com.google.android.apps.docs, PID: 4491
E/AndroidRuntime( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4491): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4491): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4491): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4491): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4491): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteDatabase( 4491): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4491): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4491): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4491): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4491): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4491): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4491): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4491): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4491): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4491): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4491): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4491): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4491): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4491): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4491): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4491): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4491): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4491): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4491): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4491): Opened ClientFlag.db in read-only mode
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4509 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4491): killProcess, pid=4491
D/Process ( 4491): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/BroadcastQueue(  908): Skipping deliver [background] BroadcastRecord{42f7f038 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42f0cb00 4491 com.google.android.apps.docs/10100/u0 remote:42b534e8}: process crashing
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  908): Recipient 4491
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4491) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4509): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4509): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4509): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4509): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4509): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4509): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4509): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4509): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4509): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4509): threadid=10: thread exiting with uncaught exception (group=0x42031e30)
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4523 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4509): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4509): Process: com.android.keychain, PID: 4509
E/AndroidRuntime( 4509): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4509): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4509): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4509): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4509): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4509): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4509): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4509): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4509): killProcess, pid=4509
D/Process ( 4509): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455028856860.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 4509
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4509) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4523): getInstance(Context context)
D/AppTag  ( 4523): getInstance(Context context)
D/AppTag  ( 4523): onCreate()
D/PMS     (  908): acquireWL(43086e10): PARTIAL_WAKE_LOCK  AsyncService 0x1 4117 10160 null
D/PMS     (  908): releaseWL(43086e10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  908): killProcessQuiet, pid=3459
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/dalvikvm( 4145): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  908): Killing 3459:com.htc.task/u0a71 (adj 15): empty #17
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2183): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2183): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3459
W/dalvikvm( 2183): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2183): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2183): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2183): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2183): App measurement is starting up, version: 8489
I/GMPM-SVC( 2183): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655585b0
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/DriveAsyncService( 2183): disk I/O error (code 3850)
E/DriveAsyncService( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2183): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2183): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2183): Opening the database failed, dropping and recreating it
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6e327008
W/dalvikvm( 2183): threadid=48: thread exiting with uncaught exception (group=0x42031e30)
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2183): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2183): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2183): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 2183): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 2183): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2183): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2183): Process: com.google.android.gms, PID: 2183
E/AndroidRuntime( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2183): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2183): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2183): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2183): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  908): acquireWL(431e1df0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/SQLiteOpenHelper( 2183): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2183): killProcess, pid=2183
W/SQLiteOpenHelper( 2183): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/ActivityManager(  908): Recipient 2183
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms (pid 2183) has died.
D/WifiService(  908): Client connection lost with reason: 4
D/PMS     (  908): handleWLDeath(431e1df0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 30999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 40999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 40999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 40998ms
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@424f4c70 +
I/Prism.WidgetManager( 1275): onLoadItems() +

```
