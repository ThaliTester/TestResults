#### Test 757892681403989_thali02_HTC-HTC One M8s Logs


```
--------- beginning of main
07-05 11:58:48.448   411   411 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 396us total 25.670ms
07-05 11:58:48.448  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
07-05 11:58:48.448  5314  5314 I MultiDex: VM with version 2.1.0 has multidex support
07-05 11:58:48.448  5314  5314 I MultiDex: install
07-05 11:58:48.448  5314  5314 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 11:58:48.488  2228  5355 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 63 ms
--------- beginning of system
07-05 11:58:48.488   969  1993 D PMS     : releaseWL(10b5a0b7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
07-05 11:58:48.498   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:58:48.498   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:58:48.508   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=15.8, 0.0, 0.0  rx=19.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1166086716] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:58:48.508   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:48.508   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=15.8, 0.0, 0.0  rx=19.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1166086713] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:58:48.508   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:58:48.508   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:58:48.508  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-05 11:58:48.518  1432  1432 I wpa_supplicant: environment dirty rate=0 [14][0][0]
07-05 11:58:48.518   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:58:48.518   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:58:48.518   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
07-05 11:58:48.518   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=14.88 txretriesrate=0.00 rxrate=15.42 userTriggerdPenalty0
07-05 11:58:48.518   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:58:48.518   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:58:48.518   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
07-05 11:58:48.528  3698  3698 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
07-05 11:58:48.528  3698  5358 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
07-05 11:58:48.528   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:48.528   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:58:48.528  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:58:48.528  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-05 11:58:48.528  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-05 11:58:48.528  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 +
07-05 11:58:48.528  5331  5331 D SyncApplication: Loading default preferences
07-05 11:58:48.528  5314  5365 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-05 11:58:48.528  5314  5365 I SocialManager[SocialBiLogHelper]: last commit ulog time 1467694861030
07-05 11:58:48.528  5314  5365 I SocialManager[SocialBiLogHelper]: skip commit this time
07-05 11:58:48.528  1623  1836 I Prism.WidgetManager: onLoadItems() +
07-05 11:58:48.538  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
07-05 11:58:48.538  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:48.538  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:58:48.538  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 11:58:48.538   969  1442 D Process : killProcessQuiet, pid=4863
07-05 11:58:48.538   969  1442 I ActivityManager: Killing 4863:com.htc.cs.pns/u0a71 (adj 15): empty #17
07-05 11:58:48.538   969  1442 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:58:48.548  5331  5331 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
07-05 11:58:48.578  1623  1836 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-05 11:58:48.588   969   969 E WifiTrafficPoller: ADD_CLIENT: 7
07-05 11:58:48.588   969  1268 D WifiService: New client listening to asynchronous messages
07-05 11:58:48.608   969  1676 I ActivityManager: Recipient 4863
07-05 11:58:48.628  5331  5331 D SyncApplication: Overriding preferences with custom values
07-05 11:58:48.638  3698  5368 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
07-05 11:58:48.638  3698  5368 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
07-05 11:58:48.638  3698  5368 D MediaScannerServiceEx: [handleExternalVolume] ext storage
07-05 11:58:48.638  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-05 11:58:48.638  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-05 11:58:48.638  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/usb
07-05 11:58:48.638  3698  5368 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
07-05 11:58:48.638  3698  5368 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
07-05 11:58:48.638  5331  5331 D SyncApplication: Updating preferences succeeded
07-05 11:58:48.648  5331  5331 E SyncApplication: Application created.
07-05 11:58:48.658  3698  5368 D MediaProvider: [update][12]#0#
07-05 11:58:48.658  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 11:58:48.658  3698  5368 D MediaProvider: [update][2]#0#
07-05 11:58:48.658  5331  5331 I CalendarDefines: getNewCalendarAuthority()...
07-05 11:58:48.668  5331  5374 W VolumeInfo: Unable to read mount points
07-05 11:58:48.668  5331  5374 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.io.FileReader.<init>(FileReader.java:66)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
07-05 11:58:48.668  5331  5374 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-05 11:58:48.668  5331  5374 W VolumeInfo: 	... 13 more
07-05 11:58:48.668   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5331, uid=10005, userID:0
07-05 11:58:48.668  5331  5374 V VolumeInfo: Found 0 mount point(s)
07-05 11:58:48.668   969  1681 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
07-05 11:58:48.668  5331  5374 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
07-05 11:58:48.668   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5331, uid=10005, userID:0
07-05 11:58:48.668  5331  5374 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
07-05 11:58:48.668   969  1464 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
07-05 11:58:48.668  5331  5331 D SyncApplication: enableAppOperation()+
07-05 11:58:48.668  5331  5331 D SyncApplication: enableAppOperation()-
07-05 11:58:48.678  3698  5368 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
07-05 11:58:48.678  3698  5368 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
07-05 11:58:48.678  3698  5368 D MediaProvider: [update][18]#1#
07-05 11:58:48.678  5331  5374 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
07-05 11:58:48.678  5331  5374 W VolumeInfo: Can not create volume ID for unmounted volume null
07-05 11:58:48.678  5331  5331 D HTCUtilities: isNeorSinged() + 
07-05 11:58:48.678  3698  5368 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
07-05 11:58:48.688   969  1981 D PMS     : acquireWL(2707d7cb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3698 10017 null
07-05 11:58:48.688  5331  5331 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
07-05 11:58:48.688  5331  5331 D HTCUtilities: isNeorSinged() return false
07-05 11:58:48.698  3698  5368 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
07-05 11:58:48.708  5331  5331 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
07-05 11:58:48.708  5331  5331 D CDMountReceiver: USB connected to PC
07-05 11:58:48.718  1443  2811 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 11:58:48.718  1443  2811 D DotMatrix: [EventService] notificationPosted, eventType:1014
07-05 11:58:48.718  1339  1339 I RemoteViews: reapply : com.google.android.gms 2 40
07-05 11:58:48.718  1443  2811 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
07-05 11:58:48.718  2228  4984 W CheckinRequestBuilder: awaiting user notification for token
07-05 11:58:48.728  5331  5331 D FOTAReceiver: onReceive() enter 
07-05 11:58:48.728  5331  5331 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
07-05 11:58:48.728  4263  4263 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
07-05 11:58:48.728  4263  4263 D         : Cust_ConnectToPC   : Internet_Sharing>true
07-05 11:58:48.728  4263  4263 D         : Cust_ConnectToPC   : Modem_Link>false
07-05 11:58:48.728  4263  4263 D         : Cust_ConnectToPC   : spcsc>false
07-05 11:58:48.728  4263  4263 D         : Cust_ConnectToPC   : IPT>true
07-05 11:58:48.738  4263  4263 D         : Cust_ConnectToPC   : Singel_USB>false
07-05 11:58:48.738  4263  4263 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 11:58:48.738  4263  4263 E SmartNS_Utility: hasRemovableStorageSlot: true
07-05 11:58:48.738  4263  4263 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
07-05 11:58:48.738  4263  4263 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
07-05 11:58:48.738  4263  4263 D SmartNS_Utility: usb_cable_connect = 1
07-05 11:58:48.738  4263  4263 D SmartNS_Utility: usb_denied = 0
07-05 11:58:48.738  4263  4263 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
07-05 11:58:48.738  4263  4263 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
07-05 11:58:48.738  4263  4263 I SmartNS_PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC
07-05 11:58:48.738  4263  4263 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
07-05 11:58:48.748  4263  4263 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC
07-05 11:58:48.748  4263  4263 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 11:58:48.748  4263  4263 I SmartNS_PSService:  defaultType:0
07-05 11:58:48.758  2228  4984 I CheckinRequestBuilder: Classify the device as Phone.
07-05 11:58:48.758  1572  2200 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-05 11:58:48.758  4263  4263 I SmartNS_PSService: fail notificaiton:false
07-05 11:58:48.758  4263  4263 D SmartNS_Utility: usb_cable_connect = 1
07-05 11:58:48.758  4263  4263 D SmartNS_Utility: usb_denied = 0
07-05 11:58:48.758  4263  4263 I SmartNS_PSService: usb notificaiton:true
07-05 11:58:48.768   969  1442 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 11:58:48.768  1572  2200 D PhoneApp: -- N1 =0
07-05 11:58:48.768  1572  2200 D PhoneApp: -- N2 =0
07-05 11:58:48.768  1572  2200 D PhoneApp: -- N3 =0
07-05 11:58:48.768   969   989 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=5380 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
07-05 11:58:48.788  4263  4263 D SmartNS_Utility: usb_cable_connect = 1
07-05 11:58:48.788  1443  1462 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
07-05 11:58:48.788  1339  1339 I RemoteViews: reapply : com.android.settings 1 36
07-05 11:58:48.788  4263  4263 D SmartNS_Utility: usb_denied = 0
07-05 11:58:48.788  4263  4263 I SmartNS_PSService: usb notificaiton:true
07-05 11:58:48.788   969  1681 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 11:58:48.808  4263  4263 D SmartNS_Utility: usb_cable_connect = 1
07-05 11:58:48.808  4263  4263 D SmartNS_Utility: usb_denied = 0
07-05 11:58:48.808  1443  2811 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
07-05 11:58:48.818  1339  1339 I RemoteViews: reapply : com.android.settings 1 36
07-05 11:58:48.818  4263  4263 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false
07-05 11:58:48.818  4263  4263 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
07-05 11:58:48.828   969  2390 D Process : killProcessQuiet, pid=4894
07-05 11:58:48.828   969  2390 I ActivityManager: Killing 4894:com.google.android.music:main/u0a159 (adj 15): empty #17
07-05 11:58:48.828   969  2390 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:58:48.838  5380  5380 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 11:58:48.868  5371  5403 E cutils-trace: Error opening trace file: Permission denied (13)
07-05 11:58:48.888  1623  1836 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 11:58:48.908   969  4144 I ActivityManager: Recipient 4894
07-05 11:58:48.908   969  1676 D MediaRouterService: Client com.google.android.music (pid 4894): Died!
07-05 11:58:48.958  5371  5371 D CustomizationManager: ====startRecUseTime====
07-05 11:58:48.958  5371  5371 D htc.customization.log.level:  is 
07-05 11:58:48.958  5371  5371 W CustomizationLogLevel: Level value is invalid, use default level 2
07-05 11:58:48.958   969  2390 D PMS     : acquireWL(3259b6c1): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5380 10069 null
07-05 11:58:48.958   969  4144 I ActivityManager: Killing 4787:com.htc.bgp/u0a11 (adj 15): empty #17
07-05 11:58:48.958   969  4144 D Process : killProcessQuiet, pid=4787
07-05 11:58:48.958   969  4144 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-05 11:58:48.968   969  1676 D PMS     : acquireWL(2027ce66): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5380 10069 null
07-05 11:58:48.968  2228  4984 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
07-05 11:58:49.038  5371  5371 D CustomizationManager:  Read ACC file spent 0.049 (s)
07-05 11:58:49.038  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__032
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__031
07-05 11:58:49.048  5371  5371 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 11:58:49.048  5371  5371 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = system
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = application
07-05 11:58:49.048   969  1681 I ActivityManager: Recipient 4787
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: Parsing tag category name = ACC
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 42507
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 21902
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23420
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 22299
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 24002
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23210
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23205
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23806
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23430
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23408
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 27205
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-05 11:58:49.048  5371  5371 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-05 11:58:49.048  5371  5371 D CustomizationManager:  Read CID file spent 0.093 (s)
07-05 11:58:49.048  5371  5371 D CustomizationManager:  All configurations done spent 0.094 (s)
07-05 11:58:49.058  1623  1836 W asset   : Copying FileAsset 0xad05c508 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-05 11:58:49.068   969  1993 D PMS     : releaseWL(3259b6c1): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
07-05 11:58:49.078  5380  5416 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-05 11:58:49.078  5380  5416 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-05 11:58:49.078  5380  5416 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
07-05 11:58:49.078  5380  5416 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
07-05 11:58:49.088   969  2390 D PMS     : releaseWL(2027ce66): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
07-05 11:58:49.078  5380  5416 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:58:49.078  5380  5416 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:58:49.078  5380  5416 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:58:49.098   969   969 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5419 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
07-05 11:58:49.108  2228  4984 I CheckinService: Checking schedule, now: 1467712729116 next: 1468249560984
07-05 11:58:49.108   969  1050 D PMS     : acquireHCC(1ee51a54): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
07-05 11:58:49.108  2228  4984 I CheckinService: active receiver: disabled
07-05 11:58:49.108   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2228, uid=10024, userID:0
07-05 11:58:49.108  5380  5416 W NotifyReceiver: stopSelfResult true
07-05 11:58:49.108   969  1050 D PMS     : acquireHCC(2689fdfd): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
07-05 11:58:49.108   969   989 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5371 on display 0
07-05 11:58:49.128   969   989 D PMS     : acquireWL(1a387c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 969 1000 null
07-05 11:58:49.128   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-05 11:58:49.128   969   969 E WifiTrafficPoller:  packet count Tx=145 Rx=202
07-05 11:58:49.128   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:58:49.128  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:58:49.128  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:58:49.138  1623  1836 I Prism.WidgetManager: onLoadItems() -
07-05 11:58:49.138  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 -
07-05 11:58:49.138   969  1038 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/7
07-05 11:58:49.148  1623  1836 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 11:58:49.148  1623  1836 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
07-05 11:58:49.158   969  1981 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5440 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:58:49.168  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-05 11:58:49.168  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-05 11:58:49.278   969  4144 D PMS     : releaseWL(37511130): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:49.288  1623  1623 I FeedHostManager: [onPause]
07-05 11:58:49.288  1623  1623 I FeedProviderManager: onPause
07-05 11:58:49.288  1623  1623 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@cf9aba6
07-05 11:58:49.288  1623  2596 I SocialFeedProvider: +onPause
07-05 11:58:49.288  1623  2596 I SocialFeedProvider: -onPause
07-05 11:58:49.298  1623  1623 I ContextualWidget: onPause
07-05 11:58:49.298  1623  1623 I ContextualWidget: notifyWidgetDeactive
07-05 11:58:49.308   969  1671 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-05 11:58:49.318  1623  1623 I TrimMemoryManager: [trimMemory] 20
07-05 11:58:49.318  1623  1623 I Launcher: Deferring update until onResume
07-05 11:58:49.318   969  1036 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-05 11:58:49.318  1623  1623 D Launcher: waitUntilResume // bindAppsAdded
07-05 11:58:49.318   969  1036 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 11:58:49.318   969  1036 D StatusBarManagerService: hiding MENU key
07-05 11:58:49.338  5419  5419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,07-05 11:58:49.378   969   988 D Process : killProcessQuiet, pid=4936,
07-05 11:58:49.378   969   988 I ActivityManager: Killing 4936:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,07-05 11:58:49.378   969   988 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:49.388  1623  1623 E ActivityThread: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
07-05 11:58:49.388  1623  1623 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
,07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 11:58:49.388  1623  1623 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-05 11:58:49.408   969  2390 D PMS     : acquireWL(3abb606d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:58:49.438   969  4144 I ActivityManager: Recipient 4936,
,07-05 11:58:49.488   969   988 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{34804b9b u0 com.htc.launcher/.Launcher t103}
,07-05 11:58:49.488   969   989 D PMS     : releaseWL(3abb606d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:49.508   969   988 I ActivityManager: Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5463 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,07-05 11:58:49.508   969  1993 I art     : Explicit concurrent mark sweep GC freed 30933(1729KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.852ms total 173.426ms
,07-05 11:58:49.538  3698  5368 D MediaProvider: [update][10]#1#
,07-05 11:58:49.568  5463  5463 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:58:49.588  5463  5463 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@131a4951(com.htc.providers.calendar.HtcCalendarProvider@2a2e15b6)
,07-05 11:58:49.598  5440  5440 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,07-05 11:58:49.608  5463  5485 D CalendarProvider2: wait start:true
,07-05 11:58:49.628  5463  5463 D FlexNetS: updateSvcAllowedInSettings:false
,07-05 11:58:49.638  5463  5485 D CalendarProvider2: wait end:false
,07-05 11:58:49.648  5440  5440 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 6060-6074)
07-05 11:58:49.648  5440  5440 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 11:58:49.658   969   989 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5490 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,07-05 11:58:49.668  1675  5489 D WeatherUtility: Weather sync is On
,07-05 11:58:49.668  1675  5489 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
,07-05 11:58:49.678  5440  5440 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {100e2b7}
,07-05 11:58:49.678  5440  5440 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 11:58:49.678  5440  5440 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,07-05 11:58:49.708  5440  5440 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 11:58:49.708  5440  5440 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:58:49.718  5440  5440 E SysUtils: ApplicationContext is null in ApplicationStatus,
,07-05 11:58:49.728   969  1028 I ActivityManager: Waited long enough for: ServiceRecord{1d852e1e u0 com.google.android.gms/.config.ConfigFetchService}
,07-05 11:58:49.748   969  1464 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 11:58:49.848  5490  5520 D WeatherUtility: Weather sync is On
,07-05 11:58:49.878  5440  5440 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 11:58:49.888  5440  5440 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 11:58:49.888  5440  5440 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 11:58:49.888  5440  5440 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-05 11:58:49.888  5440  5440 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:58:49.888  5440  5440 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 11:58:49.888  5440  5440 I Adreno-EGL: Local Branch: 
07-05 11:58:49.888  5440  5440 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 11:58:49.888  5440  5440 I Adreno-EGL: Local Patches: NONE
07-05 11:58:49.888  5440  5440 I Adreno-EGL: Reconstruct Branch: NOTHING
07-05 11:58:49.888  5490  5520 W WeatherRequest: request cur loc, but there is no sys cur
07-05 11:58:49.888  5490  5520 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 11:58:49.898  5490  5520 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,07-05 11:58:49.898  5514  5514 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-05 11:58:49.918   969   989 D PMS     : acquireWL(32c452b4): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5463 10011 null
,07-05 11:58:49.918  1623  1623 I RemoteViews: reapply : com.htc.widget.weatherclock 7 17
,07-05 11:58:49.928  5514  5541 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-05 11:58:49.928  5514  5541 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 11:58:49.928  5463  5542 E SQLiteLog: (284) automatic index on view_events(_id)
,07-05 11:58:49.938   969  1993 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5543 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a,
,07-05 11:58:49.938  5514  5541 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
,07-05 11:58:49.948   969   988 D PMS     : releaseWL(32c452b4): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-05 11:58:49.948  5514  5541 D PowerUsageService: repeat time = 1467713629957,
07-05 11:58:49.948  3698  5368 D MediaProvider: [update][16]#1#
,07-05 11:58:49.978   969  1037 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER,
07-05 11:58:49.978   969  1993 W System.err: java.lang.Throwable: stack dump
07-05 11:58:49.978   969  1993 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-05 11:58:49.978   969  1037 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13f36c95:true
07-05 11:58:49.978   969  1993 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-05 11:58:49.978   969  1993 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-05 11:58:49.978   969  1993 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-05 11:58:49.978  5440  5569 D BluetoothAdapter: 171373395: getState(). Returning 12
,07-05 11:58:50.018  5543  5543 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-05 11:58:50.028  5514  5541 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,07-05 11:58:50.048  5514  5541 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,07-05 11:58:50.048  5514  5541 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 1000, sipper.name = com.android.settings:remote,
07-05 11:58:50.048  5514  5541 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10024, sipper.name = com.google.android.gms.persistent
07-05 11:58:50.048  5514  5541 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 11:58:50.058  5514  5541 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 11:58:50.058  5514  5541 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10041, sipper.name = com.htc.dotmatrixevent
07-05 11:58:50.058  5514  5541 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 0, sipper.name = null
,07-05 11:58:50.068  5440  5440 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:58:50.078  5440  5440 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,07-05 11:58:50.098  5543  5543 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 11:58:50.098  5543  5543 I MultiDex: install
07-05 11:58:50.098  5543  5543 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 11:58:50.098  5440  5440 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-05 11:58:50.108  5440  5440 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:58:50.108  5440  5440 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 11:58:50.128   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
07-05 11:58:50.128   969   969 E WifiTrafficPoller:  packet count Tx=145 Rx=203
07-05 11:58:50.128   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:58:50.128  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:58:50.128  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:58:50.158  5440  5566 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-05 11:58:50.208  5440  5440 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,07-05 11:58:50.248   969  1990 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5588 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-05 11:58:50.248   969  1758 I ActivityManager: Cannot resolve ContentProvider=com.aiqidii.mercury.provider
,07-05 11:58:50.248  5543  5586 E ActivityThread: Failed to find provider info for com.aiqidii.mercury.provider
,07-05 11:58:50.268  5543  5586 E MediaManager: [PPClientWrapper]	 (isPPLogin) has an exception
,07-05 11:58:50.288  5543  5586 E MediaManager: [PPClientWrapper],	PP Error code:1, Error msg:Unknown URI content://com.aiqidii.mercury.provider
,07-05 11:58:50.328  5588  5588 I MusicStore: Database version: 120,
,07-05 11:58:50.348  5440  5440 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@aaa249f, mServedView=org.apache.cordova.engine.SystemWebView{139439ec VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@384ac1b5
07-05 11:58:50.348   969  1464 I InputMethodManagerService: Disable input method client, pid=1623
07-05 11:58:50.348   969  1464 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 11:58:50.348   969  1464 I InputMethodManagerService: Enable input method client, pid=5440
,07-05 11:58:50.348  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-05 11:58:50.358   969  1038 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s215ms
,07-05 11:58:50.358  5543  5587 E SQLiteLog: (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,07-05 11:58:50.368   969  1442 D PMS     : releaseWL(1a387c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-05 11:58:50.388   969  4144 D VoldConnector: SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,07-05 11:58:50.388   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,07-05 11:58:50.388  5588  5588 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,07-05 11:58:50.398  1503  1503 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
07-05 11:58:50.398  1503  1503 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-05 11:58:50.398  1503  1503 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
07-05 11:58:50.398  1503  1503 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-05 11:58:50.428  3698  5368 D MediaProvider: [update][130]#1#
,07-05 11:58:50.428  3698  5368 D MediaScanner:  prescan time: 785ms,
07-05 11:58:50.428  3698  5368 D MediaScanner:     scan time: 942ms
07-05 11:58:50.428  3698  5368 D MediaScanner: postscan time: 7ms
07-05 11:58:50.428  3698  5368 D MediaScanner:    total time: 1734ms
07-05 11:58:50.428  3698  5368 D MediaScanner: -----------------------------------------------------------------
07-05 11:58:50.428  3698  5368 D MediaScanner: firstscan(media) time: 397ms
07-05 11:58:50.428  3698  5368 D MediaScanner: secondscan(non-media) time: 545ms
07-05 11:58:50.428  3698  5368 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
07-05 11:58:50.428  3698  5368 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
07-05 11:58:50.428  3698  5368 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
07-05 11:58:50.428  3698  5368 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1553
,07-05 11:58:50.438   969   988 D VoldConnector: SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
07-05 11:58:50.448   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,07-05 11:58:50.448  5588  5588 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,07-05 11:58:50.448  3698  5368 D MediaProvider: [delete][16]
07-05 11:58:50.448  3698  5368 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
07-05 11:58:50.448   969  1706 D VoldConnector: SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,07-05 11:58:50.448  5514  5541 D PowerUsageService: calcPower(), no data,
07-05 11:58:50.448  5588  5588 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
07-05 11:58:50.448   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
07-05 11:58:50.448  3698  5368 D MediaProvider: [recoverParentNodes] - 0
07-05 11:58:50.448  3698  5368 D MediaProvider: [update][3]
07-05 11:58:50.448  3698  5368 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
,07-05 11:58:50.448  3698  5368 D MediaScannerServiceEx: [updateImage]+
07-05 11:58:50.448   969  1706 I ActivityManager: Killing 4962:com.google.android.apps.photos/u0a197 (adj 15): empty #17
07-05 11:58:50.448   969  1706 D Process : killProcessQuiet, pid=4962
,07-05 11:58:50.448   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:58:50.458  5440  5440 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5440
,07-05 11:58:50.468  3698  5368 D MediaScannerServiceEx: [updateImage]-0
,07-05 11:58:50.568   969  1758 I ActivityManager: Recipient 4962
,07-05 11:58:50.568  5440  5440 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 11:58:50.618  5463  5463 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,07-05 11:58:50.618  5463  5463 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 11:58:50.668   969  1256 V AlarmManager: sending alarm PendingIntent{23d99144: PendingIntentRecord{2c7dc22d com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1467712730679, Int=0
,07-05 11:58:50.668   969  1676 D PMS     : releaseWL(2707d7cb): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
07-05 11:58:50.668  3698  5368 D MediaScannerServiceEx: [1] scan finished
,07-05 11:58:50.668  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/emulated/0,
07-05 11:58:50.668  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-05 11:58:50.668  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/usb
07-05 11:58:50.668  3698  5368 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
,07-05 11:58:50.668  3698  5368 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
07-05 11:58:50.668  3698  5368 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,07-05 11:58:50.678  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,07-05 11:58:50.678  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 +
07-05 11:58:50.678   969  1276 I ActivityManager: Killing 5018:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
07-05 11:58:50.678  1623  1836 I Prism.WidgetManager: onLoadItems() +
07-05 11:58:50.678   969  1276 D Process : killProcessQuiet, pid=5018
07-05 11:58:50.678   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:58:50.688  3698  5368 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
07-05 11:58:50.688  3698  5368 D MediaProvider: [update][4]#1#
07-05 11:58:50.688  5440  5440 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 11:58:50.718  3698  5368 D MediaProvider: [update][27]#0#,
07-05 11:58:50.718  3698  5368 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,07-05 11:58:50.848   969  1676 I ActivityManager: Recipient 5018,
,07-05 11:58:50.898  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
,07-05 11:58:50.898  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-05 11:58:50.898  3698  5368 D MediaProviderUtils: calcVolumeId: /storage/usb
07-05 11:58:50.898  3698  5368 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
07-05 11:58:50.898  3698  5368 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
07-05 11:58:50.908  3698  5368 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,07-05 11:58:50.918  3698  5368 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted
,07-05 11:58:50.918  3698  5368 D MediaProvider: [update][11]#1#
,07-05 11:58:50.918   969  1993 I ActivityManager: Killing 5075:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
07-05 11:58:50.928   969  1993 D Process : killProcessQuiet, pid=5075
07-05 11:58:50.928   969  1993 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:50.928  5588  5588 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 11:58:50.928  5588  5588 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:58:50.938  5440  5618 D jxcore_app_log: JniHelper::setJavaVM(0xab94e7b8), pthread_self() = -1396376392
,07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 11:58:50.948  5440  5618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc782ee added. We now have 1 listener(s)
,07-05 11:58:50.958  3698  5368 D MediaProvider: [update][35]#0#
,07-05 11:58:50.958  3698  5368 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,07-05 11:58:51.008  1623  1836 E Prism.WidgetManager: The same lists. No need to update. skip it.,
07-05 11:58:51.008  1623  1836 I Prism.WidgetManager: onLoadItems() -
07-05 11:58:51.008  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 -
,07-05 11:58:51.028   969  1981 I ActivityManager: Recipient 5075,
,07-05 11:58:51.028   969  2390 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-05 11:58:51.038  5440  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
07-05 11:58:51.038   969  1256 V AlarmManager: sending alarm PendingIntent{11215429: PendingIntentRecord{338b83ae android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=67452, Int=0
,07-05 11:58:51.038  5440  5618 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
,07-05 11:58:51.048  5440  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 11:58:51.048  5440  5618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 11:58:51.048  5440  5618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17708225 added. We now have 1 listener(s)
07-05 11:58:51.048  5440  5618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 11:58:51.058   969   969 E WifiTrafficPoller: ADD_CLIENT: 8
07-05 11:58:51.058   969  1268 D WifiService: New client listening to asynchronous messages
,07-05 11:58:51.058  5440  5618 D BluetoothAdapter: 171373395: getState(). Returning 12
,07-05 11:58:51.058  5440  5618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 11:58:51.058  5440  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 11:58:51.058  5440  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 11:58:51.058  5440  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 11:58:51.058  5440  5618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-05 11:58:51.058  5588  5588 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-05 11:58:51.068  5440  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 11:58:51.068   969  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 11:58:51.068  5440  5618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-05 11:58:51.068   969  4144 I ActivityManager: Killing 5102:com.htc.mobiledata/u0a46 (adj 15): empty #17,
07-05 11:58:51.068   969  4144 D Process : killProcessQuiet, pid=5102
07-05 11:58:51.068   969  4144 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:51.078  5440  5618 D BluetoothAdapter: 171373395: getState(). Returning 12
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 11:58:51.078  5440  5618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 11:58:51.078  5440  5618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 11:58:51.078  5440  5618 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 11:58:51.078  5440  5618 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 11:58:51.078  5440  5440 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 11:58:51.088  5440  5440 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 11:58:51.098  5440  5440 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 11:58:51.108  5588  5588 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
07-05 11:58:51.108  5588  5588 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f7bd70a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 11:58:51.108  5588  5588 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 11:58:51.108  5588  5588 D AndroidMusic: GMSCore installation verified
,07-05 11:58:51.128   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:58:51.128   969   969 E WifiTrafficPoller:  packet count Tx=145 Rx=203
07-05 11:58:51.138  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:58:51.128   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:58:51.138  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:58:51.138   969  1681 I ActivityManager: Recipient 5102
,07-05 11:58:51.178  5588  5588 I ConfigStore: Config Database version: 1
,07-05 11:58:51.188   969  1050 D PMS     : releaseHCC(1ee51a54): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-05 11:58:51.188   969  1050 D PMS     : releaseHCC(2689fdfd): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-05 11:58:51.228   969  1758 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5588, uid=10159, userID:0,
,07-05 11:58:51.238   969   988 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
07-05 11:58:51.238   969   988 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:58:51.238   969   988 D WifiDisplayAdapter:     GroupId: 
07-05 11:58:51.238   969   988 D WifiDisplayAdapter:     Passphrase: 
07-05 11:58:51.238   969   988 D WifiDisplayAdapter:     SessionId: 0
07-05 11:58:51.238   969   988 D WifiDisplayAdapter:     IP Address: }
,07-05 11:58:51.248   969  2390 D MediaRouterService: Client com.google.android.music (pid 5588): Registered,
,07-05 11:58:51.248   969  1276 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:58:51.248   969  1276 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:58:51.248   969  1276 D WifiDisplayAdapter:     GroupId: 
07-05 11:58:51.248   969  1276 D WifiDisplayAdapter:     Passphrase: 
07-05 11:58:51.248   969  1276 D WifiDisplayAdapter:     SessionId: 0
07-05 11:58:51.248   969  1276 D WifiDisplayAdapter:     IP Address: }
,07-05 11:58:51.258  5588  5588 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 11:58:51.268  5588  5588 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 11:58:51.268  1572  1572 D TelephonyReceiver: bind: true
,07-05 11:58:51.298   969  4144 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5638 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,07-05 11:58:51.318   969   989 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5656 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-05 11:58:51.358  5588  5588 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true,
,07-05 11:58:51.378   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5588, uid=10159, userID:0
,07-05 11:58:51.388  5638  5638 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,07-05 11:58:51.388  5638  5638 D MessageFrequencyProvider: onCreate,
07-05 11:58:51.398  5638  5638 V GetPrviateResource: GetPrviateResource
07-05 11:58:51.398  5588  5588 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-05 11:58:51.398  5638  5638 V GetPrviateResource: GetPrviateResource
07-05 11:58:51.398  5638  5674 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count
07-05 11:58:51.408  5588  5588 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 11:58:51.408  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:51.408  5638  5674 E SQLiteLog: (14) cannot open file at line 30058 of [9491ba7d73]
07-05 11:58:51.408  5638  5674 E SQLiteLog: (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
07-05 11:58:51.408  5638  5638 D MessageCustFlag: sense_version=6.0,
,07-05 11:58:51.418  5638  5674 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
07-05 11:58:51.418  5638  5674 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
,07-05 11:58:51.418  5638  5674 E SQLiteDatabase: Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
07-05 11:58:51.418  5638  5674 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
07-05 11:58:51.418  5638  5674 W System.err: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database,
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
07-05 11:58:51.418  5638  5674 W System.err: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
,07-05 11:58:51.418  5638  5674 W System.err: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-05 11:58:51.418  5638  5674 W System.err: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
,07-05 11:58:51.418  5638  5674 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-05 11:58:51.418  5638  5638 D BTAccessoryUtil: createReceiver
,07-05 11:58:51.428  5656  5686 I DFPI.ApkInstallService: onHandleIntent
,07-05 11:58:51.428  5656  5686 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:58:51.428  5656  5686 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:58:51.438  5656  5686 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:51.448   969  1993 I ActivityManager: Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5687 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,07-05 11:58:51.458  1572  1572 D TelephonyReceiver: switchBindHtcMsgCursor: null
,07-05 11:58:51.458  5638  5638 D BTAccessoryUtil: registerReceiver return intent = null,
07-05 11:58:51.458  5638  5638 D MessageCustFlag: sku_id=118
,07-05 11:58:51.468   969  1464 I ActivityManager: Killing 5140:com.android.chrome/u0a96 (adj 15): empty #17
07-05 11:58:51.468   969  1464 D Process : killProcessQuiet, pid=5140
07-05 11:58:51.468   969  1464 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:58:51.468  5638  5638 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
07-05 11:58:51.468  5638  5638 W SystemReader: Cannot find qct_8960_interface, use default value instead
,07-05 11:58:51.528   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
,07-05 11:58:51.528   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:58:51.528   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=14.9, 0.0, 0.0  rx=15.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1166083695] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 11:58:51.528   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:58:51.528   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=14.9, 0.0, 0.0  rx=15.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166083693] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 11:58:51.528   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:58:51.528   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,07-05 11:58:51.528  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:58:51.538  1675  1849 D AutoSetting: service - mRequestRunnable: screen on delay 10s, request NLP now
,07-05 11:58:51.538  1675  1849 D AutoSetting: Util - check NLP state, Allowned:false, Enabled:false
,07-05 11:58:51.538  1675  1849 D AutoSetting: service - requestNLP() NetworkLocationProvider not enabled
07-05 11:58:51.538  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0],
,07-05 11:58:51.538   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:58:51.548   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:58:51.548   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
07-05 11:58:51.548   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.44 txretriesrate=0.00 rxrate=8.21 userTriggerdPenalty0
07-05 11:58:51.548   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:58:51.548   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:58:51.548   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-05 11:58:51.588   969  1981 I ActivityManager: Recipient 5140
,07-05 11:58:51.608  5440  5634 W jxcore-log: Initializing JXcore engine
,07-05 11:58:51.608  5440  5634 W jxcore-log: JXcore engine is ready
,07-05 11:58:51.668  5440  5634 W jxcore-log: Starting JXcore engine
,07-05 11:58:51.708   969  1464 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5711 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-05 11:58:51.708   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:51.718   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
,07-05 11:58:51.718  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3,
07-05 11:58:51.718  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:58:51.768   969  1981 D Process : killProcessQuiet, pid=4190
,07-05 11:58:51.768   969  1981 I ActivityManager: Killing 4190:com.android.defcontainer/u0a15 (adj 15): empty #17
07-05 11:58:51.768   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:51.868   969  1681 I art     : Explicit concurrent mark sweep GC freed 16948(920KB) AllocSpace objects, 2(272KB) LOS objects, 33% free, 16MB/24MB, paused 1.927ms total 146.542ms
,07-05 11:58:51.938   969  2390 I ActivityManager: Recipient 4190
,07-05 11:58:51.938   969  1267 E WifiStateMachine: handleMessage: E msg.what=131165
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: ConnectedState,
07-05 11:58:51.938   969  1267 E WifiStateMachine:  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:51.938   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:58:51.938   969  1267 E WifiStateMachine:  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: DriverStartedState
07-05 11:58:51.938   969  1267 E WifiStateMachine:  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
07-05 11:58:51.938   969  1267 E WifiStateMachine:  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-05 11:58:51.938   969  1267 E WifiStateMachine: processMsg: DefaultState
07-05 11:58:51.938   969  1267 E WifiStateMachine:  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-05 11:58:51.938   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:51.988   969   989 I ActivityManager: Killing 5165:com.google.android.apps.plus/u0a167 (adj 15): empty #17
07-05 11:58:51.988   969   989 D Process : killProcessQuiet, pid=5165,
07-05 11:58:51.988   969   989 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 ,
,07-05 11:58:52.128   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:58:52.138   969   969 E WifiTrafficPoller:  packet count Tx=145 Rx=203
,07-05 11:58:52.138   969  1276 I ActivityManager: Recipient 5165
,07-05 11:58:52.258   969   989 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5734 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,07-05 11:58:52.268  5687  5687 I EASAppSvc: [ NA ]onCreate
,07-05 11:58:52.288  5687  5756 I VersionUtil: [ NA ]setIsFOTAing: true
,07-05 11:58:52.298  5687  5756 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100,
07-05 11:58:52.298  5687  5756 I VersionUtil: [ NA ]setIsFOTAing: false
,07-05 11:58:52.308   969  1028 W BroadcastQueue: Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{265bad9c u0 ReceiverList{4bd590f 5711 com.htc.musicenhancer/10049/u0 remote:39c38e6e}},
,07-05 11:58:52.318  5687  5756 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 5756
,07-05 11:58:52.328   969   988 D VoldConnector: SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
07-05 11:58:52.328   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,07-05 11:58:52.328  5711  5758 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,07-05 11:58:52.328  5380  5760 D ORMLib  : put()
,07-05 11:58:52.338  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,07-05 11:58:52.338  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:58:52.348  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:52.348  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:52.348  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,07-05 11:58:52.358  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.368  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.368  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.368  1572  1572 D TelephonyReceiver: bind: false
07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.368  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-05 11:58:52.368  1572  1572 D TelephonyReceiver: switchBindHtcMsgCursor: null
,07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.368  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:52.368  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:52.368  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:52.368  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,07-05 11:58:52.378  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.378  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.378  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:52.378  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:52.378  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:52.378  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.388  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.388  5656  5766 I DFPI.ApkInstallService: onHandleIntent,
07-05 11:58:52.388  5656  5766 I DFPI.ApkInstallService: Media Scan Finished Case 
07-05 11:58:52.388  5656  5766 D DFPI.ApkInstallService: check CID = HTC__102
,07-05 11:58:52.388  5656  5766 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:52.398  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.398  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.398  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.398  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
,07-05 11:58:52.398  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-05 11:58:52.398   969  1981 I ActivityManager: Killing 5201:com.htc.calendar/u0a10 (adj 15): empty #17
07-05 11:58:52.398  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.398   969  1981 D Process : killProcessQuiet, pid=5201
07-05 11:58:52.398  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:52.398   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:52.468   969  1442 I ActivityManager: Recipient 5201,
,07-05 11:58:52.518  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-05 11:58:52.528   969  1268 D WifiService: New client listening to asynchronous messages
,07-05 11:58:52.528   969   969 E WifiTrafficPoller: ADD_CLIENT: 9
07-05 11:58:52.528  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-05 11:58:52.528  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.528  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-05 11:58:52.528  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.528  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.548  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.548  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.548  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.548  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.548  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.548  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:52.548  5687  5687 I EASAppSvc: [ NA ]onDestroy
,07-05 11:58:52.548  5687  5756 I EASAppSvc: [ NA ]> uninitEASService
,07-05 11:58:52.558  5687  5687 I EASAppSvc: [ NA ]onCreate,
07-05 11:58:52.558  5687  5756 I EASRequestController: [ NA ]release
07-05 11:58:52.558  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.558  5687  5771 I VersionUtil: [ NA ]setIsFOTAing: true
,07-05 11:58:52.568  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.578  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.578  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.578  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:52.578  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.578  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30,
,07-05 11:58:52.578  5687  5771 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100
07-05 11:58:52.578  5687  5771 I VersionUtil: [ NA ]setIsFOTAing: false
07-05 11:58:52.578  5656  5775 I DFPI.ApkInstallService: onHandleIntent
07-05 11:58:52.578  5656  5775 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:58:52.578  5656  5775 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:58:52.578  5656  5775 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:52.588  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:52.598  5687  5756 D EASPublicBinder: [ NA ]release
07-05 11:58:52.598  5687  5756 D TaskBinder: [ NA ]release
07-05 11:58:52.598  5687  5756 D TaskBinder: [ NA ]release
07-05 11:58:52.598  5687  5756 I EASAppSvc: [ NA ]< uninitEASService
,07-05 11:58:52.598  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:52.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.598  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:52.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:58:52.598  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:58:52.608  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-05 11:58:52.608  5380  5776 D ORMLib  : put()
,07-05 11:58:52.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.618  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:58:52.628  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:58:52.638  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:52.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104,
07-05 11:58:52.638  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.638  5687  5687 I EASAppSvc: [ NA ]onDestroy
07-05 11:58:52.638  5687  5771 I EASAppSvc: [ NA ]> uninitEASService
,07-05 11:58:52.648  5656  5781 I DFPI.ApkInstallService: onHandleIntent
,07-05 11:58:52.648  5656  5781 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:58:52.648  5656  5781 D DFPI.ApkInstallService: check CID = HTC__102
,07-05 11:58:52.648  5656  5781 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:52.668  5687  5771 I EASRequestController: [ NA ]release
,07-05 11:58:52.668   969   988 I ActivityManager: Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5782 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,07-05 11:58:52.668  5687  5771 D EASPublicBinder: [ NA ]release
,07-05 11:58:52.668  5687  5771 D TaskBinder: [ NA ]release
07-05 11:58:52.668  5687  5771 D TaskBinder: [ NA ]release
07-05 11:58:52.668  5687  5771 I EASAppSvc: [ NA ]< uninitEASService
,07-05 11:58:52.668  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
07-05 11:58:52.678  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:52.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:58:52.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:52.678  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:52.678  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:58:52.688  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.688   410   410 I art     : Explicit concurrent mark sweep GC freed 8652(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 237us total 29.222ms
,07-05 11:58:52.688  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.688  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.698  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:52.698  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:52.698  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:52.698  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:52.698  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
07-05 11:58:52.698  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.698  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.698  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.698  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.698  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma),
07-05 11:58:52.698  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.698  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-05 11:58:52.708  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.708  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.708  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.708  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:52.708  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:58:52.708  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:52.708  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.708  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:52.708   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 227us total 22.067ms
07-05 11:58:52.718  5656  5810 I DFPI.ApkInstallService: onHandleIntent
07-05 11:58:52.718  5656  5810 I DFPI.ApkInstallService: Media Scan Finished Case 
07-05 11:58:52.718  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.718  5656  5810 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:58:52.718  5656  5810 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-05 11:58:52.718  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.718  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.718  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.718  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.718  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.728  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:58:52.728   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 140us total 16.509ms
,07-05 11:58:52.728  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:58:52.738  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.748  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-05 11:58:52.748  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.748  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.748  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.748  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.748  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.758  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.758  5656  5813 I DFPI.ApkInstallService: onHandleIntent
07-05 11:58:52.758  5656  5813 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:58:52.758  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.758  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.758  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.758  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.758  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-05 11:58:52.758  5656  5813 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:58:52.758  5656  5813 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:52.768  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
07-05 11:58:52.768  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
07-05 11:58:52.778  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-05 11:58:52.778  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-05 11:58:52.778  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.778  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.778  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:52.778  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.778  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:58:52.778  5380  5812 D ORMLib  : put()
,07-05 11:58:52.788  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:52.798  5656  5656 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.798  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.798  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.798  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:52.798  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:58:52.808  5656  5814 I DFPI.ApkInstallService: onHandleIntent
,07-05 11:58:52.808  5656  5814 I DFPI.ApkInstallService: Media Scan Finished Case 
07-05 11:58:52.808  5656  5814 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:58:52.808  5656  5814 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:58:52.808  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.808  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:58:52.818  5734  5734 I SoundPicker: SoundPickerReceiver [onReceive] startService,
07-05 11:58:52.818  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.818  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.818  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.818  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-05 11:58:52.818  3202  3264 I HtcModeClient: handler message = 4011
07-05 11:58:52.818  3202  3264 E HtcModeClient: Check connection and retry 6 times.
,07-05 11:58:52.818  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.828  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
07-05 11:58:52.828  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.828  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:52.828  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-05 11:58:52.828  1945  5815 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 11:58:52.838  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:58:52.838  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
07-05 11:58:52.838  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:52.838  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.838  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:52.838  1945  1945 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 11:58:52.848  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.848   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:58:52.848  2228  2228 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
07-05 11:58:52.848  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.848  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.848  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:52.848   969  5816 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=126 rxSum=122} preTxRxSum={txSum=126 rxSum=122}
07-05 11:58:52.848   969  5816 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:58:52.848   969  5816 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
07-05 11:58:52.848  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:52.848  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:52.848  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:58:52.848  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:52.848  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-05 11:58:52.858  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.858  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.858  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.858  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.858  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.858  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
,07-05 11:58:52.858  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:52.858  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:52.858  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.868  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.868  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.868  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.868  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.868  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.868  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.878  3698  3720 I art     : Explicit concurrent mark sweep GC freed 57906(4MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1558KB/5MB, paused 565us total 40.367ms
,07-05 11:58:52.878  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.878  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.878  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.878  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.878  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.878  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.888  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.888  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-05 11:58:52.888  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.888  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.888  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.888  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:52.898  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.898   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2228, uid=10024, userID:0
07-05 11:58:52.898  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.898  1842  5819 E MDM     : [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 11:58:52.898  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.898  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:52.898  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.898  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-05 11:58:52.908  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.918  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.918  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:52.918  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:52.918  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-05 11:58:52.918  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-05 11:58:52.918  2228  5820 D LocationInitializer: Restart initialization of location
07-05 11:58:52.918   969  1706 D PMS     : acquireWL(20c4f893): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:52.928  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.928  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.928  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:52.928  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.928  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-05 11:58:52.928   969  2390 D PMS     : releaseWL(20c4f893): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:52.928  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.938  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:52.938  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:58:52.938  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-05 11:58:52.938  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:58:52.938   969  1464 D PMS     : acquireWL(c4cd0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:52.948  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:58:52.948  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,07-05 11:58:52.948  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:52.948  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:52.948  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:52.948   969   989 D PMS     : releaseWL(c4cd0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:52.958  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-05 11:58:52.958  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:52.958  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:52.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,07-05 11:58:52.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.968  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.968  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.968  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.968  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:52.968  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:52.968  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:52.978  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.978  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.978  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.978  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:52.978  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:52.978  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:52.988  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:52.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:52.988  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:52.988  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:52.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:53.018   969  1990 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5826 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,07-05 11:58:53.018  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.018  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-05 11:58:53.018  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.028   969  2390 D PMS     : acquireWL(368ce6da): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.018  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:53.028  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:58:53.028  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:53.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:53.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:53.038  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:53.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-05 11:58:53.038  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.048  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-05 11:58:53.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.048  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:53.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:58:53.068  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:53.068  2228  5825 I art     : Explicit concurrent mark sweep GC freed 16630(1220KB) AllocSpace objects, 17(340KB) LOS objects, 41% free, 5MB/9MB, paused 2.867ms total 76.159ms
,07-05 11:58:53.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-05 11:58:53.078  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:58:53.078  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
07-05 11:58:53.078  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:58:53.138   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 9,
07-05 11:58:53.138  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:58:53.138   969   969 E WifiTrafficPoller:  packet count Tx=145 Rx=204
,07-05 11:58:53.138   969   969 E WifiTrafficPoller: notifying of data activity 1
07-05 11:58:53.138  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:58:53.198   969  1758 I art     : Explicit concurrent mark sweep GC freed 11480(558KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.724ms total 134.089ms
,07-05 11:58:53.218  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:58:53.218  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:58:53.218  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:53.218  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:53.218  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:53.228  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.228  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.228  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.228  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-05 11:58:53.228  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:53.228  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:53.228  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:58:53.228  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,07-05 11:58:53.228  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.228  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
,07-05 11:58:53.228  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:53.228  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-05 11:58:53.228  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma),
07-05 11:58:53.228  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:53.228  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-05 11:58:53.228  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:53.238  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:53.238  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:53.238  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:53.238  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:58:53.238  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:53.238  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:53.238  5826  5826 D PhoneMonitor: Register our PhoneStateListener
,07-05 11:58:53.248  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:53.248  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.248  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.248  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:53.248  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,07-05 11:58:53.248  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:53.258  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:53.268  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:53.268  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.268  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:53.268  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:53.268  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:53.268   969  1681 D Process : killProcessQuiet, pid=5261
07-05 11:58:53.268   969  1681 I ActivityManager: Killing 5261:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,07-05 11:58:53.268   969  1681 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:58:53.278  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
,07-05 11:58:53.288  5826  5826 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-05 11:58:53.288  5826  5826 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-05 11:58:53.408   969   988 I ActivityManager: Recipient 5261
,07-05 11:58:53.468  5638  5638 D Messaging: supportCMAS(SIE)/init? false/true,
07-05 11:58:53.468  5638  5638 D MmsConfig: networkCode: ,
07-05 11:58:53.468  5638  5638 D MessageCustFlag: sku_id=118
,07-05 11:58:53.468  5638  5638 D MmsConfig: SIE smsPri: null,
07-05 11:58:53.478  5638  5638 D MmsConfig: networkCode: 
,07-05 11:58:53.478  5638  5851 D Messaging: mNeedToUpdateDate2 start,
07-05 11:58:53.478  5638  5638 D MmsConfig: packageName: com.htc.vvm.att does not exist
07-05 11:58:53.488  5638  5638 D ReportIndicatorCache: startAsyncQueryReports ---
,07-05 11:58:53.488  5638  5638 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@100e2b7
07-05 11:58:53.488  5638  5683 D MmsAsyncWorkHandler: 
07-05 11:58:53.488  5638  5683 D MmsAsyncWorkHandler: HM tk = 20001
07-05 11:58:53.488  5638  5683 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
07-05 11:58:53.498  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
07-05 11:58:53.498  1572  4141 D MmsSmsV2Provider:  slotId = -1000
07-05 11:58:53.498  1572  4141 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,07-05 11:58:53.498  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.498  5638  5638 D DraftCache: [DraftCache/1] DraftCache.constructor
07-05 11:58:53.498   969  1706 D PMS     : acquireWL(768933d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.498  1945  5853 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 11:58:53.498  5638  5638 D DraftCache: [DraftCache/1] refresh
,07-05 11:58:53.508  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.508  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.508  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-05 11:58:53.508  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:53.508  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-05 11:58:53.508  5638  5638 D MmsConfig: networkCode: 
07-05 11:58:53.508  5638  5854 I Messaging: mccmnc> 
,07-05 11:58:53.518  1572  2192 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
07-05 11:58:53.518  5638  5856 D Messaging: ViewCache CreatePreloadOnlyConversationList
07-05 11:58:53.528  1572  2192 D AccFlag : sku_id=118
,07-05 11:58:53.538  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.538   969  1993 D PMS     : acquireWL(2ced2c83): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:53.538   969  1442 D PMS     : releaseWL(368ce6da): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.538  5638  5683 D DraftCache: [DraftCache/166] rebuildCache
,07-05 11:58:53.538  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.538   969   989 D PMS     : releaseWL(768933d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.538  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.538  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:53.538  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.538  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-05 11:58:53.538  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
07-05 11:58:53.538  1572  4141 D MmsSmsV2Provider:  slotId = -1000
07-05 11:58:53.538  1572  4141 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,07-05 11:58:53.548  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:53.548  5638  5856 D MessageCustFlag: sense_version=6.0
,07-05 11:58:53.548  5638  5856 D Jerry   : start to preload cursor >>>>>>>
,07-05 11:58:53.548  1572  1620 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,07-05 11:58:53.548  1572  1620 D MmsSmsV2Provider:  slotId = -1000
07-05 11:58:53.548  1572  1620 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-05 11:58:53.548  5638  5638 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
07-05 11:58:53.548  5638  5638 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
07-05 11:58:53.548  5638  5638 D PhoneStorageUtil: createReceiver
07-05 11:58:53.558  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:53.558  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:53.558  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,07-05 11:58:53.558  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:58:53.558  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-05 11:58:53.558  5638  5851 D Messaging: mNeedToUpdateDate2: false
,07-05 11:58:53.558  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.568  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.568  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-05 11:58:53.568  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:58:53.568  1572  1638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-05 11:58:53.568  1572  1638 D Jerry   : URI_DRAFT
,07-05 11:58:53.568  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 11:58:53.568  1572  2193 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
07-05 11:58:53.568  1572  2193 V MmsProvider: Update uri=content://mms, match=0
07-05 11:58:53.568  1572  2193 V MmsProvider: selection=st=129 AND m_type!=134
,07-05 11:58:53.578  5638  5858 D Messaging: Reset downloading state: 0
,07-05 11:58:53.578  2228  2228 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
07-05 11:58:53.578  5638  5858 V MmsSystemEventReceiver: TransactionService is going to be woken up.
,07-05 11:58:53.578  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
07-05 11:58:53.578  1572  2193 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
07-05 11:58:53.578  1572  2193 D MmsSmsV2Provider:  slotId = -1000
07-05 11:58:53.578  1572  2193 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
07-05 11:58:53.578  5638  5683 D DraftCache: hasDraft() = false mNeedNotifyChange = true
,07-05 11:58:53.578  5638  5683 D DraftCache: [DraftCache/166] rebuildCache time: 6
07-05 11:58:53.578  5638  5683 D MmsAsyncWorkHandler: 
07-05 11:58:53.578  5638  5683 D MmsAsyncWorkHandler: HM tk = 20002
,07-05 11:58:53.578  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-05 11:58:53.588  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:58:53.588  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:53.588  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-05 11:58:53.588  2228  5859 I CheckinService: Checking schedule, now: 1467712733598 next: 1467712758984
,07-05 11:58:53.588  2228  5859 I CheckinService: active receiver: disabled
,07-05 11:58:53.588   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2228, uid=10024, userID:0
07-05 11:58:53.588  5638  5638 V TransactionService: 1-Creating TransactionService
,07-05 11:58:53.588  5638  5852 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,07-05 11:58:53.588  1572  2193 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
07-05 11:58:53.588  1572  2193 D MmsSmsV2Provider:  slotId = -1000
,07-05 11:58:53.588  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:58:53.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:58:53.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,07-05 11:58:53.598   969   988 D PMS     : releaseWL(2ced2c83): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.598  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:53.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:53.598  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.598  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
07-05 11:58:53.598  1572  4141 D AccFlag : sku_id=118
,07-05 11:58:53.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.598  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.608  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:53.608  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:53.608  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:53.608  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:53.608  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:53.608  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:53.608  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:53.608  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-05 11:58:53.608  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:53.618  5638  5856 D Messaging: ViewCache CreatePreload
07-05 11:58:53.618  5638  5856 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
07-05 11:58:53.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.618  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:53.618  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:53.618  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:53.618  1572  2193 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
07-05 11:58:53.618  1572  2193 D AccFlag : sku_id=118
07-05 11:58:53.618  5638  5638 V TransactionService: onStartCommand: 1
,07-05 11:58:53.618  5638  5638 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-05 11:58:53.618  5638  5860 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-05 11:58:53.618  5638  5860 V TransactionService: Loading previous transactions.
,07-05 11:58:53.618  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.618   969   989 D PMS     : acquireWL(2a98e6c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:53.628  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.628  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.628  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:53.628  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:53.628  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:58:53.628  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:58:53.628  5638  5856 D Cust_MMSMS: _has_set_default_values_2=true,
,07-05 11:58:53.638  5638  5856 D MsgPreferenceUtils: def_index: 0
07-05 11:58:53.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.638  1572  1638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-05 11:58:53.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:53.638  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:53.638  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:53.638  1572  1638 D AccFlag : device_type: 1
07-05 11:58:53.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:53.638  5638  5856 D MsgPreferenceUtils: globalIndex = 1
07-05 11:58:53.638   969  1276 D PMS     : releaseWL(2a98e6c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:53.638  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.638  5638  5860 D TransactionService: Force clearing mTransactionList
07-05 11:58:53.638  5638  5860 D TransactionService: Force set service start id to 1
,07-05 11:58:53.638  5638  5860 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
07-05 11:58:53.638  5638  5860 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-05 11:58:53.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.638  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.648  5638  5860 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
07-05 11:58:53.648  5638  5638 V TransactionService: Destroying TransactionService
,07-05 11:58:53.648  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-05 11:58:53.648  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.648  5638  5856 D MsgPreferenceUtils: phone state: true
07-05 11:58:53.648  5638  5856 D MsgPreferenceUtils: sd state: false
07-05 11:58:53.648  5638  5856 D MsgPreferenceUtils: vIndex = 0
07-05 11:58:53.648  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:58:53.658   969  1464 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=5868 uid=10035 gids={50035, 9997} abi=arm64-v8a
,07-05 11:58:53.668  5638  5860 V TransactionService: 4-Handling incoming message: { when=-23ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,07-05 11:58:53.668  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:53.678  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:58:53.678  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:53.678  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:53.678  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:58:53.718  5588  5770 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-05 11:58:53.718   969  1442 D Process : killProcessQuiet, pid=5290
,07-05 11:58:53.718   969  1442 I ActivityManager: Killing 5290:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
07-05 11:58:53.718  3698  3731 I art     : Explicit concurrent mark sweep GC freed 5063(242KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1503KB/5MB, paused 634us total 29.537ms
07-05 11:58:53.718   969  1442 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:58:53.798   969  4144 I ActivityManager: Recipient 5290
,07-05 11:58:53.828   969   988 D Process : killProcessQuiet, pid=4478
07-05 11:58:53.828   969   988 I ActivityManager: Killing 4478:com.google.android.talk/u0a112 (adj 15): empty #17
07-05 11:58:53.828   969   988 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 ,
,07-05 11:58:53.918   969  1464 I ActivityManager: Recipient 4478
,07-05 11:58:53.948  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,07-05 11:58:53.948  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
07-05 11:58:53.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac,
07-05 11:58:53.958  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:53.958  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:58:53.978   969  1276 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5900 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,07-05 11:58:53.988  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,07-05 11:58:53.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:58:53.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:53.988  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-05 11:58:53.988  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:58:53.998  5734  5762 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:53.998  5734  5762 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:58:53.998  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:58:53.998  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/1,22 type=1
07-05 11:58:53.998  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:54.008  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.018  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.018  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.018  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:58:54.018  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:58:54.018  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:54.018  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:58:54.028  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:58:54.028  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:58:54.028  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:58:54.028  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:58:54.028  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:54.038  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,07-05 11:58:54.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:54.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:58:54.038  5734  5762 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:58:54.038  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:58:54.038  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:58:54.048  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:58:54.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:54.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:58:54.048  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:58:54.048  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:58:54.058  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-05 11:58:54.058  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-05 11:58:54.058  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:58:54.058  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:58:54.058  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:58:54.058  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:58:54.068  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:58:54.068  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:58:54.068  5734  5762 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:58:54.068  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:58:54.078  5734  5762 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:54.078  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:58:54.078  5734  5762 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:58:54.078   969  1993 D Process : killProcessQuiet, pid=5314
07-05 11:58:54.078   969  1993 I ActivityManager: Killing 5314:com.htc.sense.news/u0a74 (adj 15): empty #17
07-05 11:58:54.078   969  1993 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:54.138   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 9
07-05 11:58:54.138  1339  1339 D WIFI_ICON: WifiActivity: 3
,07-05 11:58:54.138   969   969 E WifiTrafficPoller:  packet count Tx=147 Rx=205
07-05 11:58:54.138  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-05 11:58:54.138   969   969 E WifiTrafficPoller: notifying of data activity 3
,07-05 11:58:54.188   969  1758 I ActivityManager: Recipient 5314
,07-05 11:58:54.188   969   988 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 11:58:54.258  5900  5900 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,07-05 11:58:54.258  5900  5925 I Gmail   : getAccountsCursor,
,07-05 11:58:54.268  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:54.288   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5900, uid=10106, userID:0
,07-05 11:58:54.298   969  1442 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 11:58:54.298   969  1758 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 11:58:54.328  5900  5935 E Gmail   : Error finding the version of the Email provider.....,
07-05 11:58:54.328  5900  5935 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 11:58:54.328  5900  5935 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-05 11:58:54.328  5900  5935 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 11:58:54.328  5900  5935 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 11:58:54.448   969  1276 I art     : Explicit concurrent mark sweep GC freed 6761(324KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.466ms total 137.146ms
,07-05 11:58:54.458  5900  5933 I Gmail   : Observing account changes for notifications
,07-05 11:58:54.468  5900  5937 I Gmail   : getAccountsCursor
,07-05 11:58:54.478   969  2390 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5939 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-05 11:58:54.478   969  1681 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-05 11:58:54.478   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5900, uid=10106, userID:0
,07-05 11:58:54.478   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5900, uid=10106, userID:0
07-05 11:58:54.478   969  1028 I ActivityManager: Waited long enough for: ServiceRecord{3ea0023f u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,07-05 11:58:54.478  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 11:58:54.488   969  1676 D Process : killProcessQuiet, pid=5331
07-05 11:58:54.488   969  1676 I ActivityManager: Killing 5331:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
07-05 11:58:54.488   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 ,
,07-05 11:58:54.548   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155,
07-05 11:58:54.548   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:58:54.548   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=7.4, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:2842] from screen [on:0 period:-1166080668] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:58:54.548   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:54.548   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=7.4, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166080667] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:58:54.548   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:58:54.548   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
07-05 11:58:54.558  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:58:54.568   969  1706 I ActivityManager: Recipient 5331
07-05 11:58:54.568   969  1268 D WifiService: Client connection lost with reason: 4
,07-05 11:58:54.568  1432  1432 I wpa_supplicant: environment dirty rate=0 [2][0][0]
,07-05 11:58:54.568   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:58:54.568   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:58:54.568   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:58:54.568   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.72 txretriesrate=0.00 rxrate=5.11 userTriggerdPenalty0
,07-05 11:58:54.568   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:58:54.568   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:58:54.568   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
,07-05 11:58:54.598   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:54.608   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
,07-05 11:58:54.608  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:58:54.608  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,07-05 11:58:54.618  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:58:54.628  5939  5939 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-05 11:58:54.668  5900  5962 E SQLiteLog: (283) recovered 1941 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,07-05 11:58:54.748  5900  5963 I Gmail   : notifyAccountChanged,
,07-05 11:58:54.748  5900  5963 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,07-05 11:58:54.748  5900  5966 I Gmail   : getAccountsCursor
,07-05 11:58:54.758  5900  5963 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,07-05 11:58:54.758  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:54.768  5900  5963 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 11:58:54.768  5900  5963 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 11:58:54.768   969  1981 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:58:54.768   969  1990 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2228, uid=10024, userID:0
07-05 11:58:54.768  2228  4447 I CheckinService: Done disabling old GoogleServicesFramework version
07-05 11:58:54.768   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2228, uid=10024, userID:0,
,07-05 11:58:54.828  5939  5971 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-05 11:58:54.828  5939  5971 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 11:58:54.838  5638  5666 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
,07-05 11:58:54.838  5900  5966 I Gmail   : master sync=false, engine sync=true,
,07-05 11:58:54.868  5638  5674 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile,
,07-05 11:58:54.868   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5939, uid=10112, userID:0
,07-05 11:58:54.868  5939  5971 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml,
,07-05 11:58:54.868  5939  5971 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 11:58:54.888  5939  5971 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc ,
07-05 11:58:54.888  5939  5971 I Babel_SMS: MmsConfig.loadFromResources,
,07-05 11:58:54.888  5939  5971 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 11:58:54.888  5939  5971 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,07-05 11:58:54.888  5900  5975 I Gmail   : getAccountsCursor
,07-05 11:58:54.898  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:58:54.908  5900  5975 I Gmail   : master sync=false, engine sync=true,
,07-05 11:58:54.938  5939  5939 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,07-05 11:58:54.948  5939  5939 I Babel_Crash: startup - clean
07-05 11:58:54.948  1945  1945 I art     : Explicit concurrent mark sweep GC freed 10238(518KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 772us total 49.061ms,
,07-05 11:58:54.958  5939  5976 I Babel   : deleted: false for 0
,07-05 11:58:54.988   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5939, uid=10112, userID:0,
,07-05 11:58:54.998   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5939, uid=10112, userID:0
,07-05 11:58:54.998   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5939, uid=10112, userID:0
,07-05 11:58:54.998   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5939, uid=10112, userID:0
,07-05 11:58:54.998   969  1981 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5939, uid=10112, userID:0
,07-05 11:58:54.998   969  1706 D PMS     : acquireWL(1553676d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5939 10112 null
,07-05 11:58:55.018   969   969 E WifiStateMachine: WiFiStateMachine SCAN ALARM,
07-05 11:58:55.018   969   969 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:58:55.018   969   969 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:58:55.018   969   969 D WifiDisplayAdapter:     GroupId: 
07-05 11:58:55.018   969   969 D WifiDisplayAdapter:     Passphrase: 
07-05 11:58:55.018   969   969 D WifiDisplayAdapter:     SessionId: 0
07-05 11:58:55.018   969   969 D WifiDisplayAdapter:     IP Address: }
07-05 11:58:55.018   969  1267 E WifiStateMachine: handleMessage: E msg.what=131143
07-05 11:58:55.018   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:58:55.018   969  1267 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:76 rssi=-56 f=2447 sc=60 link=150 tx=4.7, 0.0, 0.0  rx=5.1 list=2447 [on:0 tx:0 rx:0 period:415] from screen [on:0 period:-1166080203]
07-05 11:58:55.018   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:55.018   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):3 dur:76 rssi=-56 f=2447 sc=60 link=150 tx=4.7, 0.0, 0.0  rx=5.1 list=2447 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166080202]
07-05 11:58:55.018   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.72 rxSuccessRate=5.11 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-56
07-05 11:58:55.018   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1467712735030 interval=40000 maxinterval=300000
07-05 11:58:55.018   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1467712735030 interval=40000 maxinterval=300000
07-05 11:58:55.018   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
07-05 11:58:55.018   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =60000
07-05 11:58:55.018   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-05 11:58:55.018  1432  1432 I wpa_supplicant: wpa_supplicant_scan enter
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Request Type
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Config Methods (4288)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * UUID-E
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Primary Device Type
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * RF Bands (3)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Association State
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Configuration Error (0)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Device Password ID (0)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Manufacturer
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Model Name
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Model Number
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Device Name
07-05 11:58:55.018  1432  1432 D wpa_supplicant: WPS:  * Version2 (0x20)
07-05 11:58:55.018  1432  1432 D wpa_supplicant: P2P: * P2P IE header
07-05 11:58:55.018  1432  1432 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-05 11:58:55.018  1432  1432 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55baf59aa0
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55baf59aa0 after 0.000042 second wait
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: nl80211: scan request
07-05 11:58:55.018  1432  1432 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 11:58:55.018  1432  1432 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
07-05 11:58:55.018  1432  1432 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000096 seconds
07-05 11:58:55.018  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-05 11:5,8:55.018   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-05 11:58:55.018   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-05 11:58:55.018   969  1788 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-05 11:58:55.018   969  1788 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-05 11:58:55.018   969  1267 E WifiStateMachine: [1,467,712,735,032 ms] noteScanstart no scan source
07-05 11:58:55.018   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:58:55.048  5939  5939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.058   969  1981 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5980 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,07-05 11:58:55.088  5939  5939 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,07-05 11:58:55.098  5939  5939 W Utils   : could not parse size range '64x64-1920X1080'
,07-05 11:58:55.098  5980  5980 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:58:55.098  5939  5939 W AudioCapabilities: Unsupported mime audio/qcelp,
,07-05 11:58:55.098  5939  5939 W AudioCapabilities: Unsupported mime audio/x-ms-wma,
,07-05 11:58:55.098  5939  5939 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 11:58:55.098  5939  5939 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,07-05 11:58:55.118  5980  5980 D CalendarApplication: onCreate,
,07-05 11:58:55.118  5980  5980 D ProviderChangeReceiver: ---------------------------------------------------,
07-05 11:58:55.118  5980  5980 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-05 11:58:55.118  5900  5978 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false,
,07-05 11:58:55.118  5980  6005 D HtcAlertService: start to updateAlertNotification!,
,07-05 11:58:55.138   969  1681 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6006 uid=10197 gids={50197, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 11:58:55.138   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:58:55.138  1339  1339 D WIFI_ICON: WifiActivity: 0
,07-05 11:58:55.138   969   969 E WifiTrafficPoller:  packet count Tx=147 Rx=205
07-05 11:58:55.138   969   969 E WifiTrafficPoller: notifying of data activity 0
,07-05 11:58:55.148  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
,07-05 11:58:55.148  5939  5939 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 11:58:55.158  5939  5939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.158  5939  5939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 11:58:55.158  5980  6005 D HtcAlertService: No fired or scheduled alerts
,07-05 11:58:55.158  5980  6005 D HtcAlertUtils: -- cancelReminderNotification --
,07-05 11:58:55.158  5980  6005 D HtcAlertUtils: broadcastExistReminder!
,07-05 11:58:55.158  5939  5939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.168  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 11:58:55.168  5939  5939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.178  5900  5978 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,07-05 11:58:55.178   969  1681 I ActivityManager: Killing 4263:com.android.settings/1000 (adj 15): empty #17
,07-05 11:58:55.188   969  1681 D Process : killProcessQuiet, pid=4263
07-05 11:58:55.188   969  1681 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:55.298   969  4144 I ActivityManager: Recipient 4263
,07-05 11:58:55.398  5939  5939 I vclib   : onServiceConnected,
,07-05 11:58:55.408  5939  5939 W Babel   : Attempted to change video mute state without an active call.
,07-05 11:58:55.428  5939  5939 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-05 11:58:55.428  5939  5939 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:58:55.488   969   988 D PMS     : acquireWL(1c67bf1c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 6006 10197 null,
,07-05 11:58:55.498  1945  6032 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 11:58:55.498  1945  1945 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,07-05 11:58:55.508  2228  2228 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,07-05 11:58:55.518   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2228, uid=10024, userID:0,
,07-05 11:58:55.528  1842  6034 E MDM     : [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:58:55.538  2228  6035 D LocationInitializer: Restart initialization of location,
,07-05 11:58:55.538   969  1676 D PMS     : releaseWL(1c67bf1c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 null,
,07-05 11:58:55.548   969  4144 I ActivityManager: Killing 5419:com.htc.backupreset/1000 (adj 15): empty #17
07-05 11:58:55.548   969  4144 D Process : killProcessQuiet, pid=5419
07-05 11:58:55.548   969  4144 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:55.568  5939  5939 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,07-05 11:58:55.618   969  1981 I ActivityManager: Recipient 5419
,07-05 11:58:55.688  5939  5939 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 11:58:55.688  5939  5939 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:58:55.748   969  4144 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6039 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,07-05 11:58:55.768  1572  4141 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.,
,07-05 11:58:55.778  5939  6027 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
07-05 11:58:55.778  5939  6027 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.778  5939  6027 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:58:55.838   969   988 D PMS     : releaseWL(1553676d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,07-05 11:58:55.918   969  1681 D LocationManagerService: getProviders()=[passive],
,07-05 11:58:55.958   969  1464 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6069 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,07-05 11:58:55.968   969  1990 D Process : killProcessQuiet, pid=5490
,07-05 11:58:55.968   969  1990 I ActivityManager: Killing 5490:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,07-05 11:58:55.968   969  1990 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:58:56.068   969  1993 I ActivityManager: Recipient 5490
,07-05 11:58:56.078   969  1676 D Process : killProcessQuiet, pid=5514
07-05 11:58:56.078   969  1676 I ActivityManager: Killing 5514:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,07-05 11:58:56.088   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.attachApplicationLocked:6655 
,07-05 11:58:56.138   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:58:56.148   969   969 E WifiTrafficPoller:  packet count Tx=147 Rx=205
,07-05 11:58:56.158   969  2390 I ActivityManager: Recipient 5514
,07-05 11:58:56.218  1675  6091 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-05 11:58:56.218  1675  6091 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
07-05 11:58:56.218  1623  1623 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED,
07-05 11:58:56.218  1623  1623 I ContextualWidget: package com.google.android.gms changed
,07-05 11:58:56.228  1623  1875 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
,07-05 11:58:56.238  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 11:58:56.238  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-05 11:58:56.238  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0,
07-05 11:58:56.238  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 11:58:56.238  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
,07-05 11:58:56.238  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-05 11:58:56.238  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:58:56.238  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 11:58:56.238  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:58:56.258  1945  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
07-05 11:58:56.258  1945  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:56.258  1945  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:58:56.258  1945  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:58:56.258   969  2390 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 11:58:56.268  1945  2121 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:56.298  5939  6062 E Babel   : UserRecoverableAuthException.,
,07-05 11:58:56.298  5939  6062 E Babel   : eei: BadAuthentication,
07-05 11:58:56.298  5939  6062 E Babel   : 	at eeg.a(Unknown Source)
07-05 11:58:56.298  5939  6062 E Babel   : 	at eeg.a(Unknown Source)
07-05 11:58:56.298  5939  6062 E Babel   : 	at eeg.a(Unknown Source)
07-05 11:58:56.298  5939  6062 E Babel   : 	at g.a(Unknown Source)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cae.a(SourceFile:3089)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cae.a(SourceFile:1131)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cws.a(SourceFile:4333)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cws.a(SourceFile:1419)
07-05 11:58:56.298  5939  6062 E Babel   : 	at crl.a(SourceFile:492)
07-05 11:58:56.298  5939  6062 E Babel   : 	at crl.a(SourceFile:1468)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cqu.a(SourceFile:4416)
07-05 11:58:56.298  5939  6062 E Babel   : ,	at cas.b(SourceFile:106)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cap.d(SourceFile:335)
07-05 11:58:56.298  5939  6062 E Babel   : 	at caq.run(SourceFile:81)
07-05 11:58:56.298  5939  6062 E Babel   : Error getting auth token
07-05 11:58:56.298  5939  6062 E Babel   : dvm
07-05 11:58:56.298  5939  6062 E Babel   : 	at g.a(Unknown Source)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cae.a(SourceFile:3089)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cae.a(SourceFile:1131)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cws.a(SourceFile:4333),
07-05 11:58:56.298  5939  6062 E Babel   : 	at cws.a(SourceFile:1419)
07-05 11:58:56.298  5939  6062 E Babel   : 	at crl.a(SourceFile:492)
07-05 11:58:56.298  5939  6062 E Babel   : 	at crl.a(SourceFile:1468)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cqu.a(SourceFile:4416)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cas.b(SourceFile:106)
07-05 11:58:56.298  5939  6062 E Babel   : 	at cap.d(SourceFile:335)
07-05 11:58:56.298  5939  6062 E Babel   : 	at caq.run(SourceFile:81)
,07-05 11:58:56.418  5939  6062 E Babel   : Account registration failed 1-Redacted-21
07-05 11:58:56.418  5939  6062 E Babel   : cyp: null -- null
07-05 11:58:56.418  5939  6062 E Babel   : 	at cae.a(SourceFile:3121)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cae.a(SourceFile:1131)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cws.a(SourceFile:4333)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cws.a(SourceFile:1419)
07-05 11:58:56.418  5939  6062 E Babel   : 	at crl.a(SourceFile:492)
07-05 11:58:56.418  5939  6062 E Babel   : 	at crl.a(SourceFile:1468)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cqu.a(SourceFile:4416)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cas.b(SourceFile:106)
07-05 11:58:56.418  5939  6062 E Babel   : 	at cap.d(SourceFile:335)
07-05 11:58:56.418  5939  6062 E Babel   : 	at caq.run(SourceFile:81)
,07-05 11:58:56.438  5939  6116 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
07-05 11:58:56.438  5939  6062 I art     : Note: end time exceeds epoch: 
07-05 11:58:56.438  5939  6116 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 11:58:56.438  5939  6116 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-05 11:58:56.438  5939  6116 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 11:58:56.448  5939  6116 D libc    : [NET] android_getaddrinfo_proxy+
07-05 11:58:56.448  5939  6116 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 11:58:56.448   396  6120 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-05 11:58:56.448   396  6120 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 11:58:56.448   396  6120 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 11:58:56.448   396  6120 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 11:58:56.448  5939  6116 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 11:58:56.458  6093  6093 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
,07-05 11:58:56.488  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 11:58:56.488  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-05 11:58:56.488  6093  6093 V Settings:HtcSettingsApplication: [6093/6093] onCreate()
07-05 11:58:56.488  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-05 11:58:56.498  1945  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
,07-05 11:58:56.498  1945  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:56.498  1945  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:58:56.498  1945  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:58:56.498  1945  2118 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:56.528   969  1276 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6122 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,07-05 11:58:56.528   969  1276 I ActivityManager: Killing 5463:com.htc.bgp/u0a11 (adj 15): empty #17
07-05 11:58:56.528   969  1276 D Process : killProcessQuiet, pid=5463
07-05 11:58:56.528   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-05 11:58:56.538  1623  1875 I ContextualWidget: MFU.onLoadComplete
07-05 11:58:56.538  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 11:58:56.538  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 11:58:56.538  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-05 11:58:56.538  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:58:56.538  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 11:58:56.538  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:58:56.578  6093  6145 D Settings:HtcWirelessFeatureFlags: id/is att sku: 118/false,
,07-05 11:58:56.618  6093  6145 E Settings:HtcWrapHeaderInfo: no such activity!
,07-05 11:58:56.628  6093  6137 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
,07-05 11:58:56.638  6093  6137 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-05 11:58:56.658   969  1681 I ActivityManager: Recipient 5463
,07-05 11:58:56.678  6093  6137 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
,07-05 11:58:56.758   969  1256 V AlarmManager: sending alarm PendingIntent{31ddf14e: PendingIntentRecord{b59b26f com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1467712736734, Int=0
,07-05 11:58:56.768  1945  2118 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-05 11:58:56.768  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-05 11:58:56.768  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-05 11:58:56.768  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
,07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:58:56.778  6093  6137 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-05 11:58:56.798  5939  6118 E Babel   : Unexpected exception while authenticating.,
07-05 11:58:56.798  5939  6118 E Babel   : eej: User intervention required. Notification has been pushed.
07-05 11:58:56.798  5939  6118 E Babel   : 	at eeg.b(Unknown Source)
07-05 11:58:56.798  5939  6118 E Babel   : 	at eeg.b(Unknown Source)
07-05 11:58:56.798  5939  6118 E Babel   : 	at g.a(Unknown Source)
07-05 11:58:56.798  5939  6118 E Babel   : 	at cae.b(SourceFile:1146)
07-05 11:58:56.798  5939  6118 E Babel   : 	at dcg.run(SourceFile:5617)
07-05 11:58:56.798  5939  6118 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 11:58:56.798  5939  6118 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 11:58:56.798  5939  6118 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
07-05 11:58:56.798  1443  1673 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 11:58:56.798  1443  1673 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-05 11:58:56.808  1339  1339 I RemoteViews: reapply : com.google.android.gms 2 40,
07-05 11:58:56.808  1443  1673 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 11:58:56.808   969  1990 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi,
07-05 11:58:56.808  6093  6137 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
,07-05 11:58:56.808  6093  6137 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-05 11:58:56.818  6093  6141 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.
,07-05 11:58:56.818  6093  6141 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-05 11:58:56.828  6093  6141 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false
,07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true,
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:58:56.828  6093  6141 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-05 11:58:56.838   969  1676 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi,
07-05 11:58:56.838  6093  6141 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-05 11:58:56.838  6093  6141 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
,07-05 11:58:56.948   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6122, uid=10072, userID:0,
,07-05 11:58:56.958  6122  6122 W global  : [apache-http] Connection GC has been deprecated!,
,07-05 11:58:56.988  6122  6122 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,07-05 11:58:56.988  6122  6122 W global  : [apache-http] Connection GC has been deprecated!,
,07-05 11:58:57.148   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:58:57.148  1339  1339 D WIFI_ICON: WifiActivity: 2
07-05 11:58:57.148   969   969 E WifiTrafficPoller:  packet count Tx=148 Rx=205
,07-05 11:58:57.148  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
07-05 11:58:57.148   969   969 E WifiTrafficPoller: notifying of data activity 2
,07-05 11:58:57.168   969  4144 I art     : Explicit concurrent mark sweep GC freed 13374(669KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/24MB, paused 1.695ms total 127.095ms,
,07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: nl80211: New scan results available
07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
07-05 11:58:57.178  1432  1432 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: Scan completed in 2.157339 seconds
07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Associated on 2447 MHz
07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Received scan results (8 BSSes)
07-05 11:58:57.178  1432  1432 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-56
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-65
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-65
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 00:1a:ef:42:f2:b0 freq=2412 level=-77
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 00:16:a6:1f:06:5c freq=2462 level=-79
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 00:fe:c8:73:02:02 freq=2462 level=-89
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-86
07-05 11:58:57.178  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:12:64:93 freq=2412 level=-87
,07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Start scan result update 3
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 3 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 4 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 5 BSSID 00:fe:c8:73:02:02 SSID '\x00'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 6 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 7 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS'
07-05 11:58:57.178  1432  1432 D wpa_supplicant: BSS: last_scan_res_used=8/32
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: Scan-only results received
07-05 11:58:57.178  1432  1432 D wpa_supplicant: wlan0: Radio work 'scan'@0x55baf59aa0 done in 2.158922 seconds
07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 00:1f:27:54:70:c0]
,07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 00:1f:27:54:70:c1]
07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 00:1a:ef:42:f2:b0]
07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 00:fe:c8:73:02:02]
07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 84:b2:61:1a:ce:73]
07-05 11:58:57.178   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 84:b2:61:12:64:93]
,07-05 11:58:57.178   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-05 11:58:57.178   969  1788 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-05 11:58:57.178   969  1267 E WifiStateMachine: handleMessage: E msg.what=147461
07-05 11:58:57.178   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:58:57.178   969  1267 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
07-05 11:58:57.178   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:57.178   969  1267 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
07-05 11:58:57.178   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:58:57.188   969  1267 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
07-05 11:58:57.188   969  1267 E WifiStateMachine: processMsg: DriverStartedState
07-05 11:58:57.188   969  1267 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
07-05 11:58:57.188   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
,07-05 11:58:57.188   969  1267 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
07-05 11:58:57.188   969  1267 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
07-05 11:58:57.188   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
07-05 11:58:57.188  1432  1432 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,07-05 11:58:57.198   969  1267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14202 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14367 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8128 
,07-05 11:58:57.198   969  1267 E WifiStateMachine: [1,467,712,737,209 ms] noteScanEnd no scan source
07-05 11:58:57.198   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
07-05 11:58:57.198  1432  1432 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,07-05 11:58:57.198   969  1267 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@338ae233 sup_state=COMPLETED debouncing=false,
07-05 11:58:57.198   969  1267 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-56 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,07-05 11:58:57.198   969  1267 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
07-05 11:58:57.198   969  1267 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
07-05 11:58:57.198   969  1267 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-56 freq=2447
07-05 11:58:57.198   969  1267 E WifiAutoJoinController :  00:16:a6:1f:06:5c rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
,07-05 11:58:57.208   969  1267 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-65 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-65 cap [WPA2-EAP-TKIP][ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : Conrad_AP 00:1a:ef:42:f2:b0 rssi=-77 cap [WPA-PSK-CCMP][WPS][ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController :  00:fe:c8:73:02:02 rssi=-89 cap [WPA2-PSK-CCMP][ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-86 cap [ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:12:64:93 rssi=-87 cap [ESS] is not scored
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 8 now 1467712737217
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : newSupplicantResults size=8 known=1 true
07-05 11:58:57.208   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
07-05 11:58:57.208  1432  1432 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
,07-05 11:58:57.208   969  1267 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : ssid=NG700
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : id=0
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : mode=station
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : pairwise_cipher=CCMP
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : group_cipher=CCMP
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : key_mgmt=WPA2-PSK
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : wpa_state=COMPLETED
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : ip_address=192.168.1.107
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
,07-05 11:58:57.208   969  1267 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-56,-127) num=(1,0)
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-56 freq=2447 Current: f4:f2:6d:22:99:3e
07-05 11:58:57.208   969  1267 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
07-05 11:58:57.208   969  1267 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 11:58:57.208   969  1267 E WifiAutoJoinController : Done attemptAutoJoin status=0
07-05 11:58:57.208   969  1267 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
07-05 11:58:57.208   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:57.208  1842  1842 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10024
07-05 11:58:57.218  6122  6122 W global  : [apache-http] Connection GC has been deprecated!,
,07-05 11:58:57.238  5939  6116 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-05 11:58:57.248  6122  6122 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,07-05 11:58:57.328   969  4144 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6164 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,07-05 11:58:57.358  6122  6122 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
07-05 11:58:57.358  6122  6122 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 11:58:57.368  6164  6164 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-05 11:58:57.378  6164  6164 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:58:57.378   969  1981 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6122, uid=10072, userID:0
,07-05 11:58:57.388  6164  6164 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 11:58:57.388  6164  6164 I MultiDex: install
07-05 11:58:57.388  6164  6164 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 11:58:57.408  6164  6164 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-05 11:58:57.428  6122  6122 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,07-05 11:58:57.428  6122  6122 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,07-05 11:58:57.438  6122  6122 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-05 11:58:57.448  6164  6164 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e5b323: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 11:58:57.448  6164  6164 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-05 11:58:57.448  6164  6164 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:58:57.478  2228  6194 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 11:58:57.478  6122  6122 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-05 11:58:57.488   969  1276 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6195 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,07-05 11:58:57.498   969  1276 D Process : killProcessQuiet, pid=5380,
07-05 11:58:57.498   969  1276 I ActivityManager: Killing 5380:com.htc.task/u0a69 (adj 15): empty #17
07-05 11:58:57.498   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:57.568   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:58:57.568   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:58:57.568   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=4.7, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:2550] from screen [on:0 period:-1166077649] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:58:57.568   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:58:57.568   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=4.7, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166077647] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:58:57.578   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:58:57.578   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:58:57.578  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:58:57.578  1432  1432 I wpa_supplicant: environment dirty rate=0 [4][0][0],
07-05 11:58:57.578   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:58:57.578   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
,07-05 11:58:57.578   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
07-05 11:58:57.578   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.36 txretriesrate=0.00 rxrate=4.05 userTriggerdPenalty0
07-05 11:58:57.578   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:58:57.578   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:58:57.578   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61,
,07-05 11:58:57.588   969  1676 I ActivityManager: Recipient 5380
,07-05 11:58:57.608   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:58:57.618   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:58:57.618  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:58:57.618  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,07-05 11:58:57.618  2228  6194 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.,
,07-05 11:58:57.628   969  1981 D PMS     : acquireWL(c4f49fe): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:57.628  6195  6195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 11:58:57.698  2228  4461 I Icing   : Storage manager: low false usage 1.98MB avail 3.92GB capacity 7.95GB
,07-05 11:58:57.738  2228  4461 W Icing   : Received bad json for section weights override -- ignoring.,
,07-05 11:58:57.748  2228  4461 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,07-05 11:58:57.748  2228  4461 W Icing   : Received bad json for section weights override -- ignoring.
07-05 11:58:57.748  2228  4461 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,07-05 11:58:57.818  3202  3264 I HtcModeClient: handler message = 4011,
07-05 11:58:57.818  3202  3264 E HtcModeClient: Check connection and retry 7 times.
,07-05 11:58:57.828   969  1442 D PMS     : acquireWL(3c1ca87b): PARTIAL_WAKE_LOCK  AsyncService 0x1 6195 10167 null,
,07-05 11:58:57.828   969  2390 D PMS     : acquireWL(ccd2ef1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6195 10167 null,
,07-05 11:58:57.838   969  1981 D PMS     : releaseWL(3c1ca87b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-05 11:58:57.838  2228  4461 E Icing   : Loading extension by file descriptor -1 failed
,07-05 11:58:57.848   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
07-05 11:58:57.848  6039  6228 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 11:58:57.858   969  6229 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=132 rxSum=126} preTxRxSum={txSum=126 rxSum=122}
07-05 11:58:57.858   969  6229 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
,07-05 11:58:57.858   969  6229 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:58:57.898  1623  1623 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
,07-05 11:58:57.898  1675  6234 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest,
,07-05 11:58:57.898  1675  6234 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-05 11:58:57.898  1623  1623 I ContextualWidget: package com.test.thalitest added
,07-05 11:58:57.918   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0,
07-05 11:58:57.918   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:58:57.918   969  1990 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.918   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.918   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.918   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.918   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:58:57.918   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.928   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:57.928   969  2390 D PMS     : releaseWL(ccd2ef1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
07-05 11:58:57.928   969  1758 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6239 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,07-05 11:58:57.938   969  1758 I ActivityManager: Killing 4993:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
07-05 11:58:57.938   969  1758 D Process : killProcessQuiet, pid=4993
07-05 11:58:57.938   969  1758 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:57.938  1623  6238 W SystemReader: Cannot find enable_download_option, use default value instead
,07-05 11:58:57.948  6122  6122 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,07-05 11:58:58.028  6039  6228 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 178 ms] updated apps [took 178 ms] 
,07-05 11:58:58.048   969  1442 I ActivityManager: Recipient 4993
,07-05 11:58:58.148   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:58:58.148   969   969 E WifiTrafficPoller:  packet count Tx=151 Rx=208
07-05 11:58:58.148  1339  1339 D WIFI_ICON: WifiActivity: 3
07-05 11:58:58.148   969   969 E WifiTrafficPoller: notifying of data activity 3
07-05 11:58:58.148  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,07-05 11:58:58.158   969  1981 D Process : killProcessQuiet, pid=5687
07-05 11:58:58.158   969  1981 I ActivityManager: Killing 5687:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
07-05 11:58:58.168   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:58.258   969  1276 I ActivityManager: Recipient 5687
07-05 11:58:58.258   969  1268 D WifiService: Client connection lost with reason: 4
,07-05 11:58:58.278   969  1256 V AlarmManager: sending alarm PendingIntent{3341144f: PendingIntentRecord{2affe7dc com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712738260, Int=0,
,07-05 11:58:58.288  6122  6122 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-05 11:58:58.308  6239  6239 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6239 dbg=false s=true,
,07-05 11:58:58.318  6239  6239 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-05 11:58:58.318  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:58.348   969   988 I ActivityManager: Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=6263 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,07-05 11:58:58.368  2228  4461 I Icing   : updateResources: need to parse f{com.google.android.gms},
,07-05 11:58:58.378  1945  1977 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 11:58:58.378  1945  1977 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,07-05 11:58:58.378  1945  1977 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 11:58:58.378  1945  1977 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 11:58:58.388  1945  1977 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:58.398   969  1256 V AlarmManager: sending alarm PendingIntent{3f8b9f5e: PendingIntentRecord{39b5af3f com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1467712738406, Int=0
,07-05 11:58:58.398  6263  6263 D HtcCupdReceiver(Provider):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
07-05 11:58:58.398   969  1256 V AlarmManager: sending alarm PendingIntent{68ad6ae: PendingIntentRecord{f1a9c4f android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1467712733080, Int=20000
,07-05 11:58:58.428  6122  6122 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 11:58:58.438  2228  4461 I Icing   : Internal init done: storage state 0
,07-05 11:58:58.448  2228  6286 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-05 11:58:58.448  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:58.458  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 11:58:58.458  2228  2228 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,07-05 11:58:58.468   969   989 D PMS     : acquireWL(3552620d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2228 10024 null,
,07-05 11:58:58.478  2228  4461 I Icing   : Post-init done
,07-05 11:58:58.488  2228  4461 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-05 11:58:58.488  2228  6284 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 86 ms
,07-05 11:58:58.498  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 11:58:58.498  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:58.498  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:58:58.498  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:58:58.498  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:58:58.508   969  1276 D PMS     : releaseWL(c4f49fe): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:58.538  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:58.568  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 11:58:58.568  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:58.568  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:58:58.568  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 11:58:58.578  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:58.588  6122  6122 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 11:58:58.628  2228  2228 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-05 11:58:58.628  2228  2228 I ConfigFetchService: launchTask,
07-05 11:58:58.628   969  1993 D PMS     : acquireWL(5ace87d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 2228 10024 WorkSource{10195 com.test.thalitest}
07-05 11:58:58.638   969  1758 D PMS     : releaseWL(3552620d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-05 11:58:58.648   969  2390 D PMS     : acquireWL(4bca3c3): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:58:58.648  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games,
07-05 11:58:58.648  2228  2228 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded,
,07-05 11:58:58.648  2228  6289 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W-XCms6N1eoV4MZgxpXxSo7zua8oeQRadnDZ8i8W3wOcOHSGBJHJdlBs4BuLeTZSI8mVlymKmZOV3uQ8xtg6dOGOPw1YDeoy2S_QU2m9kq_RQMqxjlS23LJmoQl83lMwnj-B25tqjjGqq17EXWlXseRzwzE7NijIuR838NMQ4lrIBzcyaF2c6qHNmyo9ccU5p1oG3cn0Eqa_rFK1b4ZskbuTJ6Mwj-Ep7edlXz2r5KbksvGlw
,07-05 11:58:58.658   969  1676 D PMS     : releaseWL(4bca3c3): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:58.658  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,07-05 11:58:58.658  2228  6290 I PeopleContactsSync: CP2 sync disabled
,07-05 11:58:58.668  2228  6289 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 11:58:58.668   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2228, uid=10024, userID:0
07-05 11:58:58.668  2228  2228 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,07-05 11:58:58.668  2228  2228 D Vision  : Failed to find package metadata for com.test.thalitest
07-05 11:58:58.668  2228  2228 D Vision  : No vision deps
,07-05 11:58:58.688  6122  6138 E AndroidHttpClient: Leak found
,07-05 11:58:58.688  6122  6138 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 11:58:58.688  6122  6138 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-05 11:58:58.688   969   989 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6293 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,07-05 11:58:58.698   969  1464 D PMS     : acquireWL(1cbbb91f): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:58.708   410   410 I art     : Explicit concurrent mark sweep GC freed 8660(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 146us total 19.455ms,
07-05 11:58:58.708   969  1981 D PMS     : releaseWL(1cbbb91f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:58:58.718   969  1981 D PMS     : acquireWL(2dd5aa35): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:58.728   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 15.881ms
,07-05 11:58:58.728   969  4144 D PMS     : releaseWL(2dd5aa35): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:58.748   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 15.134ms
,07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfo_proxy+
07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 11:58:58.758   396  6314 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 11:58:58.758   396  6314 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 11:58:58.758   396  6314 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 11:58:58.758   396  6314 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 11:58:58.758  2228  6289 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 11:58:58.848  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 11:58:58.848  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 11:58:58.918  2228  6289 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-05 11:58:58.918  2228  6289 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:58:58.918  2228  6289 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 11:58:58.918  2228  6289 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:58:58.928  1945  2118 I art     : Explicit concurrent mark sweep GC freed 16138(967KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 915us total 44.383ms,
,07-05 11:58:58.938  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 11:58:58.958  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 11:58:58.958  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.,
,07-05 11:58:58.968  2228  2228 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 11:58:58.968   969  1442 D PMS     : releaseWL(5ace87d): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10195 com.test.thalitest}
07-05 11:58:58.968  2228  2228 I ConfigFetchService: stopping self
,07-05 11:58:58.978  2228  6292 W BaseAppContext: Using Auth Proxy for data requests.,
,07-05 11:58:58.988  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:59.018  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,07-05 11:58:59.018  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:58:59.018  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 11:58:59.018  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:58:59.028  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:58:59.048  6122  6122 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,07-05 11:58:59.048  6122  6122 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,07-05 11:58:59.058  6122  6122 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,07-05 11:58:59.068  6122  6122 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1),
,07-05 11:58:59.068   969  1276 D Process : killProcessQuiet, pid=5656
07-05 11:58:59.068   969  1276 I ActivityManager: Killing 5656:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
07-05 11:58:59.078   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 ,
07-05 11:58:59.078  1842  1869 D DeviceConnectionService: client connected with version: 7571000
,07-05 11:58:59.148   969   988 I ActivityManager: Recipient 5656,
,07-05 11:58:59.148   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
07-05 11:58:59.148   969   969 E WifiTrafficPoller:  packet count Tx=162 Rx=220
,07-05 11:58:59.178   969  1276 D Process : killProcessQuiet, pid=5782,
07-05 11:58:59.178   969  1276 I ActivityManager: Killing 5782:com.htc.task.gtask/u0a66 (adj 15): empty #18
07-05 11:58:59.178   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:58:59.218   969  1981 I art     : Explicit concurrent mark sweep GC freed 17320(843KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.662ms total 171.463ms
,07-05 11:58:59.278   969  1758 I ActivityManager: Recipient 5782,
,07-05 11:58:59.308  1772  2139 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
07-05 11:58:59.318  5900  5929 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-05 11:58:59.318   969  1258 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-05 11:58:59.348  1772  2139 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-05 11:58:59.358  5440  5634 W jxcore-log: Platform android
07-05 11:58:59.358  5440  5634 W jxcore-log: 
07-05 11:58:59.358  5440  5634 W jxcore-log: Process ARCH arm
07-05 11:58:59.358  5440  5634 W jxcore-log: 
07-05 11:58:59.358  1572  1572 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
07-05 11:58:59.368  1842  1869 I art     : Explicit concurrent mark sweep GC freed 15533(849KB) AllocSpace objects, 6(120KB) LOS objects, 46% free, 4MB/8MB, paused 1.005ms total 75.203ms
,07-05 11:58:59.378  1772  2139 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,07-05 11:58:59.398  1772  2139 E ExternalAccountType: Unsupported attribute readOnly
,07-05 11:58:59.448   969  1026 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-05 11:58:59.448   969   969 W PackageManager: Unable to load service info ResolveInfo{386b6fc9 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-05 11:58:59.448   969   969 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 11:58:59.448   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70),
07-05 11:58:59.448   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 11:58:59.448   969   969 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:58:59.448   969   969 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324),
07-05 11:58:59.448   969   969 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 11:58:59.448   969   969 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:58:59.448   969   969 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:58:59.448   969   969 W PackageManager: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 11:58:59.448   969   969 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-05 11:58:59.468  6293  6293 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-05 11:58:59.468  6293  6293 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 11:58:59.468  6293  6293 I GAv4    :   adb logcat -s GAv4
,07-05 11:58:59.488  6293  6293 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 11:58:59.498   969   969 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-05 11:58:59.518  1842  1842 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,07-05 11:58:59.528  6293  6293 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-05 11:58:59.538   969  1758 D PMS     : acquireWL(a580408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:59.538  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-05 11:58:59.538  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-05 11:58:59.538   969  1681 D PMS     : releaseWL(a580408): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.548  1623  1623 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-05 11:58:59.558   969  1026 D LocationProviderProxy: applying state to connected service
,07-05 11:58:59.568  6293  6329 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 11:58:59.568  1623  1623 I Launcher: Deferring update until onResume
07-05 11:58:59.568  1623  1623 D Launcher: waitUntilResume // bindAppsUpdated
,07-05 11:58:59.578  6293  6293 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,07-05 11:58:59.598   969  1026 D LocationProviderProxy: applying state to connected service,
,07-05 11:58:59.598  1842  1842 V GmsNetworkLocationProvi: DISABLE
,07-05 11:58:59.608   969  1026 D PMS     : acquireWL(1ee457a1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:58:59.608   969  1706 D PMS     : acquireWL(21728dc6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.618   969  1681 D PMS     : releaseWL(21728dc6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.618   969   989 D PMS     : releaseWL(1ee457a1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:58:59.648  5440  5634 I jxcore-log: JXcore Cordova bridge is ready!,
07-05 11:58:59.648  5440  5634 I jxcore-log: 
07-05 11:58:59.648  5440  5634 W jxcore-log: JXcore engine is started,
,07-05 11:58:59.708   969  1276 D VoldConnector: SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,07-05 11:58:59.708   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,07-05 11:58:59.708  6293  6334 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,07-05 11:58:59.718   969  1676 D PMS     : acquireWL(295c0f23): PARTIAL_WAKE_LOCK  AsyncService 0x1 6195 10167 null
,07-05 11:58:59.728   969  2390 D PMS     : releaseWL(295c0f23): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,07-05 11:58:59.728   969  1981 D PMS     : acquireWL(5df59d9): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6195 10167 null
,07-05 11:58:59.738  6293  6335 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 11:58:59.738  6293  6335 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:58:59.778  6293  6335 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-05 11:58:59.778   969  1981 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0,
,07-05 11:58:59.778   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0,
07-05 11:58:59.778   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:59.778   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:59.778   969   989 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:58:59.778   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:59.778   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:58:59.778   969  1990 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:58:59.778   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=6195, uid=10167, userID:0,
,07-05 11:58:59.788   969  1758 D PMS     : releaseWL(5df59d9): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,07-05 11:58:59.808  2228  6292 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,07-05 11:58:59.808  2228  6292 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-05 11:58:59.818   969  1706 D PMS     : acquireWL(32df0a4c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5588 10159 null,
,07-05 11:58:59.818  6039  6338 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-05 11:58:59.828  6293  6335 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 11:58:59.828  6293  6335 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:58:59.868  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:58:59.868   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5588, uid=10159, userID:0
,07-05 11:58:59.878   969  1464 D PMS     : releaseWL(32df0a4c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,07-05 11:58:59.878  5588  6341 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 11:58:59.878  5588  6341 I MusicLeanback: Stop autocaching.
,07-05 11:58:59.888   969  2390 I ActivityManager: Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver,
,07-05 11:58:59.928   969  1981 I ActivityManager: Resuming delayed broadcast,
07-05 11:58:59.928   969  1706 D PMS     : acquireWL(3d655a80): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:58:59.928   969  1276 D PMS     : releaseWL(3d655a80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
07-05 11:58:59.938  5588  5588 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:58:59.938  5588  6351 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:58:59.948   969  1681 D PMS     : acquireWL(3fdf34fe): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.958   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=6069, uid=10027, userID:0
,07-05 11:58:59.968   969  1464 D PMS     : acquireWL(2ea3245f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.978   969  1990 D PMS     : releaseWL(2ea3245f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:58:59.988   969  4144 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6361 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,07-05 11:58:59.988   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=76414, Int=0
,07-05 11:59:00.018  1339  2550 D WeatherUtility: Weather sync is On
,07-05 11:59:00.018  1339  2550 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,07-05 11:59:00.038  1339  2168 I ClockController: schedule update now=1467712740045 next=59955,
07-05 11:59:00.038  1339  1339 I Clock   : updateClock:11:59 Europe/Warsaw
07-05 11:59:00.038  1339  1339 I Clock   : updateClock:11:59 Europe/Warsaw
07-05 11:59:00.038  1339  1339 I Clock   : updateClock:11:59 Europe/Warsaw
,07-05 11:59:00.058   969  1276 D PMS     : acquireWL(1952e5d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms},
07-05 11:59:00.058   969  4144 D PMS     : releaseWL(1952e5d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.078  6039  6338 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 257 ms] updated apps [took 257 ms] 
,07-05 11:59:00.148  6361  6361 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION,
07-05 11:59:00.148   969  1990 D PMS     : acquireWL(23d74057): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.148   969  1442 D PMS     : releaseWL(23d74057): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:00.148   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
07-05 11:59:00.148   969   969 E WifiTrafficPoller:  packet count Tx=162 Rx=228
07-05 11:59:00.148   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:00.158  1339  1339 D WIFI_ICON: WifiActivity: 1
,07-05 11:59:00.158  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:00.178  6361  6361 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 11:59:00.188   969   988 D PMS     : acquireWL(328b1744): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.188   969  1681 D PMS     : releaseWL(328b1744): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.198  6361  6361 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 11:59:00.208   969  1990 D PMS     : acquireWL(28e7d02d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.208   969  1758 D PMS     : releaseWL(28e7d02d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.218  6361  6361 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 11:59:00.228   969  1993 D PMS     : acquireWL(3bef8962): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:00.228   969  1990 D PMS     : releaseWL(3bef8962): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.248   969   989 D PMS     : acquireWL(24a58af3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.248   969   988 D PMS     : releaseWL(24a58af3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.258   969  1276 I ActivityManager: Killing 5734:com.htc.sdm/u0a79 (adj 15): empty #17
07-05 11:59:00.258   969  1276 D Process : killProcessQuiet, pid=5734
,07-05 11:59:00.258   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:00.358   969  1993 I ActivityManager: Recipient 5734,
,07-05 11:59:00.378   969  1276 D Process : killProcessQuiet, pid=5826
07-05 11:59:00.378   969  1276 I ActivityManager: Killing 5826:com.google.android.setupwizard/u0a77 (adj 15): empty #17
07-05 11:59:00.378   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:59:00.488   969  1981 I ActivityManager: Recipient 5826
,07-05 11:59:00.578   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:00.578   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:00.578   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=4.4, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:2970] from screen [on:0 period:-1166074638] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:00.588   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:00.588   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=4.4, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166074636] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:00.588   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:00.588   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:00.588  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:00.598   969   989 I ActivityManager: Killing 5868:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,07-05 11:59:00.598   969   989 D Process : killProcessQuiet, pid=5868
,07-05 11:59:00.598   969   989 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:59:00.598  1432  1432 I wpa_supplicant: environment dirty rate=0 [11][0][0]
07-05 11:59:00.598   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:00.598   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
07-05 11:59:00.598   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:00.598   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.68 txretriesrate=0.00 rxrate=14.03 userTriggerdPenalty0
07-05 11:59:00.598   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:00.598   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:59:00.598   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-05 11:59:00.668   969  1676 I ActivityManager: Recipient 5868,
,07-05 11:59:00.718   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:00.718   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
07-05 11:59:00.718  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:00.718  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:00.738   969  1993 D PMS     : acquireWL(3ac0d9ae): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.748   969  1981 D PMS     : acquireWL(c040adc): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:59:00.748   969  1464 D PMS     : releaseWL(3ac0d9ae): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.748   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.photos, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=6006, uid=10197, userID:0
,07-05 11:59:00.748   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2228, uid=10024, userID:0
07-05 11:59:00.758   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.photos, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=6006, uid=10197, userID:0
,07-05 11:59:00.768  2228  6401 I CheckinService: Checking schedule, now: 1467712740780 next: 1467712758984,
07-05 11:59:00.768  2228  6401 I CheckinService: active receiver: disabled
07-05 11:59:00.768   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:00.768  2228  2228 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver },
,07-05 11:59:00.778   969  1681 D PMS     : acquireWL(1b2fd7e5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:59:00.778  2228  2228 D SystemUpdateService: onCreate
,07-05 11:59:00.788  2228  2228 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-05 11:59:00.788   969   989 D PMS     : releaseWL(c040adc): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.808  2228  6402 I SystemUpdateService: cancelUpdate (empty URL),
07-05 11:59:00.808  2228  6402 I SystemUpdateService: active receiver: disabled
,07-05 11:59:00.808   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:00.808  2228  2228 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast,
07-05 11:59:00.808  1945  2915 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 11:59:00.818  2228  2228 I OcrUtils: Updating ocr activity enabled=false,
,07-05 11:59:00.818   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2228, uid=10024, userID:0,
07-05 11:59:00.818   969  1990 D PMS     : releaseWL(1b2fd7e5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.838  2228  2228 D SystemUpdateService: onDestroy
,07-05 11:59:00.838  1842  1842 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-05 11:59:00.858  1842  1842 I GCoreUlr: DispatchingService.onCreate()
,07-05 11:59:00.878   969  1758 D PMS     : acquireWL(2304d974): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:00.888   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.copresence.service.ProximitySettingInjectorService, state=2, flag=1, pid=1842, uid=10024, userID:0
,07-05 11:59:00.918  1842  6405 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED,
,07-05 11:59:01.028  1945  1969 I art     : Explicit concurrent mark sweep GC freed 7219(367KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 1.032ms total 53.670ms,
,07-05 11:59:01.038  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-05 11:59:01.038  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 +,
07-05 11:59:01.038  1623  1836 I Prism.WidgetManager: onLoadItems() +
,07-05 11:59:01.088  2228  4461 I Icing   : Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,07-05 11:59:01.118  1623  1836 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-05 11:59:01.128  1842  6405 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 11:59:01.128   969   989 D PMS     : acquireWL(70a1e9d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:01.138   969  2390 D PMS     : releaseWL(70a1e9d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:01.138  1842  6405 I GCoreUlr: Unbound from all location providers
,07-05 11:59:01.148   969  4144 D PMS     : releaseWL(2304d974): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:01.158   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,07-05 11:59:01.158   969   969 E WifiTrafficPoller:  packet count Tx=162 Rx=232
,07-05 11:59:01.228  2228  4461 I Icing   : Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376,
,07-05 11:59:01.248   969  1676 D PMS     : releaseWL(3fdf34fe): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:01.328   969  1276 I art     : Explicit concurrent mark sweep GC freed 22171(1246KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.542ms total 178.086ms
,07-05 11:59:01.348  2228  2228 I art     : Explicit concurrent mark sweep GC freed 17817(1074KB) AllocSpace objects, 8(160KB) LOS objects, 40% free, 7MB/12MB, paused 1.045ms total 96.565ms
,07-05 11:59:01.358  1842  1842 I GCoreUlr: DispatchingService.onDestroy()
,07-05 11:59:01.358   969  1990 D PMS     : acquireWL(1f110f12): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:01.358   969  1758 D PMS     : releaseWL(1f110f12): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
07-05 11:59:01.358  1623  1836 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 11:59:01.368  1842  1842 I GCoreUlr: Unbound from all location providers
,07-05 11:59:01.388  1572  2200 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-05 11:59:01.388  1572  2200 D PhoneApp: -- N1 =0
07-05 11:59:01.388  1572  2200 D PhoneApp: -- N2 =0
07-05 11:59:01.388  1572  2200 D PhoneApp: -- N3 =0
,07-05 11:59:01.408   969  1276 D PMS     : acquireWL(25018e0): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:59:01.428  2228  4461 E Icing   : Loading extension by file descriptor -1 failed
,07-05 11:59:01.448   969  1464 I ActivityManager: Killing 5638:com.htc.sense.mms/u0a64 (adj 15): empty #17,
07-05 11:59:01.448   969  1464 D Process : killProcessQuiet, pid=5638
,07-05 11:59:01.448   969  1464 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:01.488  1623  1836 W asset   : Copying FileAsset 0xacfd38f8 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,07-05 11:59:01.498  1945  1977 I art     : Explicit concurrent mark sweep GC freed 3556(139KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 929us total 60.881ms
,07-05 11:59:01.508   969  1676 D PMS     : releaseWL(25018e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:01.548  1623  1836 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-05 11:59:01.548  1623  1836 I Prism.WidgetManager: onLoadItems() -
,07-05 11:59:01.548  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 -
,07-05 11:59:01.558   969  1276 I ActivityManager: Recipient 5638
,07-05 11:59:01.678   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1842, uid=10024, userID:0,
,07-05 11:59:01.688   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1945, uid=10024, userID:0,
,07-05 11:59:01.728  1945  2943 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 11:59:01.738  1945  1945 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 11:59:01.748  2228  2228 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 11:59:01.768   969  1026 D PMS     : acquireWL(f4de30c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,07-05 11:59:01.768   969  1026 D PMS     : acquireWL(269f8455): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 969 1000 WorkSource{10024}
,07-05 11:59:01.768   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:01.778  1339  1708 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
07-05 11:59:01.778   969  1026 D PMS     : releaseWL(f4de30c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,07-05 11:59:01.788   969  1026 D PMS     : acquireWL(144b87a4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,07-05 11:59:01.788   969  1026 D PMS     : releaseWL(144b87a4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
07-05 11:59:01.788  1842  6415 E MDM     : [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:59:01.798  2228  6417 D LocationInitializer: Restart initialization of location,
,07-05 11:59:01.838  6039  6423 I GservicesUpdateTask: Updating Gservices keys
,07-05 11:59:01.838  1339  1339 D PhoneStatusBar: addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,07-05 11:59:01.838   969  1676 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6424 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,07-05 11:59:01.908  6424  6424 D PhoneMonitor: Register our PhoneStateListener
,07-05 11:59:01.928   969  1026 D PMS     : acquireWL(2f36d041): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,07-05 11:59:01.928  6424  6424 V SetupWizard: Connected to Gservices successfully,
07-05 11:59:01.928   969  1026 D PMS     : releaseWL(269f8455): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,07-05 11:59:01.938  1339  1708 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
07-05 11:59:01.938   969  1026 D PMS     : releaseWL(2f36d041): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,07-05 11:59:01.958  6424  6424 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-05 11:59:01.958  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 11:59:01.958  2228  2228 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,07-05 11:59:01.968  6424  6424 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-05 11:59:01.978  1945  2947 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 11:59:01.988   969  1706 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=6451 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,07-05 11:59:02.038  6451  6451 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:59:02.048  6451  6473 I DFPI.ApkInstallService: onHandleIntent
07-05 11:59:02.048  6451  6473 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:59:02.058  6451  6473 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:59:02.058  6451  6473 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:59:02.058   969   988 D Process : killProcessQuiet, pid=5900
07-05 11:59:02.058   969   988 I ActivityManager: Killing 5900:com.google.android.gm/u0a106 (adj 15): empty #17
07-05 11:59:02.058   969   988 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:02.148   969   989 I ActivityManager: Recipient 5900
,07-05 11:59:02.158   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-05 11:59:02.158   969   969 E WifiTrafficPoller:  packet count Tx=162 Rx=233
,07-05 11:59:02.198   969  2390 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=6474 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,07-05 11:59:02.248  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:59:02.258  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:59:02.268  6474  6495 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:59:02.268  6474  6495 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:59:02.268  6474  6495 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,07-05 11:59:02.268  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.278  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.278  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.278  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.278  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:59:02.278  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.278  6474  6495 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:59:02.278  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:59:02.278  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:59:02.278  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.288  1675  6497 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,07-05 11:59:02.288  1675  6497 D WeatherUtility: Weather sync is On
,07-05 11:59:02.288  5980  5980 D ProviderChangeReceiver: ---------------------------------------------------
07-05 11:59:02.288  5980  5980 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-05 11:59:02.298  5980  6498 D HtcAlertService: start to updateAlertNotification!
,07-05 11:59:02.318   969   988 I ActivityManager: Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=6499 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,07-05 11:59:02.318  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-05 11:59:02.328  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.328  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.328  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.328  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:59:02.328  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.338  1675  6497 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jul 05 12:59:02 CEST 2016
,07-05 11:59:02.338  6451  6451 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:59:02.338  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.348  6451  6518 I DFPI.ApkInstallService: onHandleIntent
,07-05 11:59:02.348  6451  6518 I DFPI.ApkInstallService: Media Scan Finished Case ,
07-05 11:59:02.348  6451  6518 D DFPI.ApkInstallService: check CID = HTC__102
07-05 11:59:02.348  6451  6518 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:59:02.348  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.348  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.348  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:59:02.348  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.348  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.358  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:59:02.368  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-05 11:59:02.368  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:59:02.368  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.368  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.368  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-05 11:59:02.368  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:59:02.368  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:59:02.378  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.378  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.378  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.378  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.378  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.378  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:59:02.388  6499  6499 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:59:02.388  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:59:02.388  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.388  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.388  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:59:02.388  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:59:02.398  6451  6451 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:59:02.408  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
07-05 11:59:02.408  6451  6523 I DFPI.ApkInstallService: onHandleIntent
07-05 11:59:02.408  6451  6523 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-05 11:59:02.408  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
07-05 11:59:02.408  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:59:02.408  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.408  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:59:02.408  6451  6523 D DFPI.ApkInstallService: check CID = HTC__102,
07-05 11:59:02.408  6451  6523 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-05 11:59:02.418  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-05 11:59:02.418  6474  6474 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-05 11:59:02.418  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:59:02.428  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-05 11:59:02.428  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:59:02.428  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:59:02.428  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:59:02.428   969   969 D PMS     : acquireWL(28b98740): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 969 1000 null
,07-05 11:59:02.428   969  1026 D PMS     : acquireWL(39b44679): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 969 1000 null
,07-05 11:59:02.438   969  1026 D PMS     : releaseWL(28b98740): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,07-05 11:59:02.438  5588  6496 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-05 11:59:02.438  1675  6521 D WSP     : save sync status: 1467711113229,1467712742442
07-05 11:59:02.438   969  1026 D PMS     : releaseWL(39b44679): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,07-05 11:59:02.448   969   969 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6526 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,07-05 11:59:02.448  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:59:02.448  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
07-05 11:59:02.448  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:59:02.448  6499  6499 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@131a4951(com.htc.providers.calendar.HtcCalendarProvider@2a2e15b6)
07-05 11:59:02.448  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:59:02.448  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:59:02.458  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.458  6499  6539 D CalendarProvider2: wait start:true
,07-05 11:59:02.468  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.468  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.468  6474  6495 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
07-05 11:59:02.468  6474  6495 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
,07-05 11:59:02.468  6474  6495 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:59:02.468  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:59:02.468  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
07-05 11:59:02.468  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.478   969  1681 D PMS     : acquireWL(20709c17): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1675 10052 null
07-05 11:59:02.468  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.478  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.478  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.478  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:59:02.478  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.478  6474  6495 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:59:02.478  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:59:02.478  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:59:02.478  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.488  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-05 11:59:02.498  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.498  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.498  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.498  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,07-05 11:59:02.498  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.498  6499  6539 D CalendarProvider2: wait end:false
,07-05 11:59:02.498  6526  6526 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 11:59:02.508  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-05 11:59:02.508  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.508  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.508  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:59:02.508  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.508  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.518  1675  6522 D CityCodeHelper: code_mapping get key: 349727
,07-05 11:59:02.518  5980  6498 D HtcAlertService: No fired or scheduled alerts,
07-05 11:59:02.518  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.518  5980  6498 D HtcAlertUtils: -- cancelReminderNotification --
07-05 11:59:02.518  5980  6498 D HtcAlertUtils: broadcastExistReminder!
,07-05 11:59:02.518  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.518  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.518  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.518  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.518  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-05 11:59:02.518  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 11:59:02.528  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 4
07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 1024
07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfo_proxy+
07-05 11:59:02.528  1675  6522 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 11:59:02.528   396  6553 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 1024
07-05 11:59:02.528   396  6553 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 11:59:02.528  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.528  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.528  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.528  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.528  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:59:02.528  5588  6496 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-05 11:59:02.538  1945  3968 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 11:59:02.548  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:59:02.548  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 11:59:02.548  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.548  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.548  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:59:02.548  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:59:02.548  2228  2228 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,07-05 11:59:02.568  6526  6551 I Task_Calendar: Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,07-05 11:59:02.568   969  1442 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6554 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,07-05 11:59:02.568  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,07-05 11:59:02.578  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-05 11:59:02.578  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac,
07-05 11:59:02.578  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.578  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:59:02.578  6526  6551 D TodoTaskshortcut: update TASK shortcut>
,07-05 11:59:02.588  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,07-05 11:59:02.588  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-05 11:59:02.588  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:59:02.588  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-05 11:59:02.588  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-05 11:59:02.588   396  6553 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,07-05 11:59:02.588  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-05 11:59:02.588   396  6553 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 11:59:02.598  1675  6522 D libc    : [NET] android_getaddrinfo_proxy-, success
07-05 11:59:02.598  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-05 11:59:02.598  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:59:02.598  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:59:02.598  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-05 11:59:02.608  6474  6495 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-05 11:59:02.608  6474  6495 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-05 11:59:02.608  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-05 11:59:02.608  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-05 11:59:02.608  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.618  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-05 11:59:02.618  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.618  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.618  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-05 11:59:02.618  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-05 11:59:02.618  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-05 11:59:02.618  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-05 11:59:02.628  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.628  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.628  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-05 11:59:02.628  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-05 11:59:02.628  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-05 11:59:02.628  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.638  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.638  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-05 11:59:02.638  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-05 11:59:02.638  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-05 11:59:02.638  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:59:02.638  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,07-05 11:59:02.648  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.648  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-05 11:59:02.648  6474  6495 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-05 11:59:02.648  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-05 11:59:02.648  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-05 11:59:02.648  3698  4143 I art     : Explicit concurrent mark sweep GC freed 4351(231KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1527KB/5MB, paused 599us total 37.933ms
,07-05 11:59:02.658  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-05 11:59:02.658  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.658  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-05 11:59:02.658  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,07-05 11:59:02.658  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-05 11:59:02.658  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-05 11:59:02.668  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-05 11:59:02.668  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-05 11:59:02.668  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-05 11:59:02.668  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-05 11:59:02.668  5588  6496 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
07-05 11:59:02.668  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-05 11:59:02.678  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-05 11:59:02.678  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-05 11:59:02.678  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-05 11:59:02.678  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-05 11:59:02.678   969  1706 D Process : killProcessQuiet, pid=5939,
07-05 11:59:02.678   969  1706 I ActivityManager: Killing 5939:com.google.android.talk/u0a112 (adj 15): empty #17
07-05 11:59:02.678   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:02.718  1675  6522 D WSP     : response code: 200
,07-05 11:59:02.738  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11
,07-05 11:59:02.758  1675  6522 D WSP     : response code: 200
,07-05 11:59:02.768   969   989 I ActivityManager: Recipient 5939
,07-05 11:59:02.788   969  1993 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,07-05 11:59:02.788  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-05 11:59:02.798  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
07-05 11:59:02.798  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-05 11:59:02.798  6474  6495 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-05 11:59:02.798  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-05 11:59:02.798  1675  6522 D WSP     : response code: 200
,07-05 11:59:02.808  6474  6495 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.808  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-05 11:59:02.808  6474  6495 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-05 11:59:02.808   969  1676 D Process : killProcessQuiet, pid=6239
07-05 11:59:02.808   969  1676 I ActivityManager: Killing 6239:com.htc.cs.dm/u0a99 (adj 15): empty #17
07-05 11:59:02.808   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:02.848  3202  3264 I HtcModeClient: handler message = 4011,
07-05 11:59:02.848  3202  3264 E HtcModeClient: Check connection and retry 8 times.
,07-05 11:59:02.848   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:59:02.848   969  6577 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=158 rxSum=148} preTxRxSum={txSum=132 rxSum=126},
07-05 11:59:02.848   969  6577 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
07-05 11:59:02.858   969  6577 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:02.918   969  2390 I ActivityManager: Recipient 6239
,07-05 11:59:02.938  1675  6522 D CityCodeHelper: code_mapping get key: 274663,
,07-05 11:59:02.958  1675  6522 D WSP     : response code: 200,
,07-05 11:59:02.968  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11
,07-05 11:59:02.978  6554  6579 I Gmail   : getAccountsCursor,
,07-05 11:59:02.978  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.008  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.138   969   988 I art     : Explicit concurrent mark sweep GC freed 17016(917KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.721ms total 183.645ms,
,07-05 11:59:03.148   969  1442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6554, uid=10106, userID:0
,07-05 11:59:03.148  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 11:59:03.148   969  4144 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 11:59:03.158   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,07-05 11:59:03.158   969   969 E WifiTrafficPoller:  packet count Tx=184 Rx=251
07-05 11:59:03.158  1339  1339 D WIFI_ICON: WifiActivity: 3
07-05 11:59:03.158   969   969 E WifiTrafficPoller: notifying of data activity 3
,07-05 11:59:03.158  1675  6522 D CityCodeHelper: code_mapping get key: 328328
,07-05 11:59:03.168  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,07-05 11:59:03.178   969   988 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-05 11:59:03.178  6554  6584 I Gmail   : Observing account changes for notifications
,07-05 11:59:03.178  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.178   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6554, uid=10106, userID:0
07-05 11:59:03.178   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6554, uid=10106, userID:0,
,07-05 11:59:03.188  6554  6554 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,07-05 11:59:03.188  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11,
,07-05 11:59:03.208   969  1276 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 11:59:03.208  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.228  6554  6589 E Gmail   : Error finding the version of the Email provider.....
07-05 11:59:03.228  6554  6589 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 11:59:03.228  6554  6589 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-05 11:59:03.228  6554  6589 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 11:59:03.228  6554  6589 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 11:59:03.228  6554  6591 I Gmail   : getAccountsCursor,
,07-05 11:59:03.238  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.238  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:03.248   969  1681 D PMS     : acquireWL(145ab907): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5588 10159 null
,07-05 11:59:03.278   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5588, uid=10159, userID:0
,07-05 11:59:03.288  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:03.298   969  1981 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6597 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,07-05 11:59:03.308   969  4144 D PMS     : releaseWL(145ab907): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,07-05 11:59:03.308  5588  6595 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 11:59:03.308  5588  6595 I MusicLeanback: Stop autocaching.
,07-05 11:59:03.328  5588  5588 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:59:03.338  5588  6615 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:59:03.338   969  1464 D Process : killProcessQuiet, pid=6263
07-05 11:59:03.338   969  1464 I ActivityManager: Killing 6263:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
07-05 11:59:03.338   969  1464 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:03.338  1675  6522 D CityCodeHelper: code_mapping get key: 623
,07-05 11:59:03.368  6554  6611 E SQLiteLog: (283) recovered 1942 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,07-05 11:59:03.368  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.378  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11
,07-05 11:59:03.388  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.418  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.438  6554  6617 I Gmail   : notifyAccountChanged,
,07-05 11:59:03.448  6554  6626 I Gmail   : getAccountsCursor
,07-05 11:59:03.448  6554  6617 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 11:59:03.458  6554  6617 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 11:59:03.458   969  1990 I ActivityManager: Recipient 6263
,07-05 11:59:03.468  6554  6617 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 11:59:03.468  6554  6617 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 11:59:03.488  6499  6499 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
07-05 11:59:03.488  6499  6499 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 11:59:03.548  6597  6597 D SyncApplication: Loading default preferences,
,07-05 11:59:03.558  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
07-05 11:59:03.568   969  1676 D Process : killProcessQuiet, pid=6093
07-05 11:59:03.568   969  1676 I ActivityManager: Killing 6093:com.android.settings/1000 (adj 15): empty #17
07-05 11:59:03.568   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:03.568  1675  6522 D CityCodeHelper: code_mapping get key: 307297
,07-05 11:59:03.588  6597  6597 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,07-05 11:59:03.588  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.598  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11
07-05 11:59:03.608   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
,07-05 11:59:03.608   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:03.608   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=7.7, 0.0, 0.0  rx=14.0 bcn=0 [on:0 tx:0 rx:0 period:2890] from screen [on:0 period:-1166071614] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:03.608   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:03.608   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=7.7, 0.0, 0.0  rx=14.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1166071611] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:03.608   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:03.608   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:03.608  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:03.608  1432  1432 I wpa_supplicant: environment dirty rate=0 [37][0][0]
07-05 11:59:03.608   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:03.608   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
07-05 11:59:03.608   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:03.618   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=22.34 txretriesrate=0.00 rxrate=22.01 userTriggerdPenalty0
,07-05 11:59:03.618   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:59:03.618   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:59:03.618   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-05 11:59:03.618  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.638   969   969 E WifiTrafficPoller: ADD_CLIENT: 8
07-05 11:59:03.638   969  1268 D WifiService: New client listening to asynchronous messages,
,07-05 11:59:03.648   969  1981 I ActivityManager: Recipient 6093,
,07-05 11:59:03.658  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.668  6597  6597 D SyncApplication: Overriding preferences with custom values,
,07-05 11:59:03.678   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:03.678   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3,
07-05 11:59:03.678  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:03.678  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,07-05 11:59:03.678  6597  6597 D SyncApplication: Updating preferences succeeded,
,07-05 11:59:03.688  6597  6597 E SyncApplication: Application created.,
,07-05 11:59:03.688  6597  6631 W VolumeInfo: Unable to read mount points
07-05 11:59:03.688  6597  6631 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	,at java.io.FileReader.<init>(FileReader.java:66)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
07-05 11:59:03.688  6597  6631 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-05 11:59:03.688  6597  6631 W VolumeInfo: 	... 13 more
07-05 11:59:03.688  6597  6631 V VolumeInfo: Found 0 mount point(s)
07-05 11:59:03.688  6597  6631 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,07-05 11:59:03.698  6597  6597 I CalendarDefines: getNewCalendarAuthority()...
,07-05 11:59:03.698   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6597, uid=10005, userID:0
07-05 11:59:03.698   969  1993 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,07-05 11:59:03.698  6597  6631 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
07-05 11:59:03.698   969   989 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6597, uid=10005, userID:0
,07-05 11:59:03.698  6597  6597 D SyncApplication: enableAppOperation()+
07-05 11:59:03.698   969   989 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,07-05 11:59:03.698  6597  6597 D SyncApplication: enableAppOperation()-
,07-05 11:59:03.698  6597  6597 D HTCUtilities: isNeorSinged() + 
,07-05 11:59:03.708  6597  6631 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,07-05 11:59:03.708  6597  6631 W VolumeInfo: Can not create volume ID for unmounted volume null
,07-05 11:59:03.718  6597  6597 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
,07-05 11:59:03.718  6597  6597 D HTCUtilities: isNeorSinged() return false
,07-05 11:59:03.728  1675  6522 D CityCodeHelper: code_mapping get key: 213490,
,07-05 11:59:03.738  6597  6597 D CDMountReceiver: whether to enable CD Auto-mount: true,
07-05 11:59:03.738  6597  6597 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm,
,07-05 11:59:03.738  6597  6597 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,07-05 11:59:03.748  1675  6522 D WSP     : response code: 200,
,07-05 11:59:03.768  1443  1462 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true, isForDotMatrix: false,
07-05 11:59:03.768  1675  6522 D WSP JsonParser: sync status: same time, sync all, 11,11
,07-05 11:59:03.768  6554  6626 I Gmail   : master sync=false, engine sync=true
07-05 11:59:03.768  6597  6597 D CDMountReceiver: enable CD Auto-mount: true
07-05 11:59:03.778  1675  6522 D WSP     : response code: 200
07-05 11:59:03.778  1945  4441 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 11:59:03.788  1945  1945 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 11:59:03.788  6597  6634 D HTCUtilities: enable auto-mount
07-05 11:59:03.788  6597  6635 D HTCUtilities: enable auto-mount
,07-05 11:59:03.798  6597  6634 I HtcMountManagerAdapter: mHtcMountManager is  null
07-05 11:59:03.798  6597  6635 I HtcMountManagerAdapter: mHtcMountManager is  null
07-05 11:59:03.798  6597  6635 I HtcMountManagerAdapter: mStorageManager is  not null
07-05 11:59:03.798  1339  1339 I RemoteViews: apply : com.nero.android.htc.sync 1 14 6 38
,07-05 11:59:03.798  6597  6634 I HtcMountManagerAdapter: mStorageManager is  not null
07-05 11:59:03.798  2228  2228 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 11:59:03.798   969  1442 D VoldConnector: SND -> {30 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
07-05 11:59:03.798   969  1990 D VoldConnector: SND -> {29 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,07-05 11:59:03.808  1675  6522 D WSP     : response code: 200
,07-05 11:59:03.808   969  1442 D MountService: mountISO: /system/etc/PCTOOL.ISO
07-05 11:59:03.808   969  1990 D MountService: mountISO: /system/etc/PCTOOL.ISO
07-05 11:59:03.808   969  1981 D Process : killProcessQuiet, pid=6164
07-05 11:59:03.808   969  1981 I ActivityManager: Killing 6164:com.google.android.gms:car/u0a24 (adj 15): empty #17
,07-05 11:59:03.808   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 11:59:03.808  1339  1339 I RemoteViews: apply : com.nero.android.htc.sync 0 14 3 53
,07-05 11:59:03.818  1842  6636 E MDM     : [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:59:03.898   969  4144 I ActivityManager: Recipient 6164
,07-05 11:59:03.928   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2228, uid=10024, userID:0,
,07-05 11:59:03.948  2228  6637 D LocationInitializer: Restart initialization of location
,07-05 11:59:03.958   969   969 E WifiStateMachine: WiFiStateMachine SCAN ALARM
07-05 11:59:03.958   969   969 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:59:03.958   969   969 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:59:03.958   969   969 D WifiDisplayAdapter:     GroupId: 
07-05 11:59:03.958   969   969 D WifiDisplayAdapter:     Passphrase: 
07-05 11:59:03.958   969   969 D WifiDisplayAdapter:     SessionId: 0,
07-05 11:59:03.958   969   969 D WifiDisplayAdapter:     IP Address: }
07-05 11:59:03.958   969  1267 E WifiStateMachine: handleMessage: E msg.what=131143
,07-05 11:59:03.958   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:03.958   969  1267 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):1 dur:2177 rssi=-55 f=2447 sc=60 link=150 tx=22.3, 0.0, 0.0  rx=22.0 fiv=60000 [on:0 tx:0 rx:0 period:282] from screen [on:0 period:-1166071263]
07-05 11:59:03.958   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:03.958   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):3 dur:2177 rssi=-55 f=2447 sc=60 link=150 tx=22.3, 0.0, 0.0  rx=22.0 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166071262]
,07-05 11:59:03.958   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.34 rxSuccessRate=22.01 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-55
07-05 11:59:03.958   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=8941 interval=60000 maxinterval=300000
07-05 11:59:03.958   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
07-05 11:59:03.958   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
07-05 11:59:03.958   969  1267 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
07-05 11:59:03.958   969  1267 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2447 age=347 ?=true
07-05 11:59:03.958   969  1267 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
07-05 11:59:03.958   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2447"
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2447'
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-05 11:59:03.958  1432  1432 I wpa_supplicant: wpa_supplicant_scan enter
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Request Type
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Config Methods (4288)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * UUID-E
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Primary Device Type
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * RF Bands (3)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Association State
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Configuration Error (0)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Device Password ID (0)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Manufacturer
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Model Name
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Model Number
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Device Name
07-05 11:59:03.958  1432  1432 D wpa_supplicant: WPS:  * Version2 (0x20)
07-05 11:59:03.958  1432  1432 D wpa_supplicant: P2P: * P2P IE header
07-05 11:59:03.958  1432  1432 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-05 11:59:03.958  1432  1432 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Limit manual scan to specified channels
,07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55baf59aa0
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55baf59aa0 after 0.000060 second wait
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: nl80211: scan request
07-05 11:59:03.958  1432  1432 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 11:59:03.958  1432  1432 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
,07-05 11:59:03.958  1432  1432 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000131 seconds
07-05 11:59:03.958  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-05 11:59:03.958   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-05 11:59:03.958   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-05 11:59:03.958   969  1788 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-05 11:59:03.958   969  1788 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-05 11:59:03.958   969  1267 E WifiStateMachine: [1,467,712,743,973 ms] noteScanstart no scan source
07-05 11:59:03.958   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:03.978   969   969 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6639 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-05 11:59:03.988   969   969 D PMS     : releaseWL(277923d6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
07-05 11:59:03.988  1945  1945 I ConfigService: onDestroy
,07-05 11:59:03.998  6554  6652 I Gmail   : getAccountsCursor
,07-05 11:59:04.008  6554  6652 I Gmail   : master sync=false, engine sync=true
,07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: nl80211: New scan results available
07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Scan included frequencies: 2447
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
07-05 11:59:04.028  1432  1432 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: Scan completed in 0.068223 seconds
07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Associated on 2447 MHz
07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Received scan results (9 BSSes)
07-05 11:59:04.028  1432  1432 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2447 level=-52
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-55
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-65
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-65
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 00:1a:ef:42:f2:b0 freq=2412 level=-77
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 00:16:a6:1f:06:5c freq=2462 level=-79
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 00:fe:c8:73:02:02 freq=2462 level=-89
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-86
07-05 11:59:04.028  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:12:64:93 freq=2412 level=-87
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: BSS: Start scan result update 4
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: BSS: Add new id 8 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST'
07-05 11:59:04.028  1432  1432 D wpa_supplicant: BSS: last_scan_res_used=9/32
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: Scan-only results received
07-05 11:59:04.028  1432  1432 D wpa_supplicant: wlan0: Radio work 'scan'@0x55baf59aa0 done in 0.069446 seconds
07-05 11:59:04.028   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 f0:f2:6d:22:99:3e]
07-05 11:59:04.028   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-05 11:59:04.028   969  1788 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-05 11:59:04.028   969  1267 E WifiStateMachine: handleMessage: E msg.what=147461
07-05 11:59:04.028   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:04.028   969  1267 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-05 11:59:04.028   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:04.028   969  1267 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-05 11:59:04.028   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:59:04.028   969  1267 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-05 11:59:04.028   969  1267 E WifiStateMachine: processMsg: DriverStartedState
07-05 11:59:04.028   969  1267 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-05 11:59:04.028   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
07-05 11:59:04.038   969  1267 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-05 11:59:04.038   969  1267 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
07-05 11:59:04.038   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
07-05 11:59:04.038  1432  1432 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,07-05 11:59:04.038   969  1267 E WifiStateMachine: [1,467,712,744,048 ms] noteScanEnd no scan source
07-05 11:59:04.038   969  1267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14202 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14367 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8128 
07-05 11:59:04.038   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
07-05 11:59:04.038  1432  1432 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,07-05 11:59:04.038   969  1267 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@338ae233 sup_state=COMPLETED debouncing=false
,07-05 11:59:04.038   969  1267 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
07-05 11:59:04.038   969  1267 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
07-05 11:59:04.038   969  1267 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2447
07-05 11:59:04.038   969  1267 E WifiAutoJoinController :  00:16:a6:1f:06:5c rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
,07-05 11:59:04.038   969  1267 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-65 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-65 cap [WPA2-EAP-TKIP][ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : Conrad_AP 00:1a:ef:42:f2:b0 rssi=-77 cap [WPA-PSK-CCMP][WPS][ESS] is not scored
,07-05 11:59:04.038   969  1267 E WifiAutoJoinController :  00:fe:c8:73:02:02 rssi=-89 cap [WPA2-PSK-CCMP][ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-86 cap [ESS] is not scored
,07-05 11:59:04.038   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:12:64:93 rssi=-87 cap [ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-52 cap [WPA2-PSK-CCMP][ESS] is not scored
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 9 now 1467712744055
07-05 11:59:04.038   969  1267 E WifiAutoJoinController : newSupplicantResults size=9 known=1 true
,07-05 11:59:04.038   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
07-05 11:59:04.048  1432  1432 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
,07-05 11:59:04.048   969  1267 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : ssid=NG700
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : id=0
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : mode=station
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : pairwise_cipher=CCMP,
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : group_cipher=CCMP
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : key_mgmt=WPA2-PSK
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : wpa_state=COMPLETED
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : ip_address=192.168.1.107
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-55 freq=2447 Current: f4:f2:6d:22:99:3e
07-05 11:59:04.048   969  1267 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
07-05 11:59:04.048   969  1267 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 11:59:04.048   969  1267 E WifiAutoJoinController : Done attemptAutoJoin status=0
07-05 11:59:04.048   969  1267 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
07-05 11:59:04.048   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:04.058  6639  6639 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 11:59:04.098  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:59:04.158   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:04.158   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=271
,07-05 11:59:04.218  6639  6666 I Babel_SMS: MmsConfig: mnc/mcc: 0/0,
,07-05 11:59:04.218  6639  6666 I Babel_SMS: MmsConfig.loadMmsSettings,
,07-05 11:59:04.248   969  2390 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6669 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,07-05 11:59:04.258   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6639, uid=10112, userID:0,
,07-05 11:59:04.258   411   411 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 295us total 21.789ms
,07-05 11:59:04.278   411   411 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 262us total 18.077ms
,07-05 11:59:04.298   411   411 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 263us total 17.114ms,
,07-05 11:59:04.318  6669  6669 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,07-05 11:59:04.318  6669  6669 D MessageFrequencyProvider: onCreate,
07-05 11:59:04.318  6639  6639 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 11:59:04.328  6669  6669 V GetPrviateResource: GetPrviateResource
,07-05 11:59:04.328  6669  6669 V GetPrviateResource: GetPrviateResource
,07-05 11:59:04.328  6669  6689 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string,
07-05 11:59:04.328  6639  6639 I Babel_Crash: startup - clean
,07-05 11:59:04.328  6669  6669 D MessageCustFlag: sense_version=6.0
07-05 11:59:04.338  6669  6669 D BTAccessoryUtil: createReceiver
,07-05 11:59:04.338  6669  6669 D BTAccessoryUtil: registerReceiver return intent = null,
,07-05 11:59:04.338  6669  6688 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile,
07-05 11:59:04.338  6669  6669 D MessageCustFlag: sku_id=118
,07-05 11:59:04.338  6639  6666 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
07-05 11:59:04.338  6639  6693 I Babel   : deleted: false for 0
07-05 11:59:04.338  6639  6666 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 11:59:04.338  6669  6669 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
,07-05 11:59:04.348  6669  6669 W SystemReader: Cannot find qct_8960_interface, use default value instead
,07-05 11:59:04.348  6639  6666 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc ,
07-05 11:59:04.348  6639  6666 I Babel_SMS: MmsConfig.loadFromResources
,07-05 11:59:04.348  6639  6666 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 11:59:04.348  6639  6666 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,07-05 11:59:04.368   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,07-05 11:59:04.368   969  1990 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0,
,07-05 11:59:04.368   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,07-05 11:59:04.368   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,07-05 11:59:04.368   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6639, uid=10112, userID:0,
,07-05 11:59:04.378   969   989 D PMS     : acquireWL(3e1903a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6639 10112 null,
,07-05 11:59:04.398  1623  1623 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED,
07-05 11:59:04.398  1623  1623 I ContextualWidget: package com.google.android.gms changed
07-05 11:59:04.398  6639  6639 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 11:59:04.398  1675  6695 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-05 11:59:04.398  1675  6695 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-05 11:59:04.398  1623  1875 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
07-05 11:59:04.398  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 11:59:04.398  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-05 11:59:04.408  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-05 11:59:04.408  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 11:59:04.408  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 11:59:04.408  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-05 11:59:04.408  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:59:04.408  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
,07-05 11:59:04.408  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:59:04.428   969  2390 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6697 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 11:59:04.508  6639  6639 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,07-05 11:59:04.528  6639  6639 W Utils   : could not parse size range '64x64-1920X1080',
,07-05 11:59:04.528  6639  6639 W AudioCapabilities: Unsupported mime audio/qcelp,
,07-05 11:59:04.528  6639  6639 W AudioCapabilities: Unsupported mime audio/x-ms-wma,
,07-05 11:59:04.528  6639  6639 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 11:59:04.538  6639  6639 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,07-05 11:59:04.548  6697  6697 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
,07-05 11:59:04.578  6697  6697 V Settings:HtcSettingsApplication: [6697/6697] onCreate(),
,07-05 11:59:04.588   969  1276 I ActivityManager: Killing 6293:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
07-05 11:59:04.588   969  1276 D Process : killProcessQuiet, pid=6293,
07-05 11:59:04.588   969  1276 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:59:04.588  1623  1875 I ContextualWidget: MFU.onDataSetChanged
,07-05 11:59:04.588  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-05 11:59:04.588  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-05 11:59:04.598  6639  6639 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,07-05 11:59:04.618  6639  6639 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-05 11:59:04.618  6639  6639 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-05 11:59:04.628  6639  6639 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-05 11:59:04.638  6639  6639 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-05 11:59:04.648  6697  6721 D Settings:HtcWirelessFeatureFlags: id/is att sku: 118/false,
,07-05 11:59:04.688  1623  1875 I ContextualWidget: MFU.onLoadComplete
,07-05 11:59:04.688  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
,07-05 11:59:04.688  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 11:59:04.688  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
,07-05 11:59:04.688  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:59:04.688  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 11:59:04.688  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:59:04.708  6697  6721 E Settings:HtcWrapHeaderInfo: no such activity!
,07-05 11:59:04.718  6697  6720 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
,07-05 11:59:04.718  6697  6720 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true,
,07-05 11:59:04.738  6697  6720 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
07-05 11:59:04.738   969  1676 I ActivityManager: Recipient 6293
,07-05 11:59:04.808  2228  6723 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 11:59:04.808  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-05 11:59:04.808  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-05 11:59:04.808  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:59:04.818  6697  6720 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-05 11:59:04.828  2228  6723 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-05 11:59:04.838   969  2390 D PMS     : acquireWL(31e5ec92): PARTIAL_WAKE_LOCK  AsyncService 0x1 6195 10167 null,
07-05 11:59:04.838   969  1681 D PMS     : acquireWL(17e66663): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:04.848   969  1442 D PMS     : releaseWL(31e5ec92): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-05 11:59:04.848   969  2390 D PMS     : acquireWL(b99a319): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6195 10167 null
,07-05 11:59:04.858  2228  4461 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-05 11:59:04.868   969  1681 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
,07-05 11:59:04.868  6697  6720 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
07-05 11:59:04.868  6697  6720 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-05 11:59:04.878  6039  6729 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 11:59:04.878  6697  6719 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
07-05 11:59:04.878  6697  6719 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-05 11:59:04.888  6697  6719 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
,07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true,
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false,
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:59:04.888  6697  6719 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
07-05 11:59:04.888  1945  5237 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 11:59:04.898  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 11:59:04.898  2228  2228 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
07-05 11:59:04.898   969  1442 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi,
07-05 11:59:04.898  6697  6719 E ActivityThread: Failed to find provider info for com.htc.vowifi
07-05 11:59:04.898  6697  6719 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
07-05 11:59:04.908   969  1276 D PMS     : releaseWL(17e66663): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:04.908  6639  6639 I vclib   : onServiceConnected
,07-05 11:59:04.908  6639  6639 W Babel   : Attempted to change video mute state without an active call.
,07-05 11:59:04.928   969  1993 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6731 uid=10035 gids={50035, 9997} abi=arm64-v8a
,07-05 11:59:04.928   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:59:04.928   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:59:04.928   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0,
07-05 11:59:04.928   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
07-05 11:59:04.928   969   989 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:59:04.938   969  2390 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:59:04.938   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=6195, uid=10167, userID:0,
07-05 11:59:04.938   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:59:04.938   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=6195, uid=10167, userID:0
,07-05 11:59:04.948  6639  6639 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 11:59:04.948  6639  6639 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:59:04.968  6039  6729 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 89 ms] updated apps [took 89 ms] 
,07-05 11:59:04.978  6639  6639 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-05 11:59:04.988   969  1993 D Process : killProcessQuiet, pid=6069
07-05 11:59:04.988   969  1993 I ActivityManager: Killing 6069:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,07-05 11:59:04.988   969  1993 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 11:59:05.038   969  1276 I ActivityManager: Recipient 6069
,07-05 11:59:05.038  6639  6639 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 11:59:05.038  6639  6639 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:59:05.078   969   988 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=6757 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
07-05 11:59:05.088   969  1990 I art     : Explicit concurrent mark sweep GC freed 15628(828KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.175ms total 177.338ms
07-05 11:59:05.088   969  1990 D PMS     : acquireWL(2db1edb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:05.088   969  1676 D PMS     : releaseWL(3e1903a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-05 11:59:05.088   969  4144 D PMS     : releaseWL(b99a319): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-05 11:59:05.098   410   410 I art     : Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 153us total 20.985ms,
,07-05 11:59:05.108   969  1981 D Process : killProcessQuiet, pid=6361
07-05 11:59:05.108   969  1981 I ActivityManager: Killing 6361:com.google.android.configupdater/u0a98 (adj 15): empty #17
07-05 11:59:05.108   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:05.108   969  1758 D PMS     : releaseWL(2db1edb7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:05.118   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 164us total 16.068ms
,07-05 11:59:05.128   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 129us total 15.284ms
,07-05 11:59:05.158   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:05.168   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=272
07-05 11:59:05.168   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:05.168  1339  1339 D WIFI_ICON: WifiActivity: 1
,07-05 11:59:05.168  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
,07-05 11:59:05.238   969   988 I ActivityManager: Recipient 6361
,07-05 11:59:05.338  6006  6396 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 11:59:05.368  5980  5980 D ProviderChangeReceiver: ---------------------------------------------------
,07-05 11:59:05.368  5980  5980 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-05 11:59:05.368  5980  6788 D HtcAlertService: start to updateAlertNotification!
,07-05 11:59:05.388  6757  6785 D WeatherUtility: Weather sync is On
,07-05 11:59:05.398  5980  6788 D HtcAlertService: No fired or scheduled alerts
,07-05 11:59:05.398  5980  6788 D HtcAlertUtils: -- cancelReminderNotification --
,07-05 11:59:05.398  5980  6788 D HtcAlertUtils: broadcastExistReminder!
,07-05 11:59:05.398  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 11:59:05.418  6757  6785 W WeatherRequest: request cur loc, but there is no sys cur
07-05 11:59:05.418  6757  6785 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 11:59:05.428  6757  6785 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,07-05 11:59:05.438  1623  1623 I RemoteViews: reapply : com.htc.widget.weatherclock 6 17,
,07-05 11:59:05.448  6757  6794 D WeatherUtility: Weather sync is On,
,07-05 11:59:05.468  6757  6794 W WeatherRequest: request cur loc, but there is no sys cur,
07-05 11:59:05.468  6757  6794 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,07-05 11:59:05.478  1623  1623 I RemoteViews: reapply : com.htc.widget.weatherclock 5 17,
,07-05 11:59:06.168   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:06.168   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=272
07-05 11:59:06.168  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:06.168   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:59:06.168  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:06.348  6669  6669 D Messaging: supportCMAS(SIE)/init? false/true
,07-05 11:59:06.348  6669  6669 D MmsConfig: networkCode: 
07-05 11:59:06.348  6669  6669 D MessageCustFlag: sku_id=118
,07-05 11:59:06.348  6669  6669 D MmsConfig: SIE smsPri: null
07-05 11:59:06.348  6669  6669 D MmsConfig: networkCode: 
,07-05 11:59:06.358  6669  6796 D Messaging: mNeedToUpdateDate2 start,
07-05 11:59:06.358  6669  6669 D MmsConfig: packageName: com.htc.vvm.att does not exist
,07-05 11:59:06.358  6669  6669 D ReportIndicatorCache: startAsyncQueryReports ---
,07-05 11:59:06.358  6669  6690 D MmsAsyncWorkHandler: 
07-05 11:59:06.358  6669  6690 D MmsAsyncWorkHandler: HM tk = 20001
07-05 11:59:06.358  6669  6690 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,07-05 11:59:06.358  6669  6669 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2a2e15b6
,07-05 11:59:06.368  1572  1620 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
07-05 11:59:06.368  1572  1620 D MmsSmsV2Provider:  slotId = -1000
07-05 11:59:06.368  1572  1620 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,07-05 11:59:06.368  6669  6669 D DraftCache: [DraftCache/1] DraftCache.constructor
,07-05 11:59:06.368  6669  6669 D DraftCache: [DraftCache/1] refresh
,07-05 11:59:06.368  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
,07-05 11:59:06.368  1572  4141 D MmsSmsV2Provider:  slotId = -1000
,07-05 11:59:06.368  1572  4141 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,07-05 11:59:06.378  6669  6669 D MmsConfig: networkCode: 
,07-05 11:59:06.378  6669  6798 I Messaging: mccmnc> 
,07-05 11:59:06.388  1572  2192 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
,07-05 11:59:06.388  1572  2192 D AccFlag : sku_id=118
,07-05 11:59:06.388  6669  6800 D Messaging: ViewCache CreatePreloadOnlyConversationList,
,07-05 11:59:06.388  1572  1638 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
07-05 11:59:06.388  1572  1638 D MmsSmsV2Provider:  slotId = -1000
07-05 11:59:06.388  1572  1638 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,07-05 11:59:06.388  6669  6690 D DraftCache: [DraftCache/206] rebuildCache
,07-05 11:59:06.398  6669  6797 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
07-05 11:59:06.398  1572  1620 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
07-05 11:59:06.398  1572  1620 D MmsSmsV2Provider:  slotId = -1000
07-05 11:59:06.398  1572  1620 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,07-05 11:59:06.408  6669  6796 D Messaging: mNeedToUpdateDate2: false,
,07-05 11:59:06.418  6669  6669 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1,
07-05 11:59:06.418  6669  6669 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
07-05 11:59:06.418  6669  6669 D PhoneStorageUtil: createReceiver
,07-05 11:59:06.428  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95,
,07-05 11:59:06.428  1572  4141 D Jerry   : URI_DRAFT,
,07-05 11:59:06.428  6669  6690 D DraftCache: hasDraft() = false mNeedNotifyChange = true
,07-05 11:59:06.438  6669  6690 D DraftCache: [DraftCache/206] rebuildCache time: 13
07-05 11:59:06.438  6669  6690 D MmsAsyncWorkHandler: 
07-05 11:59:06.438  6669  6690 D MmsAsyncWorkHandler: HM tk = 20002
,07-05 11:59:06.438  6669  6800 D MessageCustFlag: sense_version=6.0,
07-05 11:59:06.438  6669  6800 D Jerry   : start to preload cursor >>>>>>>
,07-05 11:59:06.438  1572  2193 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81,
,07-05 11:59:06.438  1572  2193 D AccFlag : sku_id=118,
07-05 11:59:06.448  1572  1620 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,07-05 11:59:06.448  1572  1620 V MmsProvider: Update uri=content://mms, match=0
07-05 11:59:06.448  1572  1620 V MmsProvider: selection=st=129 AND m_type!=134
07-05 11:59:06.448  6669  6802 D Messaging: Reset downloading state: 0
,07-05 11:59:06.448  6669  6802 V MmsSystemEventReceiver: TransactionService is going to be woken up.,
,07-05 11:59:06.448  1572  4141 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
07-05 11:59:06.448  1572  4141 D MmsSmsV2Provider:  slotId = -1000
,07-05 11:59:06.458  6669  6669 V TransactionService: 1-Creating TransactionService
,07-05 11:59:06.458  1572  2193 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
07-05 11:59:06.468   969  1028 I ActivityManager: Waited long enough for: ServiceRecord{67d8335 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService}
07-05 11:59:06.468  1572  2193 D AccFlag : sku_id=118
,07-05 11:59:06.468  6669  6800 D Messaging: ViewCache CreatePreload
07-05 11:59:06.468  6669  6800 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,07-05 11:59:06.468  6669  6669 V TransactionService: onStartCommand: 1,
07-05 11:59:06.468  6669  6669 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,07-05 11:59:06.478  6669  6803 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-05 11:59:06.478  6669  6803 V TransactionService: Loading previous transactions.
,07-05 11:59:06.488  1572  2192 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80,
,07-05 11:59:06.488  1572  2192 D AccFlag : device_type: 1,
,07-05 11:59:06.488  6669  6800 D Cust_MMSMS: _has_set_default_values_2=true
,07-05 11:59:06.488  6669  6800 D MsgPreferenceUtils: def_index: 0
,07-05 11:59:06.488  6669  6803 D TransactionService: Force clearing mTransactionList
,07-05 11:59:06.488  6669  6803 D TransactionService: Force set service start id to 1
07-05 11:59:06.488  6669  6803 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
,07-05 11:59:06.488  6669  6803 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,07-05 11:59:06.488  6669  6669 V TransactionService: Destroying TransactionService
07-05 11:59:06.488  6669  6803 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,07-05 11:59:06.488  6669  6800 D MsgPreferenceUtils: globalIndex = 1
07-05 11:59:06.498   969  1993 I ActivityManager: Killing 6006:com.google.android.apps.photos/u0a197 (adj 15): empty #17
,07-05 11:59:06.498   969  1993 D Process : killProcessQuiet, pid=6006
07-05 11:59:06.498   969  1993 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:06.498  6669  6800 D MsgPreferenceUtils: phone state: true
07-05 11:59:06.498  6669  6800 D MsgPreferenceUtils: sd state: false
07-05 11:59:06.498  6669  6800 D MsgPreferenceUtils: vIndex = 0
,07-05 11:59:06.618   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
,07-05 11:59:06.618   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:06.618   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=22.3, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:2658] from screen [on:0 period:-1166068600] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:06.618   969  1990 I ActivityManager: Recipient 6006,
07-05 11:59:06.618   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:06.618   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=22.3, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166068598] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:06.618   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:06.618   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:06.618  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:06.638  1432  1432 I wpa_supplicant: environment dirty rate=0 [9][0][0],
07-05 11:59:06.638   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:06.638   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
07-05 11:59:06.638   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
07-05 11:59:06.638   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=15.67 txretriesrate=0.00 rxrate=16.01 userTriggerdPenalty0
07-05 11:59:06.638   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:59:06.638   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:59:06.638   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-05 11:59:06.708  6669  6803 V TransactionService: 4-Handling incoming message: { when=-212ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,07-05 11:59:06.708   969  1267 E WifiStateMachine: handleMessage: X,
07-05 11:59:06.708   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
,07-05 11:59:06.718  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3,
07-05 11:59:06.718  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:07.068  5543  6820 W SystemReader: Cannot find support_china_sense_feature, use default value instead,
,07-05 11:59:07.098  3073  3093 W FeatureConfig: mIsRawPhotoSupported:false,
,07-05 11:59:07.108  5543  6820 W MediaManager: [DualLensScanUtil],	mmpCursor count is 0
,07-05 11:59:07.118   969  1706 D Process : killProcessQuiet, pid=6451,
07-05 11:59:07.118   969  1706 I ActivityManager: Killing 6451:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
07-05 11:59:07.118   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:07.168   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:07.168   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=272
,07-05 11:59:07.218   969  4144 I ActivityManager: Recipient 6451
,07-05 11:59:07.238   969  1028 I ActivityManager: Waited long enough for: ServiceRecord{2a56be17 u0 com.htc.musicenhancer/.EnhancerService}
,07-05 11:59:07.848   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:59:07.858   969  6824 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=158 rxSum=148}
07-05 11:59:07.858   969  6824 D WifiDataStallTracker: updateDataStallInfo: IN/OUT,
07-05 11:59:07.858   969  6824 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:07.868  3202  3264 I HtcModeClient: handler message = 4011,
07-05 11:59:07.868  3202  3264 E HtcModeClient: Check connection and retry 9 times.
,07-05 11:59:08.168   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:08.168  1339  1339 D WIFI_ICON: WifiActivity: 1
,07-05 11:59:08.168   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=273
07-05 11:59:08.168  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:08.168   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:08.178   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:59:08.198  6554  6585 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 11:59:08.828   969  1981 D Process : killProcessQuiet, pid=6474
07-05 11:59:08.828   969  1981 I ActivityManager: Killing 6474:com.htc.sdm/u0a79 (adj 15): empty #17
07-05 11:59:08.828   969  1981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:08.928   969  1681 I ActivityManager: Recipient 6474
,07-05 11:59:08.988   969  1464 D Process : killProcessQuiet, pid=6499
07-05 11:59:08.988   969  1464 I ActivityManager: Killing 6499:com.htc.bgp/u0a11 (adj 15): empty #17
,07-05 11:59:08.988   969  1464 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:09.078   969  4144 I ActivityManager: Recipient 6499
,07-05 11:59:09.178   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:09.178   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=273
07-05 11:59:09.178  1339  1339 D WIFI_ICON: WifiActivity: 0
,07-05 11:59:09.178   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:59:09.178  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:09.638   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155,
07-05 11:59:09.638   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:09.638   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=15.7, 0.0, 0.0  rx=16.0 bcn=0 [on:0 tx:0 rx:0 period:2931] from screen [on:0 period:-1166065578] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:09.638   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:09.648   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=15.7, 0.0, 0.0  rx=16.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166065576] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:09.648   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:09.648   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:09.648  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:09.658  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,07-05 11:59:09.658   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:09.658   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
07-05 11:59:09.658   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:09.658   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.84 txretriesrate=0.00 rxrate=8.50 userTriggerdPenalty0
07-05 11:59:09.658   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:09.658  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:09.658   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 11:59:09.668  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:09.658   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=65
07-05 11:59:09.658   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
07-05 11:59:09.668   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:09.838   969  1256 D PMS     : acquireWL(16645e8f): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000},
07-05 11:59:09.838   969  1256 V AlarmManager: sending alarm PendingIntent{f26051c: PendingIntentRecord{1866e525 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=86265, Int=0
,07-05 11:59:09.848   969   969 D PMS     : releaseWL(16645e8f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,07-05 11:59:10.058   969  1080 W PackageSettings: Skipping PackageSetting{27f7ce59 com.example.hello/10374} due to missing metadata
,07-05 11:59:10.108   969  1758 D Process : killProcessQuiet, pid=6526
07-05 11:59:10.108   969  1758 I ActivityManager: Killing 6526:com.htc.task/u0a69 (adj 15): empty #17
07-05 11:59:10.108   969  1758 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:10.178   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:10.178   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=273
,07-05 11:59:10.188   969   989 I ActivityManager: Recipient 6526
,07-05 11:59:11.178   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:11.178  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:59:11.178   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=274
07-05 11:59:11.188  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-05 11:59:11.178   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:11.958   969  1267 E WifiStateMachine: handleMessage: E msg.what=131326
07-05 11:59:11.958   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:11.958   969  1267 E WifiStateMachine:  ConnectedState !what:131326 1 0
,07-05 11:59:11.958   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:11.958   969  1267 E WifiStateMachine:  L2ConnectedState !what:131326 1 0
07-05 11:59:11.958   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:12.188   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:12.188  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:12.188   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=274
07-05 11:59:12.188  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:12.188   969   969 E WifiTrafficPoller: notifying of data activity 0
,07-05 11:59:12.658   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:12.668   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:12.668   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=7.8, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1166062556] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 11:59:12.668   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:12.668   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=7.8, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166062554] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 11:59:12.668   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:12.668   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:12.668  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:12.678  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:12.678   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:12.678   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=150
07-05 11:59:12.678   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:12.678   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=3.92 txretriesrate=0.00 rxrate=4.75 userTriggerdPenalty0
07-05 11:59:12.678   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:12.688  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
,07-05 11:59:12.688   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:12.688  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:12.688   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:12.688   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:12.688   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -55, 3
,07-05 11:59:12.768  1675  1855 D AutoSetting: service - handleMessage() stop self
,07-05 11:59:12.788  1675  1855 D AutoSetting: service - handleMessage() quit looper
,07-05 11:59:12.788  1675  1675 D AutoSetting: service - onDestroy() END
,07-05 11:59:12.848   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:59:12.858   969  6827 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173}
,07-05 11:59:12.858   969  6827 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:12.858   969  6827 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,07-05 11:59:12.888  3202  3264 I HtcModeClient: handler message = 4011,
07-05 11:59:12.888  3202  3264 E HtcModeClient: Check connection and retry 10 times.
,07-05 11:59:13.188   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:13.188   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=274
,07-05 11:59:13.598   969  1256 D PMS     : acquireWL(75254ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072},
,07-05 11:59:13.598   969   969 E WifiStateMachine: WiFiStateMachine SCAN ALARM
,07-05 11:59:13.598   969  1256 V AlarmManager: sending alarm PendingIntent{1b1c5708: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712753602, Int=0
07-05 11:59:13.598   969  1267 E WifiStateMachine: handleMessage: E msg.what=131143
07-05 11:59:13.598   969  1256 V AlarmManager: sending alarm PendingIntent{68ad6ae: PendingIntentRecord{f1a9c4f android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1467712753080, Int=20000
07-05 11:59:13.598   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:13.598   969   969 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:59:13.598   969   969 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:59:13.598   969   969 D WifiDisplayAdapter:     GroupId: 
07-05 11:59:13.598   969   969 D WifiDisplayAdapter:     Passphrase: 
07-05 11:59:13.598   969   969 D WifiDisplayAdapter:     SessionId: 0
07-05 11:59:13.598   969   969 D WifiDisplayAdapter:     IP Address: }
07-05 11:59:13.608   969  1267 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:75 rssi=-55 f=2447 sc=60 link=150 tx=3.9, 0.0, 0.0  rx=4.8 list=2447 [on:0 tx:0 rx:0 period:919] from screen [on:0 period:-1166061616]
07-05 11:59:13.608   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:13.608   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):4 dur:75 rssi=-55 f=2447 sc=60 link=150 tx=3.9, 0.0, 0.0  rx=4.8 list=2447 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166061614]
07-05 11:59:13.608   969   969 D PMS     : releaseWL(75254ab): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
07-05 11:59:13.608   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.92 rxSuccessRate=4.75 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-55
07-05 11:59:13.608   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=18589 interval=60000 maxinterval=300000
07-05 11:59:13.608   969  1267 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
,07-05 11:59:13.608   969  1267 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
,07-05 11:59:13.608   969  1267 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2447 age=926 ?=true
07-05 11:59:13.608   969  1267 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,07-05 11:59:13.608   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2447"
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2447'
,07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-05 11:59:13.608  1432  1432 I wpa_supplicant: wpa_supplicant_scan enter
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Request Type
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Config Methods (4288)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * UUID-E
,07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Primary Device Type
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * RF Bands (3)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Association State
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Configuration Error (0)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Device Password ID (0)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Manufacturer
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Model Name
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Model Number
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Device Name
07-05 11:59:13.608  1432  1432 D wpa_supplicant: WPS:  * Version2 (0x20)
07-05 11:59:13.608  1432  1432 D wpa_supplicant: P2P: * P2P IE header
,07-05 11:59:13.608  1432  1432 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-05 11:59:13.608  1432  1432 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Limit manual scan to specified channels
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55baf59aa0
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55baf59aa0 after 0.000052 second wait
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: nl80211: scan request
07-05 11:59:13.608  1432  1432 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 11:59:13.608  1432  1432 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
,07-05 11:59:13.608  1432  1432 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000135 seconds
07-05 11:59:13.608  1432  1432 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-05 11:59:13.608   969  1267 E WifiStateMachine: [1,467,712,753,621 ms] noteScanstart no scan source
07-05 11:59:13.608   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:13.608   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-05 11:59:13.608   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-05 11:59:13.608   969  1788 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-05 11:59:13.608   969  1788 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: nl80211: New scan results available
07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Scan included frequencies: 2447
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
07-05 11:59:13.688  1432  1432 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: Scan completed in 0.082462 seconds
07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Associated on 2447 MHz
07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Received scan results (9 BSSes)
07-05 11:59:13.688  1432  1432 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2447 level=-52
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-55
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-65
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-65
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 00:1a:ef:42:f2:b0 freq=2412 level=-77
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 00:16:a6:1f:06:5c freq=2462 level=-79
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 00:fe:c8:73:02:02 freq=2462 level=-89
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-86
07-05 11:59:13.688  1432  1432 I wpa_supplicant: [NULL] 84:b2:61:12:64:93 freq=2412 level=-87
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: BSS: Start scan result update 5
07-05 11:59:13.688  1432  1432 D wpa_supplicant: BSS: last_scan_res_used=9/32
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: Scan-only results received
07-05 11:59:13.688  1432  1432 D wpa_supplicant: wlan0: Radio work 'scan'@0x55baf59aa0 done in 0.083529 seconds
07-05 11:59:13.688   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-05 11:59:13.688   969  1788 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-05 11:59:13.688   969  1267 E WifiStateMachine: handleMessage: E msg.what=147461
07-05 11:59:13.688   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:13.688   969  1267 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
07-05 11:59:13.688   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:13.688   969  1267 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
07-05 11:59:13.688   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:59:13.698   969  1267 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
07-05 11:59:13.698   969  1267 E WifiStateMachine: processMsg: DriverStartedState
,07-05 11:59:13.698   969  1267 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
07-05 11:59:13.698   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
07-05 11:59:13.698   969  1267 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=9 known=1 got=9 bcn=0
07-05 11:59:13.698   969  1267 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
07-05 11:59:13.698   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
07-05 11:59:13.698  1432  1432 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,07-05 11:59:13.698   969  1267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14202 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14367 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8128 
07-05 11:59:13.698   969  1267 E WifiStateMachine: [1,467,712,753,708 ms] noteScanEnd no scan source
,07-05 11:59:13.698   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
07-05 11:59:13.698  1432  1432 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,07-05 11:59:13.698   969  1267 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@338ae233 sup_state=COMPLETED debouncing=false
,07-05 11:59:13.698   969  1267 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
07-05 11:59:13.698   969  1267 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
07-05 11:59:13.698   969  1267 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-55 freq=2447
07-05 11:59:13.698   969  1267 E WifiAutoJoinController :  00:16:a6:1f:06:5c rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-65 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
,07-05 11:59:13.698   969  1267 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-65 cap [WPA2-EAP-TKIP][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : Conrad_AP 00:1a:ef:42:f2:b0 rssi=-77 cap [WPA-PSK-CCMP][WPS][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController :  00:fe:c8:73:02:02 rssi=-89 cap [WPA2-PSK-CCMP][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-86 cap [ESS] is not scored
,07-05 11:59:13.698   969  1267 E WifiAutoJoinController : RA-WINGS 84:b2:61:12:64:93 rssi=-87 cap [ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-52 cap [WPA2-PSK-CCMP][ESS] is not scored
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 9 now 1467712753714
07-05 11:59:13.698   969  1267 E WifiAutoJoinController : newSupplicantResults size=9 known=1 true
07-05 11:59:13.698   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
,07-05 11:59:13.698  1432  1432 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
,07-05 11:59:13.708   969  1267 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : ssid=NG700
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : id=0
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : mode=station
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : pairwise_cipher=CCMP
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : group_cipher=CCMP
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : key_mgmt=WPA2-PSK
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : wpa_state=COMPLETED
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : ip_address=192.168.1.107
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
,07-05 11:59:13.708   969  1267 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-55,-127) num=(1,0)
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-55 freq=2447 Current: f4:f2:6d:22:99:3e
07-05 11:59:13.708   969  1267 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
07-05 11:59:13.708   969  1267 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 11:59:13.708   969  1267 E WifiAutoJoinController : Done attemptAutoJoin status=0
07-05 11:59:13.708   969  1267 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
,07-05 11:59:13.708   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:13.868  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:13.908  1945  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-05 11:59:13.908  1945  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:59:13.908  1945  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:59:13.908  1945  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-05 11:59:13.908  1945  2118 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:59:13.918  1572  1771 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
07-05 11:59:13.918  1572  1771 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,07-05 11:59:13.928  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,07-05 11:59:13.938   969  1276 D PMS     : releaseWL(20709c17): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,07-05 11:59:13.938  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 11:59:13.938  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,07-05 11:59:14.188   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:14.188  1339  1339 D WIFI_ICON: WifiActivity: 1,
07-05 11:59:14.188   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=275
07-05 11:59:14.188  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-05 11:59:14.188   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:15.188   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:15.188   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=275
07-05 11:59:15.188   969   969 E WifiTrafficPoller: notifying of data activity 0
,07-05 11:59:15.198  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:15.198  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:15.688   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:15.688   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:15.688   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=3.9, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:2077] from screen [on:0 period:-1166059533] gl hn u24 rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:15.688   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:15.688   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=150 tx=3.9, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166059531] gl hn u24 rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:15.688   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:15.688   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:15.688  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:15.708  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:15.708   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:15.708   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:15.708   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:15.708   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.96 txretriesrate=0.00 rxrate=2.88 userTriggerdPenalty0
07-05 11:59:15.708  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:15.708   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:59:15.708  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:15.708   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:15.708   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:15.708   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:15.708   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:16.188   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:16.198   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=275
,07-05 11:59:17.198   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:17.198  1339  1339 D WIFI_ICON: WifiActivity: 1
,07-05 11:59:17.198   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=276
07-05 11:59:17.198  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-05 11:59:17.198   969   969 E WifiTrafficPoller: notifying of data activity 1
,07-05 11:59:17.858   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:59:17.858   969  6828 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173}
07-05 11:59:17.858   969  6828 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:17.858   969  6828 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:17.908  3202  3264 I HtcModeClient: handler message = 4011
07-05 11:59:17.908  3202  3264 E HtcModeClient: Check connection and retry 11 times.
,07-05 11:59:18.198   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:18.198  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:18.198   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=276
07-05 11:59:18.198  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:18.198   969   969 E WifiTrafficPoller: notifying of data activity 0
,07-05 11:59:18.708   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:18.708   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:18.708   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=2.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1166056510] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:18.708   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:18.708   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=2.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166056508] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-05 11:59:18.708   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:18.718   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:18.718  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:18.728  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,07-05 11:59:18.728   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:18.728   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:18.728   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:18.728   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.98 txretriesrate=0.00 rxrate=1.94 userTriggerdPenalty0
07-05 11:59:18.728   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:18.728  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:18.728   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:18.728  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:18.728   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:18.728   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
,07-05 11:59:18.728   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:19.198   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:19.198   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=276
,07-05 11:59:20.198   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:20.198   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=277
07-05 11:59:20.208  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:59:20.198   969   969 E WifiTrafficPoller: notifying of data activity 1
07-05 11:59:20.208  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:21.198   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:21.208   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=287
,07-05 11:59:21.728   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:21.738   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:21.738   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=1.0, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1166053485] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:21.738   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:21.738   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=1.0, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166053484] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:21.738   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:21.738   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:21.738  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:21.748  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:21.748   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:21.748   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
,07-05 11:59:21.748   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:21.758   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.49 txretriesrate=0.00 rxrate=7.97 userTriggerdPenalty0
07-05 11:59:21.758  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:21.758   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:21.758  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-05 11:59:21.758   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:21.758   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:21.758   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:21.758   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:22.118   969   969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,07-05 11:59:22.208   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:22.208   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=290
,07-05 11:59:22.858   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 11:59:22.858   969  6829 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173}
,07-05 11:59:22.858   969  6829 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:22.858   969  6829 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:22.908  3202  3264 I HtcModeClient: handler message = 4011
07-05 11:59:22.908  3202  3264 E HtcModeClient: Check connection and retry 12 times.
,07-05 11:59:23.208   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:23.208   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=291
,07-05 11:59:24.208   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:24.208   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=291
07-05 11:59:24.218  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:24.208   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:59:24.218  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:24.758   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:24.758   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:24.758   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1166050463] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:24.758   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:24.758   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166050461] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:24.758   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:24.758   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:24.758  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:24.778  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:24.778   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150,
07-05 11:59:24.778   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:24.778   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:24.778   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.24 txretriesrate=0.00 rxrate=4.48 userTriggerdPenalty0
07-05 11:59:24.778   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:59:24.778   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:24.778  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:24.778   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:24.778  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-05 11:59:24.778   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:24.778   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:25.208   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:25.218   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=291
,07-05 11:59:26.218   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:26.218   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=292
07-05 11:59:26.218  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:59:26.218   969   969 E WifiTrafficPoller: notifying of data activity 1
07-05 11:59:26.218  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:27.218   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:27.218   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=292
07-05 11:59:27.218  1339  1339 D WIFI_ICON: WifiActivity: 0
,07-05 11:59:27.218   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:59:27.228  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:27.348   969  1046 D XAN-DPC : mRamp.onAnimationEnd. policy=2,
07-05 11:59:27.348   969  1046 D PMS     : MSG: UDAS false->true
,07-05 11:59:27.778   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155,
07-05 11:59:27.778   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:27.778   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1166047440] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:27.778   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:27.778   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166047438] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:27.778   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:27.788   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:27.788  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:27.798  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,07-05 11:59:27.798   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:27.798   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
,07-05 11:59:27.798   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
07-05 11:59:27.798   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.12 txretriesrate=0.00 rxrate=2.74 userTriggerdPenalty0
,07-05 11:59:27.798   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:27.798   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:27.798   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:27.798   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:27.798   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:27.808  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:27.808  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:27.858   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,07-05 11:59:27.858   969  6830 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173}
07-05 11:59:27.858   969  6830 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:27.858   969  6830 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:27.918  3202  3264 I HtcModeClient: handler message = 4011,
,07-05 11:59:27.928  3202  3264 E HtcModeClient: Check connection and retry 12 times. Stop service and kill this process.,
,07-05 11:59:27.938  3202  3202 D HtcModeClient: Don't start project servcice,
,07-05 11:59:27.938  3202  3202 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true,
,07-05 11:59:27.938  3202  3202 D HtcModeClient: connectState: CONNECTION_READY = false
07-05 11:59:27.938  3202  3202 D SilentMusic: call stop
07-05 11:59:27.938  3202  3202 D HtcModeClient: close connection
07-05 11:59:27.938  3202  3202 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
07-05 11:59:27.938  3202  3268 W CANMesgAgentLocalSocket: read the terminate packet, so break
,07-05 11:59:27.948   969  1676 I ActivityManager: Killing 3202:com.htc.autobot/u0a47 (adj 15): empty #17
,07-05 11:59:27.948   969  1676 D Process : killProcessQuiet, pid=3202,
07-05 11:59:27.948   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:28.058   969  1758 I ActivityManager: Recipient 3202
,07-05 11:59:28.218   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:28.218   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=292
,07-05 11:59:28.888   969  1256 I ActivityManager: Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6831 uid=10076 gids={50076, 9997} abi=arm64-v8a
07-05 11:59:28.898   969  1256 D PMS     : acquireWL(2275be9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10076}
07-05 11:59:28.898   969  1256 V AlarmManager: sending alarm PendingIntent{13179238: PendingIntentRecord{1ee68211 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1467712768883, Int=60000
07-05 11:59:28.898   969   969 D PMS     : releaseWL(2275be9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,07-05 11:59:28.958  6831  6852 D SMSBackup: SMSBackupAgentService started
,07-05 11:59:28.958  6831  6852 D SMSBackup: Checking restore status
,07-05 11:59:28.958  6831  6852 D SMSBackup: Restore complete,
07-05 11:59:28.958  6831  6852 D SMSBackup: cancelCheckAlarm
,07-05 11:59:28.968  6831  6852 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,07-05 11:59:28.968   969   988 I ActivityManager: Killing 5588:com.google.android.music:main/u0a159 (adj 15): empty #17
07-05 11:59:28.968   969   988 D Process : killProcessQuiet, pid=5588
,07-05 11:59:28.968   969   988 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:29.088   969  1706 I ActivityManager: Recipient 5588
,07-05 11:59:29.088   969  2390 D MediaRouterService: Client com.google.android.music (pid 5588): Died!
,07-05 11:59:29.218   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:29.228   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=293
,07-05 11:59:29.228  1339  1339 D WIFI_ICON: WifiActivity: 1
07-05 11:59:29.228   969   969 E WifiTrafficPoller: notifying of data activity 1
07-05 11:59:29.228  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:30.228   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:30.228   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=293,
07-05 11:59:30.228  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:30.228   969   969 E WifiTrafficPoller: notifying of data activity 0
,07-05 11:59:30.228  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:30.808   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:30.808   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:30.808   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1166044413] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:30.808   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:30.808   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166044412] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:30.808   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:30.808   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:30.808  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:30.818  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:30.828   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:30.828   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:30.828   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK,
,07-05 11:59:30.828   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.06 txretriesrate=0.00 rxrate=1.87 userTriggerdPenalty0
,07-05 11:59:30.828   969  1267 E WifiStateMachine:  good link -> stuck count =0
,07-05 11:59:30.828   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:30.828   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
07-05 11:59:30.828   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:30.828   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:30.828  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:30.828  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:31.228   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
07-05 11:59:31.228   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=293
,07-05 11:59:32.228   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-05 11:59:32.228   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=294
07-05 11:59:32.228   969   969 E WifiTrafficPoller: notifying of data activity 1
07-05 11:59:32.238  1339  1339 D WIFI_ICON: WifiActivity: 1
,07-05 11:59:32.238  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-05 11:59:32.858   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,07-05 11:59:32.858   969  6853 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173},
07-05 11:59:32.858   969  6853 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:32.858   969  6853 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 11:59:33.238   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:33.238   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=294
07-05 11:59:33.238  1339  1339 D WIFI_ICON: WifiActivity: 0
07-05 11:59:33.238   969   969 E WifiTrafficPoller: notifying of data activity 0
07-05 11:59:33.238  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:33.828   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:33.828   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:33.828   969  1267 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1166041390] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-05 11:59:33.828   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:33.828   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1166041389] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:33.828   969  1267 E WifiStateMachine:  get link layer stats 0
07-05 11:59:33.828   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:33.828  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 11:59:33.848  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,07-05 11:59:33.848   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:33.848   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:33.848   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
,07-05 11:59:33.848   969  1267 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.03 txretriesrate=0.00 rxrate=1.44 userTriggerdPenalty0
07-05 11:59:33.848   969  1267 E WifiStateMachine:  good link -> stuck count =0
07-05 11:59:33.848   969  1267 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-05 11:59:33.848   969  1267 E WifiStateMachine:  isHighRSSI       ---> score=61
,07-05 11:59:33.848   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:33.848  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 11:59:33.848   969  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-05 11:59:33.848  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 11:59:33.938   969  1256 D PMS     : acquireWL(9cf99e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
,07-05 11:59:33.948   969  1256 V AlarmManager: sending alarm PendingIntent{18a02e4d: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712773948, Int=0
07-05 11:59:33.948   969   969 D PMS     : releaseWL(9cf99e4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 11:59:34.168  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:34.198  1945  6778 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
,07-05 11:59:34.198  1945  6778 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:59:34.198  1945  6778 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:59:34.208  1945  6778 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:59:34.208  1945  6778 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:34.238  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 11:59:34.238   969  1046 I PMS     : Going to sleep due to screen timeout (uid 1000)...,
07-05 11:59:34.238  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 11:59:34.238  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
07-05 11:59:34.238   969   969 I SensorManager: unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3816b72
07-05 11:59:34.238   969   969 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-05 11:59:34.238   969   969 W SensorService: disable: get sensor name = Accelerometer Sensor
,07-05 11:59:34.238   969   969 W SensorService: pid=969, uid=1000
07-05 11:59:34.238   969   969 W SensorService: Active sensors: size = 4
07-05 11:59:34.238   969   969 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
07-05 11:59:34.238   969   969 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
07-05 11:59:34.238   969   969 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-05 11:59:34.238   969   969 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-05 11:59:34.238   969   969 W SensorService: SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3816b72, eanble = 0, strlen(mName) = 90
07-05 11:59:34.238   969   969 W SensorService: Active Listeners: mActiveListeners.size() = 2
07-05 11:59:34.238   969   969 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@2f86a378
07-05 11:59:34.238   969   969 W SensorService: Listener[1] = com.htc.smartdim.sensor_eye@109b12d4
07-05 11:59:34.238   969   969 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,07-05 11:59:34.238   969   969 W PMN     : goingToSleep
,07-05 11:59:34.248  1339  1369 W HtcLockScreen: KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 11:59:34.258   969  1048 W PMS     : mWirelessDisplayManager is null
,07-05 11:59:34.268   969  1048 W PMS     : mWirelessDisplayManager is still null
07-05 11:59:34.268   969   969 D PMS     : acquireWL(315fde67): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 969 1000 null
07-05 11:59:34.268  5440  5440 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 11:59:34.268   969   969 W PMN     : goingToSleep done
07-05 11:59:34.268  5440  5440 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-05 11:59:34.268   969  1046 I PMS     : Sleeping (uid 1000)...
07-05 11:59:34.268   969  1046 D XAN-DPS : prepareColorFade 1
,07-05 11:59:34.278   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 11:59:34.278   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=294
,07-05 11:59:34.278   969  1671 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,07-05 11:59:34.278   969  1046 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-05 11:59:34.278   969  1046 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:59:34.278   969  1046 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 11:59:34.278   969  1046 I Adreno-EGL: Local Branch: 
07-05 11:59:34.278   969  1046 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 11:59:34.278   969  1046 I Adreno-EGL: Local Patches: NONE
07-05 11:59:34.278   969  1046 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 11:59:34.288  1339  1339 D BlindfeedViewCtrl: onScreenTurnedOff
,07-05 11:59:34.298   969  1028 I ActivityManager: Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6855 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,07-05 11:59:34.298  5440  5440 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@23d30c9a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33f85561, 16908290=android.view.AbsSavedState$1@33f85561}, android:focusedViewId=100}]}],
,07-05 11:59:34.298  5440  5440 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 11:59:34.298   969  1758 D PMS     : releaseWL(315fde67): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
07-05 11:59:34.298  5440  5440 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-05 11:59:34.308   969   969 D AlarmManager: ACTION_SCREEN_ON
07-05 11:59:34.298  5440  5440 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 11:59:34.308   969   969 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 11
,07-05 11:59:34.308   969   969 I AlarmManager: [AlarmQueuing] recover blocked alarms
07-05 11:59:34.308   969   969 E WifiTrafficPoller:  packet count Tx=208 Rx=294
07-05 11:59:34.308   969   969 I AlarmManager: [AlarmQueuing] done recovering
07-05 11:59:34.308   969   969 I AlarmManager: [AlarmQueuing] recover EPS screen off blocked alarms
07-05 11:59:34.308   969   969 I AlarmManager: [AlarmQueuing] done EPS screen off alarm recovering
,07-05 11:59:34.308   969   969 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL true Token 1,
07-05 11:59:34.318   969  1267 E WifiStateMachine: handleMessage: E msg.what=131167
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: ConnectModeState
,07-05 11:59:34.318   969  1267 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: DriverStartedState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: DefaultState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
,07-05 11:59:34.318   969  1267 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
07-05 11:59:34.318   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
07-05 11:59:34.318  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 1'
07-05 11:59:34.318  1432  1432 I wpa_supplicant: SET_SCREEN_ON:On
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_keepalive +
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_keepalive: enable=0, type=2, interval=15
07-05 11:59:34.318  1432  1432 D wpa_supplicant: getPrivFuncNum +	
07-05 11:59:34.318  1432  1432 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6,
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_TX_TRACKING (1)+
07-05 11:59:34.318  1432  1432 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
,07-05 11:59:34.318   969  1267 E WifiStateMachine: setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter:     GroupId: 
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter:     Passphrase: 
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter:     SessionId: 0
07-05 11:59:34.318   969  1267 D WifiDisplayAdapter:     IP Address: }
07-05 11:59:34.318   402  1061 V SRS_Proc: ParamSet string: screen_state=on
07-05 11:59:34.318   402  1061 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-05 11:59:34.318   969  1267 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
07-05 11:59:34.318   969  1267 E WifiStateMachine: handleScreenStateChanged Exit: true
07-05 11:59:34.318   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:34.318   969  1267 E WifiStateMachine: handleMessage: E msg.what=131154
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:34.318   969  1267 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-05 11:59:34.318   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:34.318   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-05 11:59:34.318   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 11:59:34.318  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-05 11:59:34.318   969  1268 D WifiController: handleMessage: E msg.what=155650
07-05 11:59:34.318   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 11:59:34.318   969  1268 D WifiController: processMsg: StaEnabledState
07-05 11:59:34.318   969  1268 D WifiController: processMsg: DefaultState
07-05 11:59:34.328   969  1268 D WifiController: handleMessage: X
07-05 11:59:34.328   969  6873 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=173} preTxRxSum={txSum=188 rxSum=173}
07-05 11:59:34.328   969  6873 D WifiDataStallTracker: updateDataStallInfo: NONE
07-05 11:59:34.328   969  1264 D NetworkPolicy: updateScreenOn: false
07-05 11:59:34.328   969  6873 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
07-05 11:59:34.328   969  1264 V NetworkPolicy: updateIfacesLocked()
,07-05 11:59:34.328   969  1264 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
,07-05 11:59:34.328   969  1026 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-05 11:59:34.328  1432  1432 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-05 11:59:34.338   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 11:59:34.338   969  1267 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-05 11:59:34.338   969  1267 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-55 "NG700"WPA_PSK
07-05 11:59:34.338   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:34.338   969  1267 E WifiStateMachine: handleMessage: E msg.what=131127
07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:34.338   969  1267 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:34.338   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:59:34.338   969  1267 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
07-05 11:59:34.338   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:34.338   969  1267 E WifiStateMachine: handleMessage: E msg.what=131129
07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:34.338   969  1267 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
,07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:34.338   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-05 11:59:34.338   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:59:34.338   969  1267 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
07-05 11:59:34.338   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
07-05 11:59:34.338  1432  1432 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
07-05 11:59:34.338  1432  1432 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
07-05 11:59:34.338   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:34.338   969  1788 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
07-05 11:59:34.338   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: BLACKLIST CLEAR 
07-05 11:59:34.338  1443  1443 D DotMatrix: [EventService] mHtcSpeakerReceiver.onReceive, action: android.intent.action.SCREEN_ON, mCoverOn = false
07-05 11:59:34.338  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,mbIsUserInForeground:true
07-05 11:59:34.338  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,mbIsUserInForeground:true
,07-05 11:59:34.358  1339  1708 I IntentController: receive(android.intent.action.SCREEN_ON,1,false)
,07-05 11:59:34.358  6855  6855 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:59:34.418   969  1046 D XAN-DPS : prepareColorFade done,
07-05 11:59:34.428   969  1299 D XAN-DPS : setBrightness to 0
07-05 11:59:34.428   969  1046 D PMS     : MSG: UDAS true->false
,07-05 11:59:34.438   969  1046 I SensorManager: unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@2f86a378
07-05 11:59:34.438   969  1038 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 11:59:34.438   969  1046 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-05 11:59:34.438   969   969 V ActivityManager: Display changed displayId=0
,07-05 11:59:34.438   969  1046 W SensorService: disable: get sensor name = CM32181 Light sensor
07-05 11:59:34.438  1443  1443 D DotMatrix: [EventService]  onDisplayChanged: 0
07-05 11:59:34.438   969  1046 W SensorService: pid=969, uid=1000
07-05 11:59:34.438   969  1046 W SensorService: Active sensors: size = 3
07-05 11:59:34.438   969  1046 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
,07-05 11:59:34.438   969  1046 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-05 11:59:34.438   969  1046 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-05 11:59:34.438   969  1046 W SensorService: SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@2f86a378, eanble = 0, strlen(mName) = 67
07-05 11:59:34.438   969  1046 W SensorService: Active Listeners: mActiveListeners.size() = 1
07-05 11:59:34.438   969  1046 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@109b12d4
07-05 11:59:34.438   969  1046 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,07-05 11:59:34.448  1443  1443 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
07-05 11:59:34.448   969  1046 D XAN-DPC : mRamp.onAnimationEnd. policy=0
,07-05 11:59:34.448   388   388 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
,07-05 11:59:34.448   388   388 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,07-05 11:59:34.568   969  1681 I art     : Explicit concurrent mark sweep GC freed 39399(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/28MB, paused 1.876ms total 189.807ms
,07-05 11:59:34.568   969  1681 D PMS     : acquireWL(2581fa03): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:34.568   969  2390 D PMS     : acquireWL(3520335f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:34.568  6855  6855 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@131a4951(com.htc.providers.calendar.HtcCalendarProvider@2a2e15b6)
,07-05 11:59:34.578   969  1706 D PMS     : releaseWL(2581fa03): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:34.598  6855  6880 D CalendarProvider2: wait start:true
,07-05 11:59:34.598   969  1464 D PMS     : releaseWL(3520335f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:34.628   969   969 D AlarmManager: ACTION_SCREEN_OFF
,07-05 11:59:34.628   969   969 I AlarmManager: [AlarmQueuing] screen off now: 
07-05 11:59:34.628   969   969 I AlarmManager: [AlarmQueuing] data connection: true
07-05 11:59:34.628   969   969 I AlarmManager: [AlarmQueuing] wifi connection: true
,07-05 11:59:34.628   969   969 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 12
,07-05 11:59:34.628   969   969 D WifiDataStallTracker: stopDataStallAlarm 
07-05 11:59:34.628   969   969 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL false Token 2
07-05 11:59:34.628   969  1267 E WifiStateMachine: handleMessage: E msg.what=131167
07-05 11:59:34.628   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:34.628   969  1267 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.628   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:34.628   969  1267 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.628   969  1267 E WifiStateMachine: processMsg: ConnectModeState
07-05 11:59:34.628   969  1267 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: processMsg: DriverStartedState
07-05 11:59:34.638   402  1060 V SRS_Proc: ParamSet string: screen_state=off
,07-05 11:59:34.638   969  1267 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: processMsg: SupplicantStartedState
07-05 11:59:34.638   969  1267 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: processMsg: DefaultState
07-05 11:59:34.638   402  1060 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-05 11:59:34.638   969  1267 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
07-05 11:59:34.638   969  1267 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
07-05 11:59:34.638  1432  1432 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 0'
07-05 11:59:34.638  1432  1432 I wpa_supplicant: SET_SCREEN_ON:Off
07-05 11:59:34.638  1432  1432 I wpa_supplicant: htc_wext_set_keepalive +
07-05 11:59:34.638  1432  1432 I wpa_supplicant: htc_wext_set_keepalive: enable=1, type=2, interval=15
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter:     Client/Owner: Client
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter:     GroupId: 
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter:     Passphrase: 
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter:     SessionId: 0
07-05 11:59:34.638   969  1267 D WifiDisplayAdapter:     IP Address: }
07-05 11:59:34.638  1432  1432 D wpa_supplicant: getPrivFuncNum +	
07-05 11:59:34.638  1432  1432 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
07-05 11:59:34.638  1432  1432 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
07-05 11:59:34.638  1432  1432 I wpa_supplicant: get_ip_address source addr = c0a8016b
07-05 11:59:34.638  1432  1432 I wpa_supplicant: htc_wext_set_keepalive gateway addr = c0a80101
07-05 11:59:34.638  1432  1432 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
07-05 11:59:34.638  1339  1339 I SensorManager: registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@37afa963, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
07-05 11:59:34.638   969  1268 D WifiController: handleMessage: E msg.what=155651
07-05 11:59:34.638   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 11:59:34.638   969  1268 D WifiController: processMsg: StaEnabledState
07-05 11:59:34.638   969  1268 D WifiController: processMsg: DefaultState
07-05 11:59:34.638   969  1268 D WifiController: handleMessage: X
07-05 11:59:34.638   969  1442 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-05 11:59:34.638   969  1264 D NetworkPolicy: updateScreenOn: false
07-05 11:59:34.638   969  1442 W SensorService: enable: get sensor name = hTC Gesture Motion HIDI
07-05 11:59:34.638   969  1264 V NetworkPolicy: updateIfacesLocked()
07-05 11:59:34.638   969  1026 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-05 11:59:34.638   969  1264 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
07-05 11:59:34.638  6855  6880 D CalendarProvider2: wait end:false
07-05 11:59:34.638   969  1267 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
07-05 11:59:34.638   969  1267 E WifiStateMachine: handleScreenStateChanged Exit: false
07-05 11:59:34.638   969  1267 E WifiStateMachine: handleMessage: X
07,-05 11:59:34.638   969  1267 E WifiStateMachine: handleMessage: E msg.what=131154
07-05 11:59:34.638   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:34.638   969  1267 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:34.638   969  1267 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-05 11:59:34.638   969  1267 E WifiStateMachine: handleMessage: X
07-05 11:59:34.638  1443  1443 D DotMatrix: [EventService] mHtcSpeakerReceiver.onReceive, action: android.intent.action.SCREEN_OFF, mCoverOn = false
07-05 11:59:34.638  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 11:59:34.638   969  1442 W SensorService: pid=1339, uid=10041
07-05 11:59:34.638   969  1442 W SensorService: Active sensors: size = 4
07-05 11:59:34.638   969  1442 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
07-05 11:59:34.638   969  1442 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-05 11:59:34.638   969  1442 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-05 11:59:34.638   969  1442 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-05 11:59:34.648  1443  1443 D DotMatrix: [EventService] getTotalRam: 1842 Mb
07-05 11:59:34.648   969  2390 W SensorService: SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@37afa963, eanble = 1, strlen(mName) = 57
07-05 11:59:34.648   969  2390 W SensorService: Active Listeners: mActiveListeners.size() = 2
07-05 11:59:34.648   969  2390 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@109b12d4
07-05 11:59:34.648   969  2390 W SensorService: Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@37afa963
07-05 11:59:34.648   969  2390 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-05 11:59:34.668   969   988 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.PowerCommonReceiver: pid=6886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 11:59:34.678  1572  6905 D ContactMessageStore: start background delete task...
,07-05 11:59:34.678  1339  1708 I IntentController: receive(android.intent.action.SCREEN_OFF,1,false)
07-05 11:59:34.678  1572  6905 D ContactMessageStore: size: 0 , 0
,07-05 11:59:34.688  1572  6905 D ContactMessageStore: Background delete complete
,07-05 11:59:34.688  1623  1623 I ContextualWidget: unlockModeChange
,07-05 11:59:34.728   388   673 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
07-05 11:59:34.728   969  1299 D PMS     : Setting HAL interactive mode to false
,07-05 11:59:34.728   388   673 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
07-05 11:59:34.728   969  1299 D SurfaceControl: Excessive delay in setPowerMode(): 294ms
,07-05 11:59:34.738   969  1299 D PMS     : Setting HAL interactive mode to false done
07-05 11:59:34.738   969  1299 D PMS     : Setting HAL auto-suspend mode to true
07-05 11:59:34.738   969  1299 D PMS     : Setting HAL auto-suspend mode done
,07-05 11:59:34.748   969  1299 D HABCtrl : TPE algorithm. remove timeout.
07-05 11:59:34.748   969  1299 D PMS     : OOBE c monitor 11
,07-05 11:59:34.748   969  1671 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
07-05 11:59:34.748   969  1034 I InputMethodManagerService: screenObserver, isScreenOn=false
07-05 11:59:34.748   969  1464 D PMS     : acquireWL(3156d72d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,07-05 11:59:34.748   969  1464 I BatteryService: n_update end
07-05 11:59:34.748   969  1464 D PMS     : releaseWL(3156d72d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 11:59:34.758  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 11:59:34.758  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 11:59:34.758   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 11:59:34.758  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 11:59:34.758   969   969 D NotificationService: plugged=true pluggin=true
07-05 11:59:34.758   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 11:59:34.758   969   969 D PMS     : runPSCheck
07-05 11:59:34.758   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 11:59:34.758   969   969 D HtcPowerSaver: Checking...
,07-05 11:59:34.758   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 11:59:34.758   969   969 I HtcPowerSaver: >> updateStatus
07-05 11:59:34.758   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 11:59:34.758   969  1268 D WifiController: battery changed pluggedType: 2
07-05 11:59:34.758   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 11:59:34.758   969  1034 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 11:59:34.758   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 11:59:34.758   969  1034 I InputMethodManagerService: Disable input method client, pid=5440
07-05 11:59:34.758   969  1268 D WifiController: processMsg: StaEnabledState
07-05 11:59:34.768   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 11:59:34.758   969  1268 D WifiController: processMsg: DefaultState
07-05 11:59:34.768   969   969 I HtcPowerSaver: << updateStatus
07-05 11:59:34.758   969  1268 D WifiController: handleMessage: X
07-05 11:59:34.768  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 11:59:34.758  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 11:59:34.768  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 11:59:34.758  5440  5440 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{139439ec VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@34c61886
07-05 11:59:34.758  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 11:59:34.768  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-05 11:59:34.768  1585  1760 D NfcService: ScreenObserver: OFF
07-05 11:59:34.768   969  1993 D PMS     : releaseWL(2ef5f6ff): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-05 11:59:34.768  1585  6908 D NfcService: applyRouting - 0
07-05 11:59:34.768   969  1981 D PMS     : acquireWL(11578462): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:34.778   969  1442 D PMS     : releaseWL(11578462): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:59:34.778   969  1442 D PMS     : acquireWL(126569f3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1585 1027 null
07-05 11:59:34.778  1585  6908 D NfcService: applyRouting -2
07-05 11:59:34.778  1585  6908 D NfcService: applyRouting
07-05 11:59:34.778  1585  6908 D NfcService: Ignore this applyRouting...
,07-05 11:59:34.778   969  2390 D PMS     : releaseWL(126569f3): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,07-05 11:59:34.778   969  1676 D PMS     : acquireWL(206856b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:34.778   969  2390 D PMS     : releaseWL(206856b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:34.798  6886  6886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.PowerCommonReceiver.onReceive:20 android.app.ActivityThread.handleReceiver:2712 
,07-05 11:59:34.798   969   969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
07-05 11:59:34.808   969   969 I InputManager: Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
07-05 11:59:34.808  1339  1708 I IntentController: receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,07-05 11:59:34.808   969   969 D SmartDim: Init customizeScreenOffDelayClass error,
,07-05 11:59:34.808  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 11:59:34.818  6886  6886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.PowerCommonReceiver.onReceive:20 android.app.ActivityThread.handleReceiver:2712 
,07-05 11:59:34.818  6886  6909 D PowerUtils: getUserIdOfProcess, curUserId = 0,
07-05 11:59:34.818  6886  6909 D PowerUtils: isRunningUnderOwner, isOwner = true,
07-05 11:59:34.818   969   969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,07-05 11:59:34.828   969   969 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@109b12d4
07-05 11:59:34.828   969   969 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-05 11:59:34.828   969   969 W SensorService: disable: get sensor name = Accelerometer Sensor
,07-05 11:59:34.828   969   969 W SensorService: pid=969, uid=1000
07-05 11:59:34.828   969   969 W SensorService: Active sensors: size = 3
07-05 11:59:34.828   969   969 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-05 11:59:34.828   969   969 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-05 11:59:34.828   969   969 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-05 11:59:34.828   969   969 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@109b12d4, eanble = 0, strlen(mName) = 36
07-05 11:59:34.828   969   969 W SensorService: Active Listeners: mActiveListeners.size() = 1
07-05 11:59:34.828   969   969 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@37afa963
07-05 11:59:34.828   969   969 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-05 11:59:34.828   969   969 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-05 11:59:34.828   969   969 W SensorService: disable: get sensor name = CM36686 Proximity sensor
,07-05 11:59:34.828  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 ,
,07-05 11:59:34.838   969   969 W SensorService: pid=969, uid=1000
07-05 11:59:34.838  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:72 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
07-05 11:59:34.838   969   969 W SensorService: Active sensors: size = 2
07-05 11:59:34.838   969   969 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-05 11:59:34.838   969   969 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-05 11:59:34.838   969   969 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@109b12d4, eanble = 0, strlen(mName) = 36
07-05 11:59:34.838   969   969 W SensorService: Active Listeners: mActiveListeners.size() = 1
07-05 11:59:34.838   969   969 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@37afa963
,07-05 11:59:34.838   969   969 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-05 11:59:34.838   969  6911 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@109b12d4
07-05 11:59:34.838  6886  6910 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-05 11:59:34.838  6886  6910 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 11:59:34.838   969   969 E ActivityThread: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@35bbcc7d that was originally registered here. Are you missing a call to unregisterReceiver()?
07-05 11:59:34.838   969   969 E ActivityThread: android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@35bbcc7d that was originally registered here. Are you missing a call to unregisterReceiver()?
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.Service.onStartCommand(Service.java:458)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:59:34.838   969   969 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 11:59:34.838   969   969 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:59:34.838   969   969 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 11:59:34.838   969   969 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-05 11:59:34.838  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:30 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
,07-05 11:59:34.848  6886  6910 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-05 11:59:34.848  6886  6912 D ExtremePowerSaverMisc: epsInRange = 0
,07-05 11:59:34.858   969  1276 D PMS     : acquireWL(3398bee5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6886 1000 null
,07-05 11:59:34.858  1339  1339 I ClockController: stop clock update:screen off
,07-05 11:59:34.868  6886  6909 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-05 11:59:34.868  6886  6909 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 11:59:34.868  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
07-05 11:59:34.868  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:72 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
,07-05 11:59:34.878  6886  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:30 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
,07-05 11:59:34.878  6886  6918 D ExtremePowerSaverMisc: epsInRange = 0
,07-05 11:59:34.888   969  1681 D PMS     : releaseWL(3398bee5): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,07-05 11:59:34.908   969  1758 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6920 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,07-05 11:59:34.948  6886  6910 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8,
,07-05 11:59:34.978  6886  6910 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,07-05 11:59:34.988  6886  6910 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 1000, sipper.name = com.android.settings:remote
,07-05 11:59:34.988  6886  6910 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10024, sipper.name = com.google.android.gms.persistent
07-05 11:59:34.988  6886  6910 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 11:59:34.988  6886  6910 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-05 11:59:34.998  6886  6910 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10041, sipper.name = com.htc.dotmatrixevent,
07-05 11:59:34.998  6886  6910 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 0, sipper.name = null
07-05 11:59:34.998  6886  6919 D SmartSyncUtils: getMobilePolicyEnabled, result = true
07-05 11:59:34.998   969  1676 I ActivityManager: Killing 6597:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
07-05 11:59:34.998   969  1676 D Process : killProcessQuiet, pid=6597
,07-05 11:59:34.998   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.removeContentProvider:10146 
,07-05 11:59:34.998   969   969 E WifiTrafficPoller: ADD_CLIENT: 9
07-05 11:59:34.998   969  1268 D WifiService: New client listening to asynchronous messages
,07-05 11:59:35.018  6886  6910 D PowerUsageService: calcPower(), no data,
,07-05 11:59:35.068   969  4144 I ActivityManager: Recipient 6597,
07-05 11:59:35.068   969  1268 D WifiService: Client connection lost with reason: 4
,07-05 11:59:35.108  6886  6910 D PowerUtils: getUserIdOfProcess, curUserId = 0,
07-05 11:59:35.108  6886  6910 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 11:59:35.108  6886  6910 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-05 11:59:35.188   969  1676 D Process : killProcessQuiet, pid=6697
,07-05 11:59:35.188   969  1676 I ActivityManager: Killing 6697:com.android.settings/1000 (adj 15): empty #17
07-05 11:59:35.188   969  1676 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:35.278   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 8
,07-05 11:59:35.298   969  1758 I ActivityManager: Recipient 6697
,07-05 11:59:35.308   969   969 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 8
,07-05 11:59:35.618  6855  6855 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
07-05 11:59:35.618  6855  6855 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 11:59:35.618  5980  5980 D ProviderChangeReceiver: ---------------------------------------------------
07-05 11:59:35.618  5980  5980 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-05 11:59:35.628  5980  6945 D HtcAlertService: start to updateAlertNotification!,
,07-05 11:59:35.628   969  2390 I ActivityManager: Killing 6195:com.google.android.apps.plus/u0a167 (adj 15): empty #17
07-05 11:59:35.628   969  2390 D Process : killProcessQuiet, pid=6195
07-05 11:59:35.628   969  2390 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:35.718   969  1442 I ActivityManager: Recipient 6195
,07-05 11:59:35.758  5980  6945 D HtcAlertService: No fired or scheduled alerts,
07-05 11:59:35.758  5980  6945 D HtcAlertUtils: -- cancelReminderNotification --
,07-05 11:59:35.758  5980  6945 D HtcAlertUtils: broadcastExistReminder!,
,07-05 11:59:35.768  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true,
,07-05 11:59:35.948   969  1256 D PMS     : acquireWL(4044bc8): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024},
07-05 11:59:35.948  2228  2228 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,07-05 11:59:35.948   969  1256 V AlarmManager: sending alarm PendingIntent{299b6461: PendingIntentRecord{13c57b86 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1467712758984, Int=536832000
07-05 11:59:35.948   969  1256 V AlarmManager: sending alarm PendingIntent{265c9c47: PendingIntentRecord{32f65c74 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=112372, Int=0
,07-05 11:59:35.958   969  1442 D PMS     : acquireWL(38c8e59d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10024 WorkSource{10024 com.google.android.gms},
,07-05 11:59:35.968   969   969 D PMS     : releaseWL(4044bc8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
07-05 11:59:35.968   969  1993 D PMS     : acquireWL(3fbcb5e3): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfo_proxy+
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 11:59:35.968   396  6946 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-05 11:59:35.968   396  6946 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 11:59:35.968   396  6946 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,07-05 11:59:35.968   396  6946 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
07-05 11:59:35.968   969  1567 D libc    : [NET] android_getaddrinfo_proxy-, success
07-05 11:59:35.978   969  1758 D PMS     : releaseWL(38c8e59d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:35.988  2228  6947 I CheckinService: Checking schedule, now: 1467712776001 next: 1467712758984
,07-05 11:59:35.988  2228  6947 I CheckinService: active receiver: enabled
,07-05 11:59:35.988   969  1276 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:36.008  2228  6947 I CheckinService: Preparing to send checkin request
,07-05 11:59:36.008  2228  6947 I EventLogService: Accumulating logs since 1467712723232
,07-05 11:59:36.028   969  1567 D AlarmManager: Ignore time set to 1467712776066 in setTime(); too close to current time 1467712776041
,07-05 11:59:36.088  2228  6947 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1,
,07-05 11:59:36.088   969  1276 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings,
07-05 11:59:36.088  2228  6947 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 11:59:36.208  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
07-05 11:59:36.208  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,07-05 11:59:36.218  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 11:59:36.218  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:59:36.218  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:59:36.288  1945  2121 I art     : Explicit concurrent mark sweep GC freed 13242(727KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 1.038ms total 61.535ms,
,07-05 11:59:36.338  1443  2811 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 11:59:36.338  1443  2811 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-05 11:59:36.338  2228  6947 W CheckinRequestBuilder: awaiting user notification for token
07-05 11:59:36.338  1443  2811 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 11:59:36.338  1339  1339 I RemoteViews: reapply : com.google.android.gms 3 40
,07-05 11:59:36.388   969  1676 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6950 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,07-05 11:59:36.428  6950  6950 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-05 11:59:36.428  6950  6950 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:59:36.448  6950  6950 I MultiDex: VM with version 2.1.0 has multidex support,
07-05 11:59:36.448  6950  6950 I MultiDex: install
,07-05 11:59:36.458  6950  6950 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 11:59:36.478  6950  6950 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,07-05 11:59:36.528  6950  6950 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,07-05 11:59:36.528  6950  6950 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e5b323: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 11:59:36.528  6950  6950 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:59:36.528  1945  5815 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,07-05 11:59:36.538  1945  1945 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,07-05 11:59:36.548  2228  2228 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 11:59:36.568   969  1706 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:36.568  5239  5239 D WearableService: callingUid 10024, callindPid: 5239
,07-05 11:59:36.578  1842  6974 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 11:59:36.598  2228  6975 D LocationInitializer: Restart initialization of location
,07-05 11:59:36.718   402   402 I WVCdm   : CdmEngine::OpenSession,
07-05 11:59:36.718   402   402 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
07-05 11:59:36.718   402   402 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 11:59:36.758   402   402 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
07-05 11:59:36.758   402   402 D DrmWidevineDash: Service_Initialize: starts!
07-05 11:59:36.758   402   402 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 11:59:36.758   402   402 D QSEECOMAPI: : App is not loaded in QSEE
07-05 11:59:36.758   402   402 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
,07-05 11:59:36.758   402   402 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 11:59:36.758   402   402 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-05 11:59:36.758   402   402 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:59:36.768  6950  6968 I art     : Background sticky concurrent mark sweep GC freed 24099(1326KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 3MB/4MB, paused 5.557ms total 101.070ms,
,07-05 11:59:36.778   402   402 D QSEECOMAPI: : Loaded image: APP id = 8
,07-05 11:59:36.778   402   402 D DrmWidevineDash: Service_Initialize: ends! returns 0,
,07-05 11:59:36.788   402   402 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
07-05 11:59:36.788   402   402 D QSAPPSVER: qsapps_get_capabilities: returns 0
07-05 11:59:36.788   402   402 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4917000
07-05 11:59:36.788   402   402 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4917000
07-05 11:59:36.788   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.788   536   551 D DrmLibTime: got the req here! ret=0
07-05 11:59:36.788   536   551 D DrmLibTime: command id, time_cmd_id = 770
07-05 11:59:36.788   536   551 D DrmLibTime: time_getutcsec starts!
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: time_get_modem_time
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
07-05 11:59:36.788   536   551 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
07-05 11:59:36.788   536   551 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1467712776
,07-05 11:59:36.788   536   551 D DrmLibTime: time_getutcsec returns 0, sec = 1467712776; nsec = 0
07-05 11:59:36.788   536   551 D DrmLibTime: time_getutcsec finished! 
07-05 11:59:36.788   536   551 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 11:59:36.788   536   551 D DrmLibTime: before calling ioctl to read the next time_cmd
07-05 11:59:36.788   459   591 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-05 11:59:36.788   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.798   402   402 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-05 11:59:36.798   402   402 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:59:36.798   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.798   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.798   402   402 D DrmWidevineDash: hlos api version =  9
07-05 11:59:36.798   402   402 D DrmWidevineDash: tz api version =  9
07-05 11:59:36.798   402   402 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:59:36.798   402   402 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-05 11:59:36.798   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-05 11:59:36.818   402   402 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xffd38058
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab090740, dataLength=8
07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-05 11:59:36.818   402   402 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab0a2ea8, wrapped_rsa_key_length=1280
07-05 11:59:36.818   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.828   402   402 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:36.828   402   402 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 11:59:36.828   402   402 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-05 11:59:36.828   402  1061 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 11:59:36.828   402  1061 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 11:59:36.828   402  1061 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 11:59:36.828   402  1061 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab092b80, idLength=0xf4a406f8
07-05 11:59:36.828   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4a4070e, maximum = 0xf4a4070f
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:36.848   402  1061 D DrmWidevineDash: hlos api version =  9
07-05 11:59:36.848   402  1061 D DrmWidevineDash: tz api version =  9
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4a4077c
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 11:59:36.848   402  1061 D WVCdm   : PrepareKeyRequest: nonce=787777860
07-05 11:59:36.848   402  1061 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab0a2ea8
07-05 11:59:36.848   402  1061 D DrmWidevineDash: message_length=1611, signature=0xab0919b8, signature_length=0xf4a406dc
07-05 11:59:36.848   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.848   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 11:59:36.848   969  1267 E WifiStateMachine: processMsg: ConnectedState
,07-05 11:59:36.848   969  1267 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1166038369] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:36.848   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
,07-05 11:59:36.848   969  1267 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166038367] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-05 11:59:36.858   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:36.988   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
07-05 11:59:36.988   402  1061 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
07-05 11:59:36.988   402  1060 I WVCdm   : CdmEngine::CloseSession
07-05 11:59:36.988   402  1060 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 11:59:36.988   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:36.988   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,07-05 11:59:36.988   402  1060 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-05 11:59:36.988   402  1060 I WVCdm   : L3 Terminate.
,07-05 11:59:36.988   402  1060 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 11:59:36.988   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:36.988   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:36.988   402  1060 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 11:59:36.988   402  1060 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 11:59:36.988   402  1060 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 8
07-05 11:59:36.988   402  1060 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0,
,07-05 11:59:36.988   402  1060 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0,
,07-05 11:59:37.038  6979  6979 E cutils-trace: Error opening trace file: Permission denied (13),
07-05 11:59:37.038  6979  6979 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-05 11:59:37.038  6979  6979 I dex2oat : dex2oat: override thread count:4
,07-05 11:59:37.138  6979  6979 I dex2oat : dex2oat took 101.107ms (threads: 4),
,07-05 11:59:37.168  6950  6971 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU (),
07-05 11:59:37.168  6950  6971 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:59:37.168  6950  6971 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 11:59:37.168  6950  6971 I Adreno-EGL: Local Branch: 
07-05 11:59:37.168  6950  6971 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 11:59:37.168  6950  6971 I Adreno-EGL: Local Patches: NONE
07-05 11:59:37.168  6950  6971 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 11:59:37.248  6950  6971 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU (),
07-05 11:59:37.248  6950  6971 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:59:37.248  6950  6971 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 11:59:37.248  6950  6971 I Adreno-EGL: Local Branch: 
07-05 11:59:37.248  6950  6971 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 11:59:37.248  6950  6971 I Adreno-EGL: Local Patches: NONE
07-05 11:59:37.248  6950  6971 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 11:59:37.338   969  1267 E WifiStateMachine: handleMessage: E msg.what=131155,
07-05 11:59:37.338   969  1267 E WifiStateMachine: processMsg: ConnectedState
07-05 11:59:37.338   969  1267 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:482] from screen [on:0 period:-1166037884] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-05 11:59:37.338   969  1267 E WifiStateMachine: processMsg: L2ConnectedState
07-05 11:59:37.338   969  1267 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1166037882] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-05 11:59:37.338   969  1267 E WifiStateMachine: handleMessage: X
,07-05 11:59:37.388   402  1061 I WVCdm   : CdmEngine::OpenSession,
07-05 11:59:37.388   402  1061 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,07-05 11:59:37.388   402  1061 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,07-05 11:59:37.398   402  1061 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,07-05 11:59:37.398   402  1061 D DrmWidevineDash: Service_Initialize: starts!
07-05 11:59:37.398   402  1061 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 11:59:37.398   402  1061 D QSEECOMAPI: : App is not loaded in QSEE
07-05 11:59:37.398   402  1061 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-05 11:59:37.398   402  1061 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 11:59:37.398   402  1061 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000,
07-05 11:59:37.398   402  1061 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:59:37.418   402  1061 D QSEECOMAPI: : Loaded image: APP id = 9,
07-05 11:59:37.418   402  1061 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-05 11:59:37.428   402  1061 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0,
07-05 11:59:37.428   402  1061 D QSAPPSVER: qsapps_get_capabilities: returns 0
07-05 11:59:37.428   402  1061 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4917000
07-05 11:59:37.428   402  1061 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4917000
07-05 11:59:37.428   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.428   536   551 D DrmLibTime: got the req here! ret=0,
07-05 11:59:37.428   536   551 D DrmLibTime: command id, time_cmd_id = 770
07-05 11:59:37.428   536   551 D DrmLibTime: time_getutcsec starts!
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: time_get_modem_time
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
07-05 11:59:37.428   536   551 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
07-05 11:59:37.428   536   551 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1467712777
07-05 11:59:37.428   536   551 D DrmLibTime: time_getutcsec returns 0, sec = 1467712777; nsec = 0
07-05 11:59:37.428   536   551 D DrmLibTime: time_getutcsec finished! 
07-05 11:59:37.428   536   551 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 11:59:37.428   536   551 D DrmLibTime: before calling ioctl to read the next time_cmd
07-05 11:59:37.428   459   591 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 11:59:37.428   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:37.438   402  1061 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0,
07-05 11:59:37.438   402  1061 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:59:37.438   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.438   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.438   402  1061 D DrmWidevineDash: hlos api version =  9
07-05 11:59:37.438   402  1061 D DrmWidevineDash: tz api version =  9
07-05 11:59:37.438   402  1061 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:59:37.438   402  1061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-05 11:59:37.438   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.458   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,07-05 11:59:37.458   402  1061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 11:59:37.458   402  1061 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 11:59:37.458   402  1061 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4a40928
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab090930, dataLength=8
07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab0a2ea8, wrapped_rsa_key_length=1280
07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.468   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.468   402  1061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 11:59:37.468   402  1061 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 11:59:37.468   402  2026 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 11:59:37.468   402  2026 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 11:59:37.468   402  2026 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 11:59:37.468   402  2026 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab092ba0, idLength=0xf2df16f8
07-05 11:59:37.468   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf2df170e, maximum = 0xf2df170f
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:59:37.498   402  2026 D DrmWidevineDash: hlos api version =  9
07-05 11:59:37.498   402  2026 D DrmWidevineDash: tz api version =  9
,07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf2df177c
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 11:59:37.498   402  2026 D WVCdm   : PrepareKeyRequest: nonce=2489000948
07-05 11:59:37.498   402  2026 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab0a2ea8
,07-05 11:59:37.498   402  2026 D DrmWidevineDash: message_length=1642, signature=0xab0919b8, signature_length=0xf2df16dc
07-05 11:59:37.498   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:59:37.668   402  2026 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
07-05 11:59:37.668   402  2026 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 11:59:37.678   402  1061 I WVCdm   : CdmEngine::CloseSession,
07-05 11:59:37.678   402  1061 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 11:59:37.678   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.678   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:37.678   402  1061 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 11:59:37.678   402  1061 I WVCdm   : L3 Terminate.
,07-05 11:59:37.678   402  1061 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 11:59:37.678   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:59:37.678   402  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:59:37.678   402  1061 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 11:59:37.678   402  1061 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 11:59:37.678   402  1061 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,07-05 11:59:37.678   402  1061 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 11:59:37.678   402  1061 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 11:59:37.758  1339  1339 D HtcUPManager: HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,07-05 11:59:37.858   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3
,07-05 11:59:37.938  2228  6947 I CheckinRequestBuilder: Classify the device as Phone.,
,07-05 11:59:37.978  2228  6947 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 11:59:37.978  2228  6947 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:59:37.978  2228  6947 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
07-05 11:59:37.978  2228  6947 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-05 11:59:37.978  2228  6947 D libc    : [NET] android_getaddrinfo_proxy+
,07-05 11:59:37.988  2228  6947 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 11:59:37.988   396  6993 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 11:59:37.988   396  6993 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
07-05 11:59:37.988   396  6993 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 11:59:37.988   396  6993 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 11:59:37.988  2228  6947 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 11:59:38.068  2228  6947 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 11:59:38.068  2228  6947 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:59:38.198  2228  6947 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 11:59:38.198  2228  6947 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:59:38.208  2228  6947 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 11:59:38.208  2228  6947 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 11:59:38.228  2228  6947 I CheckinTask: Sending checkin request (10592 bytes)
,07-05 11:59:38.528  2228  6947 I CheckinRequestBuilder: Checkin reason type: 11 attempt count: 1
,07-05 11:59:38.538   969   988 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings,
,07-05 11:59:38.538  2228  6947 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 11:59:38.668  1945  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
,07-05 11:59:38.678  1945  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,07-05 11:59:38.678  1945  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:59:38.678  1945  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-05 11:59:38.678  1945  2121 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:59:38.708  2228  6947 W CheckinRequestBuilder: awaiting user notification for token,
,07-05 11:59:38.718  1443  1463 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 11:59:38.718  1443  1463 D DotMatrix: [EventService] notificationPosted, eventType:1014
07-05 11:59:38.718  1339  1339 I RemoteViews: reapply : com.google.android.gms 4 40
07-05 11:59:38.718  1443  1463 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 11:59:38.728  2228  6947 I CheckinRequestBuilder: Classify the device as Phone.,
,07-05 11:59:38.748  2228  6947 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,07-05 11:59:38.758  2228  6947 I CheckinService: Checking schedule, now: 1467712778772 next: 1468249610764
,07-05 11:59:38.758  2228  6947 I CheckinService: active receiver: disabled
,07-05 11:59:38.758   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2228, uid=10024, userID:0
,07-05 11:59:38.788   969  1706 D PMS     : releaseWL(3fbcb5e3): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:38.818  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms,
,07-05 11:59:38.818  2228  2228 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,07-05 11:59:38.828  1945  5853 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,07-05 11:59:39.318   969   969 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3,
,07-05 11:59:41.618   969   989 I ActivityManager: Killing 6039:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
07-05 11:59:41.618   969   989 D Process : killProcessQuiet, pid=6039
,07-05 11:59:41.618   969   989 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:41.818   969  2390 I ActivityManager: Recipient 6039,
,07-05 11:59:43.188   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 11:59:43.958  1572  1771 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
07-05 11:59:43.958  1572  1771 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,07-05 11:59:46.038  1772  2139 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,07-05 11:59:46.048   969  1258 W SystemReader: Cannot find grip_rejection_width, use default value instead,
07-05 11:59:46.048   969   988 D PMS     : acquireWL(d15ba40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6639 10112 null
07-05 11:59:46.058  1772  2139 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-05 11:59:46.088   969  1026 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:59:46.108   969  1990 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6999 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,07-05 11:59:46.118  1772  2139 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
07-05 11:59:46.128   969  1676 D PMS     : releaseWL(d15ba40): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-05 11:59:46.128  1572  1572 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,07-05 11:59:46.138  6639  6639 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,07-05 11:59:46.138  6639  6639 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:59:46.148  1772  2139 E ExternalAccountType: Unsupported attribute readOnly,
,07-05 11:59:46.258   969   969 W PackageManager: Unable to load service info ResolveInfo{1d079bb8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-05 11:59:46.258   969   969 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 11:59:46.258   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 11:59:46.258   969   969 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 11:59:46.258   969   969 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-05 11:59:46.258   969   969 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 11:59:46.258   969   969 W PackageManager: ,	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:59:46.258   969   969 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:59:46.258   969   969 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 11:59:46.258   969   969 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-05 11:59:46.328   969  1758 I art     : Explicit concurrent mark sweep GC freed 26701(1505KB) AllocSpace objects, 7(640KB) LOS objects, 33% free, 18MB/28MB, paused 2.935ms total 185.149ms
,07-05 11:59:46.358   969  1706 D LocationManagerService: getProviders()=[passive],
,07-05 11:59:46.418   969   989 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7027 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,07-05 11:59:46.448  1623  1623 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED,
,07-05 11:59:46.448  1675  7047 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-05 11:59:46.458   969   969 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
07-05 11:59:46.448  1675  7047 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-05 11:59:46.458  1623  1623 I ContextualWidget: package com.google.android.gms changed
,07-05 11:59:46.458  1623  1875 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
07-05 11:59:46.458  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 11:59:46.458  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8,
07-05 11:59:46.458  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-05 11:59:46.458  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 11:59:46.458  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 11:59:46.458  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-05 11:59:46.458  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:59:46.458  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 11:59:46.458  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:59:46.468   969  1706 D Process : killProcessQuiet, pid=6731
07-05 11:59:46.468   969  1706 I ActivityManager: Killing 6731:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
07-05 11:59:46.468   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.attachApplicationLocked:6655 
,07-05 11:59:46.528   969  1981 I ActivityManager: Recipient 6731,
,07-05 11:59:46.618   969  1442 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 11:59:46.658  1842  1842 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,07-05 11:59:46.658  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 11:59:46.658  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
,07-05 11:59:46.668  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-05 11:59:46.808   969  1026 D LocationProviderProxy: applying state to connected service,
07-05 11:59:46.808   969  1981 D PMS     : acquireWL(28b360a2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:46.818   969   989 D PMS     : releaseWL(28b360a2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:46.828  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-05 11:59:46.828  1623  1623 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
07-05 11:59:46.828  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-05 11:59:46.848  1842  1842 V GmsNetworkLocationProvi: DISABLE
,07-05 11:59:46.848   969  1026 D LocationProviderProxy: applying state to connected service
,07-05 11:59:46.848   969  1758 D PMS     : acquireWL(1b1db133): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 11:59:46.848   969  1993 D PMS     : releaseWL(1b1db133): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-05 11:59:46.848  1623  1623 I Launcher: Deferring update until onResume
07-05 11:59:46.848  1623  1623 D Launcher: waitUntilResume // bindAppsUpdated
,07-05 11:59:46.858   969  1026 D PMS     : acquireWL(18142cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:46.858   969  1758 D PMS     : releaseWL(18142cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,07-05 11:59:46.858   969   969 D PMS     : acquireWL(17e87269): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:46.858   969  1276 D PMS     : releaseWL(17e87269): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:46.868  7050  7050 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate(),
,07-05 11:59:46.888  1623  1875 I ContextualWidget: MFU.onLoadComplete
,07-05 11:59:46.888  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 11:59:46.888  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 11:59:46.888  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
,07-05 11:59:46.888  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 11:59:46.888  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 11:59:46.888  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
,07-05 11:59:46.888  7050  7050 V Settings:HtcSettingsApplication: [7050/7050] onCreate(),
,07-05 11:59:46.908  2228  7078 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 11:59:46.918   969   989 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7080 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 11:59:46.918  2228  7078 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-05 11:59:46.928   969  1990 D PMS     : acquireWL(a0ccc25): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 11:59:46.938  2228  4461 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-05 11:59:46.958  7050  7095 D Settings:HtcWirelessFeatureFlags: id/is att sku: 118/false
,07-05 11:59:46.958   969  1981 D PMS     : releaseWL(a0ccc25): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-05 11:59:46.968  7080  7080 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-05 11:59:46.988  7050  7095 E Settings:HtcWrapHeaderInfo: no such activity!
,07-05 11:59:46.998  7050  7079 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
,07-05 11:59:47.008  7050  7079 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-05 11:59:47.028  7050  7079 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
,07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:59:47.038  7050  7079 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-05 11:59:47.058   969  1681 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
07-05 11:59:47.058  7050  7079 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-05 11:59:47.058  7050  7079 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
,07-05 11:59:47.068  7050  7077 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
07-05 11:59:47.068  7050  7077 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-05 11:59:47.068  7050  7077 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
,07-05 11:59:47.068  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true,
07-05 11:59:47.068  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-05 11:59:47.068  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true,
07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-05 11:59:47.078  7050  7077 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-05 11:59:47.078   969  4144 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi,
07-05 11:59:47.088  7050  7077 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
07-05 11:59:47.088  7050  7077 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-05 11:59:47.148   969  1276 D PMS     : acquireWL(1f5413ab): PARTIAL_WAKE_LOCK  AsyncService 0x1 7080 10167 null,
,07-05 11:59:47.148   969  4144 D PMS     : releaseWL(1f5413ab): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
07-05 11:59:47.158   969   989 D PMS     : acquireWL(96305a1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7080 10167 null
,07-05 11:59:47.178  6999  7110 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,07-05 11:59:47.278   969  1676 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0,
,07-05 11:59:47.278   969  1993 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0
07-05 11:59:47.278   969  4144 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969  1464 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969   989 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969  1990 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969  1681 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969  1981 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=7080, uid=10167, userID:0
,07-05 11:59:47.288   969  7074 D PMS     : releaseWL(96305a1): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-05 11:59:47.328  6999  7110 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 152 ms] updated apps [took 152 ms] 
,07-05 11:59:47.338   969   989 D Process : killProcessQuiet, pid=6757
,07-05 11:59:47.338   969   989 I ActivityManager: Killing 6757:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
07-05 11:59:47.338   969   989 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:47.388   969  1681 I ActivityManager: Recipient 6757
,07-05 11:59:48.148  1572  2200 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-05 11:59:48.148  1572  2200 D PhoneApp: -- N1 =0
,07-05 11:59:48.148  1572  2200 D PhoneApp: -- N2 =0
,07-05 11:59:48.148  1572  2200 D PhoneApp: -- N3 =0,
,07-05 11:59:48.328  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,07-05 11:59:48.328  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 +
07-05 11:59:48.328  1623  1836 I Prism.WidgetManager: onLoadItems() +
,07-05 11:59:48.398  1623  1836 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 11:59:48.568  1623  1836 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-05 11:59:48.658  1623  1836 W asset   : Copying FileAsset 0xad0514f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,07-05 11:59:48.718  1623  1836 E Prism.WidgetManager: The same lists. No need to update. skip it.,
07-05 11:59:48.718  1623  1836 I Prism.WidgetManager: onLoadItems() -
07-05 11:59:48.718  1623  1836 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23cbb669 -
,07-05 11:59:51.348   969  1990 D Process : killProcessQuiet, pid=6554,
07-05 11:59:51.348   969  1990 I ActivityManager: Killing 6554:com.google.android.gm/u0a106 (adj 15): empty #17
,07-05 11:59:51.348   969  1990 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:51.468   969   988 I ActivityManager: Recipient 6554
,07-05 11:59:51.868   969  1706 D Process : killProcessQuiet, pid=6669
07-05 11:59:51.868   969  1706 I ActivityManager: Killing 6669:com.htc.sense.mms/u0a64 (adj 15): empty #17
,07-05 11:59:51.868   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:51.968   969  1276 I ActivityManager: Recipient 6669
,07-05 11:59:52.408   969  1442 D Process : killProcessQuiet, pid=5711,
07-05 11:59:52.408   969  1442 I ActivityManager: Killing 5711:com.htc.musicenhancer/u0a49 (adj 15): empty #17
07-05 11:59:52.408   969  1442 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 11:59:52.478   969  1706 I ActivityManager: Recipient 5711,
,07-05 11:59:53.198   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,07-05 11:59:54.248   969  1256 D PMS     : acquireWL(1c65eb4): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
,07-05 11:59:54.248   969  1256 V AlarmManager: sending alarm PendingIntent{25895add: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712794247, Int=0
07-05 11:59:54.248   969   969 D PMS     : releaseWL(1c65eb4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 11:59:54.538  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 11:59:54.588  1945  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 11:59:54.598  1945  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 11:59:54.598  1945  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 11:59:54.598  1945  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 11:59:54.598  1945  2121 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 11:59:54.628  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,07-05 11:59:54.628  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 11:59:54.628  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,07-05 12:00:08.198   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:00:10.458   969  1026 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
,07-05 12:00:10.468   969  1026 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,07-05 12:00:10.468   969  1026 D PMS     : acquireWL(23d01877): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 969 1000 null,
,07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfo_proxy+
07-05 12:00:10.488   969  7113 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:00:10.488   396  7114 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
07-05 12:00:10.488   396  7114 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 12:00:10.548   396  7114 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,07-05 12:00:10.548   396  7114 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:00:10.548   969  7113 D libc    : [NET] android_getaddrinfo_proxy-, success
07-05 12:00:10.548   969  7113 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35322e38342e31),sn(),hints(known),family 0,flags 4
07-05 12:00:10.548   969  7113 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:00:10.588   969  7113 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data
,07-05 12:00:10.888   969  1569 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
07-05 12:00:10.888   969  1569 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
07-05 12:00:10.888   969  7113 D GpsLocationProvider:  [handleDownloadXtraData]inject done.,
07-05 12:00:10.888   969  7113 D PMS     : acquireWL(2823c513): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 969 1000 null,
07-05 12:00:10.888   969  1026 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
07-05 12:00:10.888   969  7113 D PMS     : releaseWL(23d01877): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
07-05 12:00:10.888   969  1026 D PMS     : releaseWL(2823c513): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,07-05 12:00:14.638   969  1256 D PMS     : acquireWL(3cf8e350): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
07-05 12:00:14.638   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136414, Int=0
07-05 12:00:14.638   969  1256 V AlarmManager: sending alarm PendingIntent{2b1b5949: PendingIntentRecord{74f724e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141216, Int=0
,07-05 12:00:14.638   969  1256 V AlarmManager: sending alarm PendingIntent{f90e47c: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712814642, Int=0
07-05 12:00:14.638   969  1256 V AlarmManager: sending alarm PendingIntent{3a374105: PendingIntentRecord{2e34655a com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1467712800000, Int=86400000
,07-05 12:00:14.718   969  1442 I ActivityManager: Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=7116 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a,
07-05 12:00:14.718   969   969 D PMS     : releaseWL(3cf8e350): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10074}
,07-05 12:00:14.778  7116  7116 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 12:00:14.778  7116  7116 I MultiDex: install
07-05 12:00:14.778  7116  7116 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 12:00:14.938  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:00:14.998  1945  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-05 12:00:14.998  1945  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:00:14.998  1945  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:00:14.998  1945  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:00:14.998  1945  2121 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:00:15.028  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,07-05 12:00:15.028  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
07-05 12:00:15.028  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,07-05 12:00:15.058   969  2390 I ActivityManager: Killing 5543:com.htc.mediamanager/u0a28 (adj 15): empty #17,
07-05 12:00:15.058   969  2390 D Process : killProcessQuiet, pid=5543
07-05 12:00:15.058   969  2390 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 12:00:15.158   969  1442 I ActivityManager: Recipient 5543
,07-05 12:00:19.778  7116  7131 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-05 12:00:22.128   969   969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,07-05 12:00:28.208   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:00:34.958   969   989 D PMS     : acquireWL(d637575): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
07-05 12:00:34.958   969   989 I BatteryService: n_update end
07-05 12:00:34.958  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:00:34.958   969   989 D PMS     : releaseWL(d637575): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:00:34.968  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:00:34.968   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:00:34.968  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:00:34.968   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:00:34.968  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:00:34.968   969   969 D PMS     : runPSCheck
07-05 12:00:34.968   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:00:34.968   969   969 D HtcPowerSaver: Checking...
07-05 12:00:34.968   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:00:34.968   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:00:34.968   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:00:34.968   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:00:34.968   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:00:34.968   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:00:34.968  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:00:34.968   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:00:34.968  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:00:34.968   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:00:34.968   969  1268 D WifiController: processMsg: DefaultState
07-05 12:00:34.968   969  1268 D WifiController: handleMessage: X
07-05 12:00:34.968  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:00:34.968   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:00:34.968   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:00:35.018  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:00:46.648   969  1256 D PMS     : acquireWL(2459a57b): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
07-05 12:00:46.648   969  1256 V AlarmManager: sending alarm PendingIntent{2b91f98: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712835046, Int=0
07-05 12:00:46.648   969  1256 V AlarmManager: sending alarm PendingIntent{1802f3f1: PendingIntentRecord{3cfb7bd6 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1467712846653, Int=0
07-05 12:00:46.648   969   969 D PMS     : acquireWL(34531e57): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
,07-05 12:00:46.658   969   969 D PMS     : releaseWL(2459a57b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,07-05 12:00:46.668   969  1279 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
07-05 12:00:46.668   969  1279 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
07-05 12:00:46.668   969  1279 D PMS     : releaseWL(34531e57): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,07-05 12:00:46.898  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:00:46.948  1945  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-05 12:00:46.948  1945  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:00:46.948  1945  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 12:00:46.948  1945  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:00:46.948  1945  2118 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:00:46.968  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:00:46.968  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,07-05 12:00:46.978  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,07-05 12:00:51.468  1572  1572 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,07-05 12:00:53.208   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:01:06.978   969  1256 D PMS     : acquireWL(35e7bb61): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
07-05 12:01:06.978   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196414, Int=0
,07-05 12:01:06.988   969  1256 V AlarmManager: sending alarm PendingIntent{2c024b47: PendingIntentRecord{5c5aea1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467712866985, Int=0
,07-05 12:01:07.008   969   969 D PMS     : releaseWL(35e7bb61): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,07-05 12:01:07.348  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:01:07.398  1945  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
,07-05 12:01:07.408  1945  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
07-05 12:01:07.408  1945  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:01:07.408  1945  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:01:07.408  1945  2121 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:01:07.448  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 12:01:07.448  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:01:07.448  6122  6122 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,07-05 12:01:17.318  1339  2561 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,07-05 12:01:17.318  1675  1675 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@e78b27c
,07-05 12:01:17.318  1339  2561 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,07-05 12:01:17.318   969  4144 D Process : killProcessQuiet, pid=6831
07-05 12:01:17.318   969  4144 I ActivityManager: Killing 6831:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
07-05 12:01:17.318   969  4144 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 12:01:17.438   969  1758 I ActivityManager: Recipient 6831
,07-05 12:01:32.688   969  1256 D PMS     : acquireWL(29053ed1): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
07-05 12:01:32.688   969  1256 V AlarmManager: sending alarm PendingIntent{37059d36: PendingIntentRecord{310e9437 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=186046, Int=0
07-05 12:01:32.688   969  1256 V AlarmManager: sending alarm PendingIntent{2de80da4: PendingIntentRecord{30cdf70d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189346, Int=0
07-05 12:01:32.698   969  1256 V AlarmManager: sending alarm PendingIntent{2a0656c2: PendingIntentRecord{2f2e3cd3 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1467712892696, Int=1800000
07-05 12:01:32.698   969  7074 D PMS     : acquireWL(b6a6010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.728   969  7074 D PMS     : acquireWL(21eff709): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.738   969  1981 D PMS     : acquireWL(2a671d0e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.748   969  1676 D PMS     : acquireWL(b17fac5): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.748   969  7074 D PMS     : releaseWL(2a671d0e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.928   969  2390 I art     : Explicit concurrent mark sweep GC freed 29400(1467KB) AllocSpace objects, 1(32KB) LOS objects, 33% free, 18MB/28MB, paused 1.981ms total 177.296ms,
07-05 12:01:32.928   969   969 D PMS     : releaseWL(29053ed1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,07-05 12:01:32.938   969   988 D PMS     : releaseWL(b6a6010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.948  2228  7141 I EventLogService: Aggregate from 1467712776063 (log), 1467711092620 (data)
,07-05 12:01:32.958  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:01:32.988   969  1990 D PMS     : releaseWL(21eff709): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:01:32.988   969  1676 D PMS     : acquireWL(25b7bd7d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.998   969  1681 D PMS     : releaseWL(25b7bd7d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:32.998   969  2390 D PMS     : acquireWL(16a5f472): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.018   969  1442 D PMS     : releaseWL(b17fac5): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.038   969  1990 D PMS     : acquireWL(375000c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.098   969  1758 D PMS     : acquireWL(2587b479): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms},
,07-05 12:01:33.118   969  1276 D PMS     : releaseWL(16a5f472): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
07-05 12:01:33.118   969  1681 D PMS     : acquireWL(1a7e61f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.138   969  1990 D PMS     : releaseWL(1a7e61f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.138  1945  7143 I VacuumService: Vacuum at: now=1467712893154 tag=VacuumService,
,07-05 12:01:33.178   969  7074 D PMS     : releaseWL(375000c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,07-05 12:01:33.178  1945  7144 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 12:01:33.178   969  1990 D PMS     : acquireWL(37949d6c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:33.208   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 12:01:33.228   969   988 D PMS     : releaseWL(37949d6c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,07-05 12:01:33.228   969  1676 D PMS     : acquireWL(1fc61f35): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
07-05 12:01:33.238  1945  7144 W Uploader: No account for auth token provided
,07-05 12:01:33.248   969  1464 D PMS     : releaseWL(1fc61f35): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfofornet-, err=8,
07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfo_proxy+
07-05 12:01:33.278  1945  7144 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:01:33.278   396  7146 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,07-05 12:01:33.278   396  7146 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 12:01:33.318   396  7146 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 12:01:33.318   396  7146 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:01:33.328  1945  7144 D libc    : [NET] android_getaddrinfo_proxy-, success,
,07-05 12:01:33.538  1945  7144 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
07-05 12:01:33.538  1945  7144 D libc    : [NET] android_getaddrinfofornet-, err=8,
07-05 12:01:33.538  1945  7144 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,07-05 12:01:33.538  1945  7144 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:01:33.638  1945  7144 W Uploader: No account for auth token provided,
,07-05 12:01:33.708  1945  7144 W Uploader:  no longer exists, so no auth token.,
,07-05 12:01:33.788  1945  7144 W Uploader: No account for auth token provided,
,07-05 12:01:33.858  1945  7144 W Uploader: No account for auth token provided,
,07-05 12:01:33.988  1945  7144 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
07-05 12:01:33.988  1945  7144 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,07-05 12:01:33.988  1945  7144 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:01:33.988  1945  7144 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:01:33.998  1945  7144 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:01:34.058  1443  1463 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 12:01:34.058  1443  1463 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-05 12:01:34.058  1443  1463 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 12:01:34.058  1339  1339 I RemoteViews: reapply : com.google.android.gms 3 40
,07-05 12:01:34.058  1945  7144 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
07-05 12:01:34.058  1945  7144 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
07-05 12:01:34.058  1945  7144 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,07-05 12:01:34.128   969  1990 D PMS     : releaseWL(2587b479): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:34.128   969  2390 D PMS     : acquireWL(22ea3a6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:34.168   969  1993 D PMS     : releaseWL(22ea3a6e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:34.178   969  7074 D PMS     : acquireWL(1a9c950f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:01:34.188   969  1276 D PMS     : releaseWL(1a9c950f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:01:35.118   969  1442 D PMS     : acquireWL(22b0399c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,07-05 12:01:35.118   969  1442 I BatteryService: n_update end
07-05 12:01:35.118   969  1442 D PMS     : releaseWL(22b0399c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:01:35.128   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:01:35.128   969   969 D NotificationService: plugged=true pluggin=true,
07-05 12:01:35.128   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:01:35.128   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:01:35.128   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:01:35.128  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:01:35.128   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:01:35.128   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:01:35.128  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:01:35.128   969   969 D PMS     : runPSCheck
07-05 12:01:35.128   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:01:35.128   969   969 D HtcPowerSaver: Checking...
07-05 12:01:35.128   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:01:35.128   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:01:35.128   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:01:35.128  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:01:35.128   969  1268 D WifiController: processMsg: DefaultState
07-05 12:01:35.128   969  1268 D WifiController: handleMessage: X
,07-05 12:01:35.128  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:01:35.128  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:01:35.128  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:01:35.128  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 12:01:35.138   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:01:35.138   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:01:35.178  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:01:43.218   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:01:58.228   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:02:18.228   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:02:20.398  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
,07-05 12:02:20.398   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 f0:f2:6d:22:99:3e]
07-05 12:02:20.398   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 f0:f2:6d:22:99:3e
,07-05 12:02:20.398  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
07-05 12:02:20.398  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
07-05 12:02:20.398  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age
,07-05 12:02:20.398  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 1 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c1]
07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c1
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1a:ef:42:f2:b0]
07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1a:ef:42:f2:b0
,07-05 12:02:20.408  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to wpa_bss_flush_by_age
07-05 12:02:20.408  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:02:20.408  1432  1432 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:16:a6:1f:06:5c]
,07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:16:a6:1f:06:5c
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:fe:c8:73:02:02]
07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:fe:c8:73:02:02
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 84:b2:61:1a:ce:73]
07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 84:b2:61:1a:ce:73
07-05 12:02:20.408   969  1788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 84:b2:61:12:64:93]
,07-05 12:02:20.408   969  1788 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 84:b2:61:12:64:93
,07-05 12:02:35.278   969  1990 D PMS     : acquireWL(213e3fa5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:02:35.288  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:02:35.278   969  1990 I BatteryService: n_update end
07-05 12:02:35.288   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:02:35.278   969  1990 D PMS     : releaseWL(213e3fa5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:02:35.288   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:02:35.288   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:02:35.288   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:02:35.288   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:02:35.288   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:02:35.288  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,07-05 12:02:35.288  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:02:35.288  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:02:35.288   969   969 D PMS     : runPSCheck
07-05 12:02:35.288   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:02:35.288   969   969 D HtcPowerSaver: Checking...
07-05 12:02:35.288   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:02:35.288   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:02:35.288   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:02:35.288   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:02:35.288   969  1268 D WifiController: processMsg: DefaultState
,07-05 12:02:35.288  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:02:35.288   969  1268 D WifiController: handleMessage: X
07-05 12:02:35.298   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:02:35.288  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:02:35.298   969   969 I HtcPowerSaver: << updateStatus
07-05 12:02:35.288  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:02:35.338  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:02:43.238   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:03:28.248   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:03:35.438   969  2390 D PMS     : acquireWL(3d838f7a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:03:35.438   969  2390 I BatteryService: n_update end
07-05 12:03:35.438   969  2390 D PMS     : releaseWL(3d838f7a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:03:35.438  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:03:35.438   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:03:35.438   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:03:35.438  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:03:35.438   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:03:35.438   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:03:35.438  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:03:35.438   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:03:35.438   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:03:35.438  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:03:35.438   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:03:35.448   969   969 D PMS     : runPSCheck
07-05 12:03:35.438   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:03:35.448   969   969 D HtcPowerSaver: Checking...
07-05 12:03:35.438   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:03:35.448   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:03:35.438   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:03:35.438   969  1268 D WifiController: processMsg: DefaultState
07-05 12:03:35.438   969  1268 D WifiController: handleMessage: X
07-05 12:03:35.438  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:03:35.438  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:03:35.448  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:03:35.448   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:03:35.448   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:03:35.498  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:03:38.248   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:03:39.798   969  1256 D PMS     : acquireWL(3917732b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
07-05 12:03:39.798   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256415, Int=0
07-05 12:03:39.798   969  1256 V AlarmManager: sending alarm PendingIntent{10f83121: PendingIntentRecord{392b2946 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1467713019806, Int=0
,07-05 12:03:39.828   969   969 D PMS     : releaseWL(3917732b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,07-05 12:03:53.258   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:03:57.278  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:03:57.358  1945  1969 I art     : Explicit concurrent mark sweep GC freed 36936(2MB) AllocSpace objects, 9(648KB) LOS objects, 47% free, 4MB/8MB, paused 1.107ms total 68.326ms,
,07-05 12:03:57.398  1945  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 12:03:57.398  1945  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:03:57.398  1945  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:03:57.398  1945  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:03:57.398  1945  2118 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:03:57.448  1443  1463 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
,07-05 12:03:57.448  1443  1463 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-05 12:03:57.448  1945  2118 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 12:03:57.448  1945  2118 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
07-05 12:03:57.458  1339  1339 I RemoteViews: reapply : com.google.android.gms 3 40
,07-05 12:03:57.458  1443  1463 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 12:03:57.458  6122  6162 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 12:03:57.458  6122  6162 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 12:03:57.458  6122  6162 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
07-05 12:03:57.458  6122  6162 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
07-05 12:03:57.458  6122  6162 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
07-05 12:03:57.458  6122  6162 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 12:03:57.458  6122  6162 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
,07-05 12:03:57.488  6122  6162 W System  : Ignoring header User-Agent because its value was null.,
,07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfo_proxy+
07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:03:57.488   396  7153 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:03:57.488   396  7153 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 12:03:57.488   396  7153 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 12:03:57.488   396  7153 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:03:57.488  6122  6162 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 12:04:13.258   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 12:04:35.598   969  1758 D PMS     : acquireWL(12c8aeb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:04:35.608  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:04:35.598   969  1758 I BatteryService: n_update end,
07-05 12:04:35.608  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:04:35.598   969  1758 D PMS     : releaseWL(12c8aeb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:04:35.608  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:04:35.608  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:04:35.608  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:04:35.608   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:04:35.608   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:04:35.608   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:04:35.608   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:04:35.608   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:04:35.608  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:04:35.608   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:04:35.608   969   969 D PMS     : runPSCheck
07-05 12:04:35.608   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:04:35.608   969   969 D HtcPowerSaver: Checking...
07-05 12:04:35.608   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:04:35.608   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:04:35.608   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:04:35.608   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:04:35.608   969  1268 D WifiController: processMsg: DefaultState
07-05 12:04:35.608  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:04:35.608   969  1268 D WifiController: handleMessage: X
,07-05 12:04:35.618   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:04:35.618   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:04:35.658  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:04:38.268   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:05:28.268   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:05:35.768   969  1676 D PMS     : acquireWL(3efea491): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
07-05 12:05:35.768   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:05:35.768   969  1676 I BatteryService: n_update end
07-05 12:05:35.768  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:05:35.768   969  1676 D PMS     : releaseWL(3efea491): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:05:35.768  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:05:35.768   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:05:35.768  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:05:35.768   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:05:35.768  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:05:35.778   969   969 D PMS     : runPSCheck
07-05 12:05:35.768   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:05:35.778   969   969 D HtcPowerSaver: Checking...
07-05 12:05:35.778   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:05:35.778   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:05:35.778   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:05:35.778   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:05:35.778   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:05:35.778  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:05:35.778   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:05:35.778  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:05:35.778   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:05:35.778   969  1268 D WifiController: processMsg: DefaultState
07-05 12:05:35.778   969  1268 D WifiController: handleMessage: X
07-05 12:05:35.778  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:05:35.778   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:05:35.778   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:05:35.828  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:05:38.278   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,07-05 12:05:53.278   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:06:13.288   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:06:35.918   969  2390 D PMS     : acquireWL(1b66ff6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:06:35.918   969  2390 I BatteryService: n_update end
07-05 12:06:35.918   969  2390 D PMS     : releaseWL(1b66ff6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:06:35.928  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:06:35.918   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:06:35.928  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:06:35.918   969   969 D PMS     : runPSCheck
07-05 12:06:35.928  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:06:35.918   969   969 D HtcPowerSaver: Checking...
07-05 12:06:35.928  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:06:35.918   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:06:35.928  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:06:35.928  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,07-05 12:06:35.928  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:06:35.938   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:06:35.938   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:06:35.938   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:06:35.938   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:06:35.938   969   969 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 12:06:35.938   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:06:35.938   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:06:35.938   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:06:35.938   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:06:35.938   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:06:35.938   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:06:35.938   969  1268 D WifiController: processMsg: DefaultState
07-05 12:06:35.938   969  1268 D WifiController: handleMessage: X
,07-05 12:06:35.978  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:06:38.298   448   448 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:07:36.078   969  1706 D PMS     : acquireWL(1f0ecff7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:07:36.078   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:07:36.078   969  1706 I BatteryService: n_update end
07-05 12:07:36.078   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:07:36.078   969  1706 D PMS     : releaseWL(1f0ecff7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:07:36.078   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:07:36.078   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:07:36.078   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:07:36.078   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:07:36.078   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:07:36.078   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:07:36.078   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:07:36.088   969   969 D PMS     : runPSCheck
07-05 12:07:36.078   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:07:36.088   969   969 D HtcPowerSaver: Checking...
07-05 12:07:36.078   969  1268 D WifiController: processMsg: DefaultState
07-05 12:07:36.088   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:07:36.078   969  1268 D WifiController: handleMessage: X
07-05 12:07:36.088  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:07:36.088  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:07:36.088  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:07:36.088  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:07:36.088  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,07-05 12:07:36.088  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:07:36.088  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:07:36.098   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,07-05 12:07:36.098   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:07:36.138  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:07:50.998   389   423 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,07-05 12:08:13.858  1572  1771 D ContactMessageStore: MSG_CHECK_DELETION >>
,07-05 12:08:13.858  1572  1771 D ContactMessageStore: mDeleteTask = null, bDeleting = false
07-05 12:08:13.858  1572  1771 D AccFlag : sku_id=118
07-05 12:08:13.858  1572  1771 D ContactMessageStore: MSG_CHECK_DELETION <<
,07-05 12:08:13.858  1572  7155 D ContactMessageStore: start background delete task...
,07-05 12:08:13.858  1572  7155 D ContactMessageStore: size: 0 , 0
,07-05 12:08:13.858  1572  7155 D ContactMessageStore: Background delete complete
,07-05 12:09:36.398   969  1442 D PMS     : acquireWL(cb5fe64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,07-05 12:09:36.408   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:09:36.398   969  1442 I BatteryService: n_update end
07-05 12:09:36.408   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:09:36.398   969  1442 D PMS     : releaseWL(cb5fe64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:09:36.408   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:09:36.408   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:09:36.408   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:09:36.408  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:09:36.408   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:09:36.408  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:09:36.408   969   969 D PMS     : runPSCheck
07-05 12:09:36.408   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:09:36.408   969   969 D HtcPowerSaver: Checking...
07-05 12:09:36.408   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:09:36.408   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:09:36.408   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:09:36.408  1339  1339 D PowerUI : closing low battery warning: level=100
,07-05 12:09:36.408   969  1268 D WifiController: processMsg: DefaultState
07-05 12:09:36.408   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:09:36.408   969  1268 D WifiController: handleMessage: X
07-05 12:09:36.408  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:09:36.418  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:09:36.418   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:09:36.418  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:09:36.418   969   969 I HtcPowerSaver: << updateStatus
07-05 12:09:36.418  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 12:09:36.458  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:10:36.558   969  4144 D PMS     : acquireWL(257f8cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:10:36.558   969  4144 I BatteryService: n_update end
07-05 12:10:36.558   969  4144 D PMS     : releaseWL(257f8cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:10:36.558  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:10:36.558   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:10:36.558  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,07-05 12:10:36.568   969   969 D PMS     : runPSCheck
07-05 12:10:36.558  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 12:10:36.568   969   969 D HtcPowerSaver: Checking...
,07-05 12:10:36.568  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:10:36.568   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:10:36.568  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:10:36.568  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,07-05 12:10:36.568   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:10:36.568   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:10:36.568   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:10:36.568   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:10:36.568   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:10:36.568   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,07-05 12:10:36.578   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:10:36.568   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:10:36.578   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:10:36.578   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:10:36.578   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:10:36.578   969  1268 D WifiController: processMsg: DefaultState
07-05 12:10:36.578   969  1268 D WifiController: handleMessage: X
07-05 12:10:36.578  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:10:36.618  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:11:36.718   969  1676 D PMS     : acquireWL(8d19582): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
07-05 12:11:36.718   969  1676 I BatteryService: n_update end
07-05 12:11:36.718   969  1676 D PMS     : releaseWL(8d19582): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:11:36.718   969  1046 D HtcPowerSaver: updateBatteryInfo,
07-05 12:11:36.728   969   969 D UsbnetService: BroadcastReceiver::onReceive+
,07-05 12:11:36.728   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:11:36.728   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:11:36.728   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:11:36.728   969   969 D PMS     : runPSCheck
07-05 12:11:36.728   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:11:36.728   969   969 D HtcPowerSaver: Checking...
,07-05 12:11:36.728   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:11:36.728   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:11:36.728   969  1268 D WifiController: processMsg: DeviceActiveState
,07-05 12:11:36.728   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:11:36.728   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:11:36.728  1339  1339 D PowerUI : closing low battery warning: level=100
,07-05 12:11:36.728   969  1268 D WifiController: processMsg: DefaultState
07-05 12:11:36.728  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:11:36.728  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:11:36.728  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:11:36.728  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:11:36.728  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-05 12:11:36.728  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:11:36.728   969  1268 D WifiController: handleMessage: X
,07-05 12:11:36.738   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:11:36.738   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:11:36.778  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:12:36.878  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1,
07-05 12:12:36.878   969  2390 D PMS     : acquireWL(1567493): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:12:36.878  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:12:36.878   969  2390 I BatteryService: n_update end
07-05 12:12:36.878  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:12:36.878   969  2390 D PMS     : releaseWL(1567493): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:12:36.878  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:12:36.878  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:12:36.878  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:12:36.878   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:12:36.878   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:12:36.878  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:12:36.878   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:12:36.878   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:12:36.878   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:12:36.878   969   969 D PMS     : runPSCheck
07-05 12:12:36.878   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:12:36.878   969   969 D HtcPowerSaver: Checking...
07-05 12:12:36.878   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:12:36.878   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:12:36.878   969  1268 D WifiController: processMsg: DeviceActiveState
,07-05 12:12:36.878   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:12:36.878   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:12:36.888   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,07-05 12:12:36.878   969  1268 D WifiController: processMsg: DefaultState
07-05 12:12:36.888   969   969 I HtcPowerSaver: << updateStatus
07-05 12:12:36.878   969  1268 D WifiController: handleMessage: X
,07-05 12:12:36.938  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:13:22.328   969  1256 D PMS     : acquireWL(26069cd0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
07-05 12:13:22.328   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=376415, Int=0
07-05 12:13:22.328   969  1256 V AlarmManager: sending alarm PendingIntent{d7854c9: PendingIntentRecord{28787ce com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=938757, Int=0
,07-05 12:13:22.348  3026  3177 I bt-btm  : Received oneshot timer event complete,
07-05 12:13:22.348  3026  3177 I bt-btm  : btm_ble_timeout
07-05 12:13:22.348   969   969 D PMS     : releaseWL(26069cd0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1002}
07-05 12:13:22.348  3026  3177 I bt-btm  : btm_gen_resolvable_private_addr
07-05 12:13:22.348   969  1681 D PMS     : acquireWL(3669c6ef): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3026 1002 null
,07-05 12:13:22.358  3026  3177 D bt-btm  : btm_ble_rand_enc_complete,
,07-05 12:13:22.368  3026  3177 I bt-btm  : btm_gen_resolve_paddr_low
07-05 12:13:22.368  3026  3177 D bt-smp  : smp_encrypt_data
07-05 12:13:22.368  3026  3177 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
07-05 12:13:22.368  3026  3177 W bt-smp  : Plain text(LSB ~ MSB) = 26 b9 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 12:13:22.368  3026  3177 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b de 00 9e 17 c7 63 fc 0e 94 21 42 ac 05 bc a7 
07-05 12:13:22.368  3026  3177 I bt-btm  : btm_gen_resolve_paddr_cmpl
07-05 12:13:22.368  3026  3177 W bt-btm  : Stopping oneshot timer
07-05 12:13:22.368  3026  3177 D bt-btm  : Starting oneshot timer type:103 timeout:900s
,07-05 12:13:23.358   969   989 D PMS     : releaseWL(3669c6ef): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,07-05 12:13:37.038   969  1758 D PMS     : acquireWL(3180b5fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
,07-05 12:13:37.038   969  1758 I BatteryService: n_update end,
,07-05 12:13:37.038  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:13:37.038   969  1758 D PMS     : releaseWL(3180b5fc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:13:37.038  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:13:37.038   969  1046 D HtcPowerSaver: updateBatteryInfo,
07-05 12:13:37.038  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:13:37.048   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:13:37.038  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:13:37.048  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:13:37.048   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:13:37.048   969   969 D PMS     : runPSCheck
07-05 12:13:37.048   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:13:37.048   969   969 D HtcPowerSaver: Checking...
,07-05 12:13:37.048   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:13:37.048   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:13:37.048   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:13:37.048   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:13:37.048   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:13:37.048  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:13:37.048   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:13:37.048   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:13:37.048   969  1268 D WifiController: processMsg: DefaultState
,07-05 12:13:37.048   969  1268 D WifiController: handleMessage: X
07-05 12:13:37.048  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:13:37.058   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:13:37.058   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:13:37.098  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:13:49.958  6122  6122 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
07-05 12:13:49.958   969  1256 D PMS     : acquireWL(309852da): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
07-05 12:13:49.958   969  1256 V AlarmManager: sending alarm PendingIntent{8b5e30b: PendingIntentRecord{2affe7dc com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713389316, Int=0
07-05 12:13:49.958   969  1256 V AlarmManager: sending alarm PendingIntent{62135e8: PendingIntentRecord{1400d401 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936370, Int=0
,07-05 12:13:49.968   969  1256 V AlarmManager: sending alarm PendingIntent{f26051c: PendingIntentRecord{1866e525 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806291, Int=0
07-05 12:13:49.968   969  1256 V AlarmManager: sending alarm PendingIntent{325da4e7: PendingIntentRecord{1dd94200 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1467713629957, Int=0
,07-05 12:13:49.968   969  1706 D PMS     : acquireWL(2d5a883): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1945 10024 WorkSource{10024 com.google.android.gms},
,07-05 12:13:49.978   969  4144 D PMS     : releaseWL(2d5a883): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:13:49.978  6886  6886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
07-05 12:13:49.988  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 12:13:49.988   969   969 D PMS     : releaseWL(309852da): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,07-05 12:13:49.998  6886  7157 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-05 12:13:49.998  6886  7157 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 12:13:49.998  6886  7157 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-05 12:13:50.008  6886  7157 D PowerUsageService: repeat time = 1467714530013
,07-05 12:13:50.038  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 12:13:50.038  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:13:50.038  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:13:50.038  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:13:50.048  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:13:50.068  6122  6122 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,07-05 12:13:50.078  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:13:50.078  6886  7157 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,07-05 12:13:50.098  6886  7157 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-05 12:13:50.098  6886  7157 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 1000, sipper.name = com.android.settings:remote
07-05 12:13:50.098  6886  7157 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10024, sipper.name = com.google.android.gms.persistent
07-05 12:13:50.098  6886  7157 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 12:13:50.108  6886  7157 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-05 12:13:50.108  6886  7157 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10041, sipper.name = com.htc.dotmatrixevent,
07-05 12:13:50.108  6886  7157 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 0, sipper.name = null
,07-05 12:13:50.108  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
07-05 12:13:50.108  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:13:50.108  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-05 12:13:50.108  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:13:50.118  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:13:50.128   969  1706 D PMS     : acquireWL(2b86e25c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1945 10024 WorkSource{10024 com.google.android.gms},
,07-05 12:13:50.128  1945  2924 D GCM     : Message class com.google.f.a.a.i
,07-05 12:13:50.128   969  1758 D PMS     : releaseWL(2b86e25c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:13:50.138  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:13:50.148  6886  7157 D PowerUsageService: calcPower(), no data,
,07-05 12:13:50.178  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 12:13:50.178  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:13:50.178  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:13:50.178  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:13:50.188  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:13:50.218  6122  6122 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,07-05 12:13:50.448  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:13:50.498  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
07-05 12:13:50.498  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:13:50.498  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:13:50.498  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:13:50.498  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:13:50.528  6122  6122 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 12:13:50.528  6122  6122 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,07-05 12:13:50.548  6122  6122 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-05 12:13:50.558  6122  6122 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2),
,07-05 12:13:50.568  1842  4493 D DeviceConnectionService: client connected with version: 7571000
,07-05 12:14:05.228   969  1256 D PMS     : acquireWL(12d802b6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
07-05 12:14:05.228   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=976415, Int=0
07-05 12:14:05.238   969  1256 V AlarmManager: sending alarm PendingIntent{2342af24: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713645232, Int=0
,07-05 12:14:05.268   969   969 D PMS     : releaseWL(12d802b6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,07-05 12:14:05.478  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:14:05.528  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:14:05.528  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:14:05.528  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 12:14:05.528  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:14:05.538  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:14:05.558  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:14:05.558  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:14:05.558  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,07-05 12:14:25.568   969  1256 D PMS     : acquireWL(2e422954): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
07-05 12:14:25.568   969  1256 V AlarmManager: sending alarm PendingIntent{25bb60fd: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713665573, Int=0
,07-05 12:14:25.568   969   969 D PMS     : releaseWL(2e422954): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 12:14:25.818  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:14:25.868  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-05 12:14:25.868  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:14:25.868  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:14:25.868  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:14:25.868  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:14:25.888  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:14:25.888  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
07-05 12:14:25.888  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,07-05 12:14:34.888   969  1256 D PMS     : acquireWL(19ee7197): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
,07-05 12:14:34.888   969  1256 V AlarmManager: sending alarm PendingIntent{22ec8f84: PendingIntentRecord{368b836d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1467713674895, Int=0
,07-05 12:14:34.898   969   969 D PMS     : releaseWL(19ee7197): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,07-05 12:14:34.898   969   989 D PMS     : acquireWL(ec05ba2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6886 1000 null,
,07-05 12:14:34.898  6886  7161 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
,07-05 12:14:34.908  6886  7161 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,07-05 12:14:34.908  6886  7161 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,07-05 12:14:34.908  6886  7161 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1467781200000, randomSettingOnTime = 1467780587000
,07-05 12:14:34.908  6886  7161 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1467759600000, randomSettingOffTime = 1467762089000,
,07-05 12:14:34.918  6886  7161 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false,
,07-05 12:14:34.918  6886  7161 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true,
07-05 12:14:34.918  6886  7161 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false,
,07-05 12:14:34.918   969  4144 D PMS     : releaseWL(ec05ba2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,07-05 12:14:45.898   969  1256 D PMS     : acquireWL(18651ff0): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
,07-05 12:14:45.898   969  1256 V AlarmManager: sending alarm PendingIntent{1669e969: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713685904, Int=0
07-05 12:14:45.898   969   969 D PMS     : releaseWL(18651ff0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 12:14:46.238  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:14:46.278  1945  7075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:14:46.278  1945  7075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:14:46.278  1945  7075 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:14:46.278  1945  7075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:14:46.288  1945  7075 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:14:46.298  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:14:46.298  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:14:46.298  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,07-05 12:14:46.468   969   989 I art     : Explicit concurrent mark sweep GC freed 32459(1615KB) AllocSpace objects, 5(484KB) LOS objects, 33% free, 18MB/28MB, paused 2.774ms total 166.108ms,
,07-05 12:15:06.298   969  1256 D PMS     : acquireWL(1b2bec23): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
07-05 12:15:06.308   969  1256 V AlarmManager: sending alarm PendingIntent{11059eac: PendingIntentRecord{1ac52775 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1036415, Int=0
,07-05 12:15:06.308   969  1256 V AlarmManager: sending alarm PendingIntent{1912fed9: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713706313, Int=0
,07-05 12:15:06.328   969   969 D PMS     : releaseWL(1b2bec23): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,07-05 12:15:06.578  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:15:06.638  1945  4142 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:15:06.638  1945  4142 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:15:06.638  1945  4142 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:15:06.638  1945  4142 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:15:06.648  1945  4142 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:15:06.698  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,07-05 12:15:06.698  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:15:06.698  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,07-05 12:15:26.708   969  1256 D PMS     : acquireWL(20beee6f): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
,07-05 12:15:26.708   969  1256 V AlarmManager: sending alarm PendingIntent{36cb877c: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713726710, Int=0
,07-05 12:15:26.708   969   969 D PMS     : releaseWL(20beee6f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 12:15:27.008  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:15:27.068  1945  7075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:15:27.068  1945  7075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:15:27.068  1945  7075 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:15:27.068  1945  7075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:15:27.078  1945  7075 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:15:27.108  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:15:27.108  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:15:27.108  6122  6122 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,07-05 12:15:37.358   969   988 D PMS     : acquireWL(17d6f5fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
07-05 12:15:37.358   969   988 I BatteryService: n_update end
07-05 12:15:37.358   969   988 D PMS     : releaseWL(17d6f5fe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:15:37.358   969   969 D NotificationService: plugged=true pluggin=true
,07-05 12:15:37.358   969   969 D UsbnetService: BroadcastReceiver::onReceive+
,07-05 12:15:37.358   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:15:37.358   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:15:37.368   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:15:37.358   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:15:37.368  1339  1339 D PowerUI : closing low battery warning: level=100
,07-05 12:15:37.358   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:15:37.358   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:15:37.358   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:15:37.358   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:15:37.358   969  1268 D WifiController: processMsg: DefaultState
07-05 12:15:37.368   969   969 D PMS     : runPSCheck
07-05 12:15:37.358   969  1268 D WifiController: handleMessage: X
07-05 12:15:37.368   969   969 D HtcPowerSaver: Checking...
07-05 12:15:37.368  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,07-05 12:15:37.368   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:15:37.368  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:15:37.368  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:15:37.368  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:15:37.368  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:15:37.368  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:15:37.378   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:15:37.378   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:15:37.418  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:15:47.118   969  1256 D PMS     : acquireWL(11bdc7ac): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072},
07-05 12:15:47.118   969  1256 V AlarmManager: sending alarm PendingIntent{3bac9c75: PendingIntentRecord{2e99ba8d com.android.vending startService}}, i=null, t=0, cnt=1, w=1467713747123, Int=0
07-05 12:15:47.118   969   969 D PMS     : releaseWL(11bdc7ac): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,07-05 12:15:47.408  1945  1945 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:15:47.458  1945  1969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:15:47.458  1945  1969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:15:47.458  1945  1969 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:15:47.458  1945  1969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:15:47.468  1945  1969 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:15:47.498  6122  6122 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:15:47.498  6122  6122 D Finsky  : [1] 5.onFinished: Installation state replication failed.,
07-05 12:15:47.508  6122  6122 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,07-05 12:17:37.678  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:17:37.678   969  1981 D PMS     : acquireWL(2bf4504f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:17:37.678  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:17:37.678   969  1981 I BatteryService: n_update end
07-05 12:17:37.678  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:17:37.678   969  1981 D PMS     : releaseWL(2bf4504f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:17:37.678  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:17:37.678  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:17:37.678  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:17:37.678   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:17:37.678   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:17:37.678   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:17:37.678   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:17:37.678  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:17:37.678   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:17:37.688   969   969 D PMS     : runPSCheck
07-05 12:17:37.688   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:17:37.688   969   969 D HtcPowerSaver: Checking...
07-05 12:17:37.688   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:17:37.688   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:17:37.688   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:17:37.688   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:17:37.688   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:17:37.688   969  1268 D WifiController: processMsg: DefaultState
,07-05 12:17:37.688   969  1268 D WifiController: handleMessage: X
,07-05 12:17:37.688   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:17:37.688   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:17:37.728  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:17:50.998   389   423 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,07-05 12:18:07.678   969  1026 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 12:18:37.828   969  1676 D PMS     : acquireWL(139873dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
,07-05 12:18:37.828   969  1676 I BatteryService: n_update end
07-05 12:18:37.828   969  1676 D PMS     : releaseWL(139873dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:18:37.838  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:18:37.828   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:18:37.838  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:18:37.838  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:18:37.838   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:18:37.838   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:18:37.838   969   969 D PMS     : runPSCheck
07-05 12:18:37.838   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:18:37.838   969   969 D HtcPowerSaver: Checking...
07-05 12:18:37.838   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:18:37.838   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:18:37.838   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:18:37.838  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:18:37.838  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:18:37.838  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:18:37.838  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:18:37.838   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:18:37.838   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:18:37.848   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:18:37.838   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:18:37.848   969   969 I HtcPowerSaver: << updateStatus
07-05 12:18:37.838   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:18:37.838   969  1268 D WifiController: processMsg: DefaultState
07-05 12:18:37.838   969  1268 D WifiController: handleMessage: X
,07-05 12:18:37.888  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:19:37.998  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:19:37.998   969   989 D PMS     : acquireWL(35e8ce5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
07-05 12:19:37.998  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-05 12:19:37.998   969   989 I BatteryService: n_update end
07-05 12:19:37.998  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:19:37.998   969   989 D PMS     : releaseWL(35e8ce5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:19:37.998  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:19:37.998  1339  1339 D PowerUI : closing low battery warning: level=100
07-05 12:19:37.998  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:19:37.998   969  1046 D HtcPowerSaver: updateBatteryInfo
07-05 12:19:37.998   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:19:37.998  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:19:37.998   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:19:37.998   969   969 D NotificationService: plugged=true pluggin=true
07-05 12:19:37.998   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:19:37.998   969   969 D PMS     : runPSCheck
07-05 12:19:37.998   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:19:37.998   969   969 D HtcPowerSaver: Checking...
07-05 12:19:37.998   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:19:37.998   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:19:37.998   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:19:37.998   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:19:37.998   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:19:37.998   969  1268 D WifiController: processMsg: DefaultState
07-05 12:19:37.998   969  1268 D WifiController: handleMessage: X
,07-05 12:19:38.008   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:19:38.008   969   969 I HtcPowerSaver: << updateStatus
,07-05 12:19:38.058  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:21:38.318   969  1990 D PMS     : acquireWL(1c4df3ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
07-05 12:21:38.318   969  1990 I BatteryService: n_update end
07-05 12:21:38.318   969  1990 D PMS     : releaseWL(1c4df3ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:21:38.318   969  1046 D HtcPowerSaver: updateBatteryInfo
,07-05 12:21:38.318  1339  1339 D PowerUI : closing low battery warning: level=100
,07-05 12:21:38.328  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1,
,07-05 12:21:38.328  1443  1443 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,07-05 12:21:38.328   969   969 D NotificationService: plugged=true pluggin=true
,07-05 12:21:38.328  1443  1443 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:21:38.328   969   969 D PMS     : runPSCheck
07-05 12:21:38.328  1339  1708 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:21:38.328   969   969 D HtcPowerSaver: Checking...
07-05 12:21:38.328  3026  3103 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:21:38.328   969   969 I HtcPowerSaver: >> updateStatus
07-05 12:21:38.328   969   969 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:21:38.328  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:21:38.328   969   969 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:21:38.328   969   969 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
07-05 12:21:38.328   969   969 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:21:38.338   969   969 I HtcPowerSaver: << updateStatus
07-05 12:21:38.328   969   969 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:21:38.338   969  1268 D WifiController: battery changed pluggedType: 2
07-05 12:21:38.338   969  1268 D WifiController: handleMessage: E msg.what=155652
07-05 12:21:38.338   969  1268 D WifiController: processMsg: DeviceActiveState
07-05 12:21:38.338   969  1268 D WifiController: processMsg: StaEnabledState
07-05 12:21:38.338   969  1268 D WifiController: processMsg: DefaultState
07-05 12:21:38.338   969  1268 D WifiController: handleMessage: X
,07-05 12:21:38.378  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1401000ms),07-05 12:22:21.128  7165  7168 E cutils-trace: Error opening trace file: Permission denied (13)
07-05 12:22:21.378  7165  7165 D CustomizationManager: ====startRecUseTime====
07-05 12:22:21.378  7165  7165 D htc.customization.log.level:  is 
07-05 12:22:21.378  7165  7165 W CustomizationLogLevel: Level value is invalid, use default level 2
07-05 12:22:21.518  7165  7165 D CustomizationManager:  Read ACC file spent 0.097 (s)
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__032
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__031
07-05 12:22:21.528  7165  7165 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 12:22:21.528  7165  7165 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-05 12:22:21.528  7165  7165 I CustomizationCIDLoader: Parsing tag category name = system
07-05 12:22:21.528  7165  7165 I CustomizationCIDLoader: Parsing tag category name = application
07-05 12:22:21.528  7165  7165 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: Parsing tag category name = ACC
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 42507
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 21902
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23420
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 22299
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 24002
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23210
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23205
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23806
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23430
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23408
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 27205
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-05 12:22:21.538  7165  7165 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-05 12:22:21.548  7165  7165 D CustomizationManager:  Read CID file spent 0.165 (s)
07-05 12:22:21.548  7165  7165 D CustomizationManager:  All configurations done spent 0.165 (s)
07-05 12:22:21.668   969  1442 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=7165, uid=2000 userid=0
07-05 12:22:21.668   969  1028 D Process : killProcessQuiet, pid=5440
07-05 12:22:21.668   969  1028 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
07-05 12:22:21.668   969  1028 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
07-05 12:22:21.668   969  1028 I ActivityManager: Killing 5440:com.test.thalitest/u0a195 (adj 0): stop com.test.thalitest
07-05 12:22:21.778   969  1080 W PackageSettings: Skipping PackageSetting{27f7ce59 com.example.hello/10374} due to missing metadata
07-05 12:22:21.858   969  1990 I ActivityManager: Recipient 5440
07-05 12:22:21.858   969  1758 I WindowState: WIN DEATH: Window{1189a505 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:22:21.858   969  1268 D WifiService: Client connection lost with reason: 4
07-05 12:22:21.868  1503  1503 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{15e559b2 uid 10195 pid 5440} (c)'
07-05 12:22:21.898   969  1028 E libprocessgroup: failed to kill 1 processes for processgroup 5440
07-05 12:22:21.898   969  1028 W ActivityManager: ProcessRecord{94fa26b 5440:com.test.thalitest/u0a195} has been replaced to new process null
07-05 12:22:21.908   969  1028 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-05 12:22:21.908   969  1028 W ActivityManager: Unable to retrieve gids
07-05 12:22:21.908   969  1028 W ActivityManager: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 12:22:21.908   969  1028 W ActivityManager: 	at android.app.ApplicationPackageManager.getPackageGids(ApplicationPackageManager.java:193)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3288)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3233)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3114)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1314)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2027)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1565)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2525)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4960)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:6373)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:6161)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:6222)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService.access$400(ActivityManagerService.java:244)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1574)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:22:21.908   969  1028 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 12:22:21.928   969  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7183 uid=10195 gids={50195, 9997} abi=armeabi-v7a
07-05 12:22:21.928   969  1028 I ActivityManager:   Force finishing activity ActivityRecord{22d26af2 u0 com.test.thalitest/.MainActivity t104}
07-05 12:22:21.978   969  1080 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
07-05 12:22:21.978   969  1080 I ActivityManager: Killing 7183:com.test.thalitest/u0a195 (adj -100): stop com.test.thalitest
07-05 12:22:21.978   969  1080 D Process : killProcessQuiet, pid=7183
07-05 12:22:21.978   969  1080 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
07-05 12:22:21.998   969  1080 W ActivityManager: ProcessRecord{426f1c8 7183:com.test.thalitest/u0a195} has been replaced to new process null
07-05 12:22:21.998   969  1080 I ActivityManager:   Force finishing activity ActivityRecord{22d26af2 u0 com.test.thalitest/.MainActivity t104 f}
07-05 12:22:21.998   969  1080 W ActivityManager: Duplicate finish request for ActivityRecord{22d26af2 u0 com.test.thalitest/.MainActivity t104 f}
07-05 12:22:22.048   969  1681 D Process : killProcessQuiet, pid=7183
07-05 12:22:22.048   969  1681 W ActivityManager: No pending application record for pid 7183 (IApplicationThread android.app.ApplicationThreadProxy@2af01261); dropping process
07-05 12:22:22.048   969  1681 D Process : com.android.server.am.ActivityManagerService.attachApplicationLocked:6457 com.android.server.am.ActivityManagerService.attachApplication:6666 android.app.ActivityManagerNative.onTransact:486 
07-05 12:22:22.058  1443  1443 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-05 12:22:22.058  1443  1443 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-05 12:22:22.068   969   989 D PMS     : acquireWL(5d79186): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
07-05 12:22:22.078  1842  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 12:22:22.078   969  1258 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-05 12:22:22.078   969  1264 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
07-05 12:22:22.078   969  1264 V NetworkPolicy: writePolicyLocked()
07-05 12:22:22.078   969  1442 D PMS     : releaseWL(5d79186): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:22:22.078   969  1990 W ActivityManager: Spurious death for ProcessRecord{94fa26b 0:com.test.thalitest/u0a195}, curProc for 5440: null
07-05 12:22:22.088  1772  2139 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-05 12:22:22.088   969  1263 D PMS     : acquireWL(280b4012): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
07-05 12:22:22.108  1772  2139 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-05 12:22:22.108   969  1264 V NetworkPolicy: updateNetworkEnabledLocked()
07-05 12:22:22.108   969  1264 V NetworkPolicy: updateNotificationsLocked()
07-05 12:22:22.118  1623  1623 I art     : Explicit concurrent mark sweep GC freed 4250(192KB) AllocSpace objects, 4(446KB) LOS objects, 32% free, 32MB/48MB, paused 1.496ms total 93.274ms
07-05 12:22:22.118  1734  7204 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-05 12:22:22.128  1675  7205 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
07-05 12:22:22.128  1623  1623 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
07-05 12:22:22.128  1623  1623 I ContextualWidget: package com.test.thalitest removed
07-05 12:22:22.148  1772  2139 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-05 12:22:22.158   969  1263 D PMS     : releaseWL(280b4012): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-05 12:22:22.158  1572  1572 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-05 12:22:22.158  1675  7205 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-05 12:22:22.158   969  1758 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
07-05 12:22:22.168  1772  2139 E ExternalAccountType: Unsupported attribute readOnly
07-05 12:22:22.218   969   969 W PackageManager: Unable to load service info ResolveInfo{3293103c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-05 12:22:22.218   969   969 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 12:22:22.218   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:22:22.218   969   969 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 12:22:22.218   969   969 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-05 12:22:22.218   969   969 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 12:22:22.218   969   969 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:22:22.218   969   969 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:22:22.218   969   969 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 12:22:22.218   969   969 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-05 12:22:22.278   969  1080 I art     : Explicit concurrent mark sweep GC freed 32925(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 18MB/28MB, paused 2.376ms total 229.775ms
07-05 12:22:22.278   969   969 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 12:22:22.278  1623  1875 I ContextualWidget: MFU.onDataSetChanged
07-05 12:22:22.278  1623  1875 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-05 12:22:22.278  1623  1875 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-05 12:22:22.288   969  1301 D TaskPersister: removeObsoleteFile: deleting file=104_task.xml
07-05 12:22:22.298   969  1301 D TaskPersister: removeObsoleteFile: deleting file=104_task_thumbnail.png
07-05 12:22:22.318  7207  7207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
07-05 12:22:22.328   969  1026 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-05 12:22:22.328   969  1036 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-05 12:22:22.328   969  1036 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:22:22.328   969  1036 D StatusBarManagerService: hiding MENU key
07-05 12:22:22.328   969  1036 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-05 12:22:22.328   969  1036 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:22:22.328   969  1036 D StatusBarManagerService: hiding MENU key
07-05 12:22:22.338  1623  1623 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-05 12:22:22.338  1623  1875 I ContextualWidget: MFU.onLoadComplete
07-05 12:22:22.338  1623  1875 W SystemReader: Cannot find enable_download_option, use default value instead
07-05 12:22:22.338  1623  1875 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 12:22:22.338  1623  1875 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-05 12:22:22.338  1623  1875 I ContextualWidget: sync all data, download=0 recommend=4
07-05 12:22:22.338  1623  1875 I ContextualWidget: sync all data, mode=GettingOut count=1
07-05 12:22:22.338  1623  1875 I ContextualWidget: notifyDataChanged, list size 3
07-05 12:22:22.348  1623  1623 I ThreadedRenderer: Defer allocateBuffers to drawing time
07-05 12:22:22.348   969  2390 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5440 uid 10195
07-05 12:22:22.348   969  1026 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-05 12:22:22.358   969  2390 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 12:22:22.368  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false)
07-05 12:22:22.378   969  1080 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7232 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
07-05 12:22:22.388   969  1706 I ActivityManager: Killing 6855:com.htc.bgp/u0a11 (adj 15): empty #17
07-05 12:22:22.388   969  1706 D Process : killProcessQuiet, pid=6855
07-05 12:22:22.388   969  1706 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-05 12:22:22.498   969  1990 I ActivityManager: Recipient 6855
07-05 12:22:22.608  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-05 12:22:22.608  1623  1836 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-05 12:22:22.628  1623  1623 I Launcher: Deferring update until onResume
07-05 12:22:22.628   969  2390 D PMS     : acquireWL(beae8ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1945 10024 WorkSource{10024 com.google.android.gms}
07-05 12:22:22.628  1623  1623 D Launcher: waitUntilResume // bindAppsRemoved
07-05 12:22:22.628  1945  1945 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 12:22:22.628  1945  1945 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 12:22:22.648   969   988 D PMS     : releaseWL(beae8ad): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:22:22.678  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:22:22.678  2228  2228 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:22:22.688  2228  7259 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 12:22:22.688  2228  7259 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 12:22:22.688  2228  2228 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:22:22.688  2228  2228 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:22:22.708   969  1276 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7262 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
07-05 12:22:22.738  2228  7259 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 12:22:22.748   410   410 I art     : Explicit concurrent mark sweep GC freed 8681(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 246us total 29.843ms
07-05 12:22:22.768  2228  7284 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 12:22:22.768  2228  7284 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 12:22:22.768   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 308us total 26.411ms
07-05 12:22:22.768  2228  7284 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 12:22:22.768  2228  7284 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 12:22:22.788  2228  7284 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 12:22:22.788  2228  7284 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 12:22:22.788  2228  7284 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 12:22:22.798   410   410 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 225us total 23.022ms
07-05 12:22:22.798  2228  7284 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 12:22:22.798  2228  7284 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 12:22:22.798  2228  7284 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 12:22:22.808  2228  7284 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
07-05 12:22:22.808  2228  7284 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-05 12:22:22.808  2228  7284 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
07-05 12:22:22.808   969   988 D PMS     : acquireWL(380f51c7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2228 10024 null
07-05 12:22:22.808  1945  1945 I ConfigService: onCreate
07-05 12:22:22.818  2228  2228 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-05 12:22:22.818   969  4144 D PMS     : releaseWL(380f51c7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
07-05 12:22:22.828  2228  7285 W BaseAppContext: Using Auth Proxy for data requests.
07-05 12:22:22.838  2228  7285 W BaseAppContext: Using Auth Proxy for data requests.
07-05 12:22:22.858  2228  7291 I PeopleContactsSync: CP2 sync disabled
07-05 12:22:22.858   969  1758 D PMS     : acquireWL(9d44819): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10024 WorkSource{10024 com.google.android.gms}
07-05 12:22:22.858   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2228, uid=10024, userID:0
07-05 12:22:22.868  2228  4461 I Icing   : doRemovePackageData com.test.thalitest
07-05 12:22:22.868   969  4144 D PMS     : releaseWL(9d44819): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:22:23.078  7262  7262 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-05 12:22:23.078  7262  7262 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 12:22:23.078  7262  7262 I GAv4    :   adb logcat -s GAv4
07-05 12:22:23.108  7262  7262 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-05 12:22:23.138  7262  7262 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-05 12:22:23.148  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.148  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.158  7262  7299 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 12:22:23.158  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.178  7262  7262 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at fdw.g(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at fdw.a(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at fdw.e(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at fdy.b(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at feb.run(Unknown Source)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:22:23.178  7262  7299 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
07-05 12:22:23.178  7262  7299 E GAv4    : Opening the database failed, dropping the table and recreating it
07-05 12:22:23.188  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at fdw.g(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at fdw.a(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at fdw.e(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at fdy.b(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at feb.run(Unknown Source)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:22:23.188  7262  7299 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
07-05 12:22:23.188  7262  7299 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.188  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.188  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.188  7262  7299 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.188  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.188  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at ael.a(PG:1521)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-05 12:22:23.208  7262  7300 E SQLiteDatabase: 	at aen.run(PG:536)
07-05 12:22:23.318  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.318  7262  7299 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.318  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.318  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.318  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.318  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.318  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328  7262  7299 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7299 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7299 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328   969  1706 D VoldConnector: SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328   386   645 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7300 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
07-05 12:22:23.328  7262  7298 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 12:22:23.328  7262  7304 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
07-05 12:22:23.328  7262  7300 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
07-05 12:22:23.338   969  1993 D PMS     : acquireWL(3dce418d): PARTIAL_WAKE_LOCK  AsyncService 0x1 7080 10167 null
07-05 12:22:23.338   969   989 D PMS     : acquireWL(161dcb53): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7080 10167 null
07-05 12:22:23.338   969  1276 D PMS     : releaseWL(3dce418d): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at ael.a(PG:1521)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at aej.c(PG:139)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at aej.b(PG:398)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at agf.f(PG:417)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at oe.run(PG:1112)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 12:22:23.348  7262  7304 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:22:23.348  7262  7305 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at aej.c(PG:139)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at aej.b(PG:398)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at agf.f(PG:417)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 12:22:23.348  7262  7304 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:22:23.348  7262  7305 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:22:23.378  6999  7308 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 12:22:23.388   969  1706 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7262 on display 0
07-05 12:22:23.398   969   969 V ActivityManager: Display changed displayId=0
07-05 12:22:23.398  1443  1443 D DotMatrix: [EventService]  onDisplayChanged: 0
07-05 12:22:23.398   969   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=7080, uid=10167, userID:0
07-05 12:22:23.398  1443  1443 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false

```
