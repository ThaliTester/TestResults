#### Test 63186632d456b18_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
03-17 09:50:13.338  4271  4271 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
03-17 09:50:13.338  4271  4372 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
--------- beginning of system
03-17 09:50:13.338   911  2287 I ActivityManager: Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=4381 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 09:50:13.348  4340  4377 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 09:50:13.358  4271  4335 W MediaScanner: Error opening directory '/oem/media/', skipping: No such file or directory.
03-17 09:50:13.358  1547  2379 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
03-17 09:50:13.358  1547  2379 D AccFlag : sku_id=118
03-17 09:50:13.358  4271  4335 W MediaScanner: Error opening directory '/oem/media/', skipping: No such file or directory.
03-17 09:50:13.368  4271  4335 D MediaScanner:  prescan time: 211ms
03-17 09:50:13.368  4271  4335 D MediaScanner:     scan time: 30ms
03-17 09:50:13.368  4271  4335 D MediaScanner: postscan time: 0ms
03-17 09:50:13.368  4271  4335 D MediaScanner:    total time: 241ms
03-17 09:50:13.368  4271  4335 D MediaScanner: -----------------------------------------------------------------
03-17 09:50:13.368  4271  4335 D MediaScanner: firstscan(media) time: 17ms
03-17 09:50:13.368  4271  4335 D MediaScanner: secondscan(non-media) time: 8ms
03-17 09:50:13.368  4271  4335 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:13.368  4271  4335 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:13.368  4271  4335 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:13.368  4271  4335 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 339
03-17 09:50:13.378  4340  4377 D SmsReceiverService: OutBoxSize = 0
03-17 09:50:13.378  4340  4377 D SmsReceiverService: sendFirstQueuedMessage start: 0
03-17 09:50:13.378  4340  4377 D MessageCustFlag: sku_id=118
03-17 09:50:13.378  4301  4301 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cb7083b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 09:50:13.378  4301  4301 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 09:50:13.378  1547  1583 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
03-17 09:50:13.378  1547  1583 D AccFlag : sku_id=118
03-17 09:50:13.378  4301  4301 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 09:50:13.388  4340  4377 D MessageCustFlag: sku_id=118
03-17 09:50:13.388  4340  4377 D SmsReceiverService: sendFirstQueuedMessage end cnt> 0
,03-17 09:50:13.398  4340  4403 D SpaceBufferUtil: > createBufferFile()
03-17 09:50:13.398  4340  4403 D SpaceBufferUtil: bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
03-17 09:50:13.398  4340  4403 D SpaceBufferUtil: < createBufferFile()
03-17 09:50:13.478  4271  4335 D MediaProvider: [delete][112]
03-17 09:50:13.478  4271  4335 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
03-17 09:50:13.498  4271  4335 D MediaProvider: [recoverParentNodes] - 0
03-17 09:50:13.498  4271  4335 D MediaProvider: [update][17]
03-17 09:50:13.498  4271  4335 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
03-17 09:50:13.498   911  4024 D PMS     : releaseWL(36a37c26): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
03-17 09:50:13.508  4271  4335 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
03-17 09:50:13.508  4271  4335 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
03-17 09:50:13.508  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] ext storage
03-17 09:50:13.508  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:13.508  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:13.508  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 09:50:13.508  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
03-17 09:50:13.508  4271  4335 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
03-17 09:50:13.518  4411  4411 E cutils-trace: Error opening trace file: Permission denied (13)
03-17 09:50:13.518  4271  4335 D MediaProvider: [update][7]#0#
03-17 09:50:13.518  4411  4411 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-17 09:50:13.518  4411  4411 I dex2oat : dex2oat: override thread count:4
03-17 09:50:13.518  4271  4335 D MediaProvider: [update][3]#0#
03-17 09:50:13.538  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
03-17 09:50:13.538  4271  4335 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
03-17 09:50:13.538  4271  4335 D MediaProvider: [update][13]#1#
03-17 09:50:13.538  4271  4335 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
03-17 09:50:13.538   911   949 D PMS     : acquireWL(1c1cceae): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4271 10017 null
03-17 09:50:13.548  4271  4335 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
03-17 09:50:13.718  4412  4420 E cutils-trace: Error opening trace file: Permission denied (13)
03-17 09:50:13.808  4412  4412 D CustomizationManager: ====startRecUseTime====
03-17 09:50:13.808  4412  4412 D htc.customization.log.level:  is 
03-17 09:50:13.808  4412  4412 W CustomizationLogLevel: Level value is invalid, use default level 2
03-17 09:50:13.828  1595  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-17 09:50:13.828  1595  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3954d238 +
03-17 09:50:13.828  1595  2108 I Prism.WidgetManager: onLoadItems() +
03-17 09:50:13.878   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 09:50:13.878  1217  1217 D WIFI_ICON: WifiActivity: 1
03-17 09:50:13.878   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=75
03-17 09:50:13.878  1217  1217 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 09:50:13.878   911   911 E WifiTrafficPoller: notifying of data activity 1
03-17 09:50:13.888  4412  4412 D CustomizationManager:  Read ACC file spent 0.042 (s)
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__001
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__102
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__032
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__002
03-17 09:50:13.888  4412  4412 D CIDMapFileReader: Parsing tag item name = HTC__031
03-17 09:50:13.898  4412  4412 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = system
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = application
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = Settings
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: Parsing tag category name = ACC
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 42507
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 21902
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23420
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 22299
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 24002
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23210
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23205
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23806
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23430
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23408
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 27205
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-17 09:50:13.898  4412  4412 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-17 09:50:13.898  4412  4412 D CustomizationManager:  Read CID file spent 0.096 (s)
03-17 09:50:13.898  4412  4412 D CustomizationManager:  All configurations done spent 0.096 (s)
03-17 09:50:13.908  1595  2108 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 09:50:13.958   911   949 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 4412 on display 0
03-17 09:50:13.958   911  1056 D PMS     : acquireHCC(7d1344f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 911 1000 null
03-17 09:50:13.958   911  1056 D PMS     : acquireHCC(161d87dc): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 911 1000 null
03-17 09:50:13.968   911   949 W asset   : Copying FileAsset 0x5595bc80c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-17 09:50:13.968   911   949 D PMS     : acquireWL(1016c66b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
03-17 09:50:13.978  1595  1595 I FeedHostManager: [onPause]
03-17 09:50:13.978  1595  1595 I FeedProviderManager: onPause
03-17 09:50:13.978  1595  1595 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@1f64eca6
03-17 09:50:13.978   911  1044 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/5
03-17 09:50:13.978  1595  2492 I SocialFeedProvider: +onPause
03-17 09:50:13.978  1595  2492 I SocialFeedProvider: -onPause
03-17 09:50:13.988   911  1639 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-17 09:50:13.998   911  4024 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4435 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 09:50:14.098   911  1042 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-17 09:50:14.098   911  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:50:14.098   911  1042 D StatusBarManagerService: hiding MENU key
03-17 09:50:14.108  4435  4435 W asset   : Copying FileAsset 0xac6fef80 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-17 09:50:14.108   911  1154 E WifiStateMachine: handleMessage: E msg.what=131155
03-17 09:50:14.108   911  1154 E WifiStateMachine: processMsg: ConnectedState
03-17 09:50:14.118   911  1154 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=3.5, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:2903] from screen [on:0 period:-2084266516] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 09:50:14.118   911  1154 E WifiStateMachine: processMsg: L2ConnectedState
03-17 09:50:14.118   911  1154 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=3.5, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2084266514] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 09:50:14.118   911  1154 E WifiStateMachine:  get link layer stats 0
03-17 09:50:14.118   911  1154 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 09:50:14.118  1342  1342 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-17 09:50:14.128  1342  1342 I wpa_supplicant: environment dirty rate=0 [2][0][0]
03-17 09:50:14.128   911  1154 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 09:50:14.128   911  1154 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-51 linkspeed=150
03-17 09:50:14.128   911  1154 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-51 "NG700"WPA_PSK
03-17 09:50:14.128   911  1154 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.76 txretriesrate=0.00 rxrate=8.82 userTriggerdPenalty0
03-17 09:50:14.128   911  1154 E WifiStateMachine:  good link -> stuck count =0
03-17 09:50:14.128   911  1154 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 09:50:14.128   911  1154 E WifiStateMachine:  isHighRSSI       ---> score=61
03-17 09:50:14.138   911  1173 D WifiWatchdogStateMachine: RSSI current: 3 new: -51, 3
03-17 09:50:14.138   911  1154 E WifiStateMachine: handleMessage: X
03-17 09:50:14.148  1595  1595 I TrimMemoryManager: [trimMemory] 20
03-17 09:50:14.158  1217  1217 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-17 09:50:14.158  1217  1217 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-17 09:50:14.278  4435  4435 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
03-17 09:50:14.338  4435  4435 I LibraryLoader: Time to load native libraries: 16 ms (timestamps 3901-3917)
03-17 09:50:14.348  4435  4435 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:50:14.348  1595  2108 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 09:50:14.358  4435  4435 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c25314e}
03-17 09:50:14.358  4435  4435 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:50:14.368  4435  4435 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 09:50:14.388  4435  4435 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 09:50:14.388  4435  4435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:50:14.398  4435  4435 E SysUtils: ApplicationContext is null in ApplicationStatus
03-17 09:50:14.428  1547  2206 D PhoneApp: EVENT_QUERY_MO_PACKAGES
03-17 09:50:14.428  1547  2206 D PhoneApp: -- N1 =0
03-17 09:50:14.438  1547  2206 D PhoneApp: -- N2 =0
03-17 09:50:14.438  1547  2206 D PhoneApp: -- N3 =0
03-17 09:50:14.468  4435  4435 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-17 09:50:14.468  3545  3601 I HtcModeClient: handler message = 4011
03-17 09:50:14.468  3545  3601 E HtcModeClient: Check connection and retry 2 times.
03-17 09:50:14.478  4435  4435 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 09:50:14.478  4435  4435 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 09:50:14.478  4435  4435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-17 09:50:14.478  4435  4435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-17 09:50:14.478  4435  4435 I Adreno-EGL: Build Date: 03/09/15 Mon
03-17 09:50:14.478  4435  4435 I Adreno-EGL: Local Branch: 
03-17 09:50:14.478  4435  4435 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-17 09:50:14.478  4435  4435 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-17 09:50:14.478  4435  4435 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
03-17 09:50:14.518  1595  2108 W asset   : Copying FileAsset 0x559597d550 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
03-17 09:50:14.568   911  1043 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-17 09:50:14.568   911  1043 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23506737:true
03-17 09:50:14.568   911  2267 W System.err: java.lang.Throwable: stack dump
03-17 09:50:14.568   911  2267 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-17 09:50:14.568   911  2267 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-17 09:50:14.568   911  2267 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-17 09:50:14.568   911  2267 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-17 09:50:14.578  4435  4470 D BluetoothAdapter: 343099019: getState(). Returning 12
03-17 09:50:14.638  1595  2108 I Prism.WidgetManager: onLoadItems() -
03-17 09:50:14.638  1595  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3954d238 -
03-17 09:50:14.648  4411  4411 I dex2oat : dex2oat took 1.133s (threads: 4)
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): VersionName:             1.2.853019
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): VersionCode:             148001224
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
03-17 09:50:14.688  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
03-17 09:50:14.698  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): Htc_DEBUG_flag:          false
03-17 09:50:14.698  4381  4381 I PushClient: ApplicationMonitor {1427145a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
03-17 09:50:14.788   911  1822 I art     : Explicit concurrent mark sweep GC freed 25131(1447KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.626ms total 210.776ms
03-17 09:50:14.818   911  1592 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4476 uid=10076 gids={50076, 9997} abi=arm64-v8a
03-17 09:50:14.828  4381  4474 I PushClient: String {2b182068}: handleBroadcast(): Schedule update on boot completed.
03-17 09:50:14.858  4476  4476 D SMSBackup: Got ACTION_BOOT_COMPLETED event
03-17 09:50:14.858  4476  4476 D SMSBackup: setCheckAlarm
03-17 09:50:14.868  4476  4476 D SMSBackup: Next check is scheduled at 60s from now
03-17 09:50:14.868   911  1605 D Process : killProcessQuiet, pid=3662
03-17 09:50:14.868   911  1605 I ActivityManager: Killing 3662:com.htc.bgp/u0a11 (adj 15): empty #17
03-17 09:50:14.868   911  1605 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-17 09:50:14.868  4271  4335 D MediaProvider: [update][19]#1#
03-17 09:50:14.878   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 09:50:14.878   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=77
03-17 09:50:14.878  4435  4435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:50:14.888  4435  4435 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-17 09:50:14.908  4435  4435 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
03-17 09:50:14.948   911  4024 I ActivityManager: Recipient 3662
,03-17 09:50:14.968   911  1605 D Process : killProcessQuiet, pid=3838,
03-17 09:50:14.968   911  1605 I ActivityManager: Killing 3838:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
03-17 09:50:14.968   911  1605 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,03-17 09:50:15.068   911  2267 I ActivityManager: Recipient 3838,
,03-17 09:50:15.088  4435  4435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:50:15.088  4435  4435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:50:15.098   911   949 I PackageManager:  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1547, uid=1001, userID:0
,03-17 09:50:15.118   911   946 I ActivityManager: Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=4504 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 09:50:15.148  4435  4468 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,03-17 09:50:15.178  4504  4504 I [AppShowMeDebug]BootCompletedReceiver: received boot complete,
,03-17 09:50:15.198  4435  4435 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-17 09:50:15.198  4504  4527 I [AppShowMeDebug]BootCompletedReceiver: push flag is false, skip check,
,03-17 09:50:15.208   911  1822 I ActivityManager: Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=4529 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,03-17 09:50:15.208   911  1822 D Process : killProcessQuiet, pid=3889
03-17 09:50:15.208   911  1822 I ActivityManager: Killing 3889:com.htc.video/u0a29 (adj 15): empty #17
,03-17 09:50:15.208   911  1822 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 09:50:15.278  4340  4340 D Messaging: supportCMAS(SIE)/init? false/true
03-17 09:50:15.278  4340  4340 D MmsConfig: networkCode: 
03-17 09:50:15.278  4340  4340 D MmsConfig: SIE smsPri: null
03-17 09:50:15.278  4340  4340 D MmsConfig: networkCode: 
,03-17 09:50:15.278  4340  4552 D Messaging: mNeedToUpdateDate2 start
,03-17 09:50:15.278  4340  4340 D MmsConfig: packageName: com.htc.vvm.att does not exist,
,03-17 09:50:15.278  4340  4340 D ReportIndicatorCache: startAsyncQueryReports ---
03-17 09:50:15.278  4340  4367 D MmsAsyncWorkHandler: 
03-17 09:50:15.278  4340  4367 D MmsAsyncWorkHandler: HM tk = 20001
03-17 09:50:15.278  4340  4367 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,03-17 09:50:15.288  4340  4340 D DraftCache: [DraftCache/1] DraftCache.constructor,
03-17 09:50:15.288  4340  4340 D DraftCache: [DraftCache/1] refresh
03-17 09:50:15.288  4340  4554 I Messaging: mccmnc> 
,03-17 09:50:15.298  4340  4340 D MmsConfig: networkCode: 
,03-17 09:50:15.298  4435  4435 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@354fdad6, mServedView=org.apache.cordova.engine.SystemWebView{1f319157 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@22ad9444
,03-17 09:50:15.298   911  1165 I InputMethodManagerService: Disable input method client, pid=1595,
03-17 09:50:15.298   911  1165 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-17 09:50:15.308   911  1165 I InputMethodManagerService: Enable input method client, pid=4435
03-17 09:50:15.308  1217  1217 I PhoneStatusBar: setImeWindowStatus(false,false)
03-17 09:50:15.308  4340  4558 D Messaging: ViewCache CreatePreloadOnlyConversationList
03-17 09:50:15.308   911  1379 I ActivityManager: Recipient 3889
03-17 09:50:15.318   911  1044 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s343ms
03-17 09:50:15.318   911   949 D PMS     : releaseWL(1016c66b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
03-17 09:50:15.328  1547  1586 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-17 09:50:15.328  1547  1586 D AccFlag : sku_id=118
03-17 09:50:15.328  4340  4558 D MessageCustFlag: sense_version=6.0
03-17 09:50:15.328  4340  4340 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
03-17 09:50:15.328  4340  4340 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
03-17 09:50:15.328  4340  4340 D PhoneStorageUtil: createReceiver
03-17 09:50:15.328  4340  4367 D DraftCache: [DraftCache/106] rebuildCache
,03-17 09:50:15.338  1547  2429 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
03-17 09:50:15.338  1547  2429 D MmsSmsV2Provider:  slotId = -1000
03-17 09:50:15.338  1547  2429 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,03-17 09:50:15.338  1547  2379 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,03-17 09:50:15.338  1547  2379 D MmsSmsV2Provider:  slotId = -1000
03-17 09:50:15.338  1547  2379 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,03-17 09:50:15.338  4340  4558 D Jerry   : start to preload cursor >>>>>>>,
,03-17 09:50:15.348  1547  1583 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,03-17 09:50:15.348  1547  1583 V MmsProvider: Update uri=content://mms, match=0
03-17 09:50:15.348  1547  1583 V MmsProvider: selection=st=129 AND m_type!=134
03-17 09:50:15.348  4340  4560 D Messaging: Reset downloading state: 0
03-17 09:50:15.348  4340  4560 V MmsSystemEventReceiver: TransactionService is going to be woken up.
03-17 09:50:15.348  1547  1586 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-17 09:50:15.348  1547  1586 D Jerry   : URI_DRAFT
03-17 09:50:15.358  4340  4340 V TransactionService: 1-Creating TransactionService
03-17 09:50:15.358  4340  4367 D DraftCache: hasDraft() = false mNeedNotifyChange = true
03-17 09:50:15.358  4340  4367 D DraftCache: [DraftCache/106] rebuildCache time: 3
03-17 09:50:15.358  4340  4367 D MmsAsyncWorkHandler: 
03-17 09:50:15.358  4340  4367 D MmsAsyncWorkHandler: HM tk = 20002
,03-17 09:50:15.368  4340  4340 V TransactionService: onStartCommand: 1
03-17 09:50:15.368  4340  4340 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,03-17 09:50:15.368  4340  4562 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
03-17 09:50:15.368  4340  4562 V TransactionService: Loading previous transactions.
,03-17 09:50:15.368  4435  4435 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4435
03-17 09:50:15.368  1547  2429 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
03-17 09:50:15.368  1547  2429 D MmsSmsV2Provider:  slotId = -1000
03-17 09:50:15.368  1547  2429 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,03-17 09:50:15.368  1400  1400 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
03-17 09:50:15.368  1400  1400 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
03-17 09:50:15.368  1400  1400 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
03-17 09:50:15.368  1400  1400 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,03-17 09:50:15.378  4271  4335 D MediaProvider: [update][21]#1#,
,03-17 09:50:15.378  4340  4552 D Messaging: mNeedToUpdateDate2: false
03-17 09:50:15.378  1547  1586 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-17 09:50:15.378  1547  1586 D AccFlag : device_type: 1
,03-17 09:50:15.378  1547  2379 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,03-17 09:50:15.388  1547  2379 D MmsSmsV2Provider:  slotId = -1000
,03-17 09:50:15.388  4340  4562 D TransactionService: Force clearing mTransactionList
,03-17 09:50:15.388  4340  4562 D TransactionService: Force set service start id to 1
03-17 09:50:15.388  4340  4562 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
03-17 09:50:15.388  4340  4562 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,03-17 09:50:15.388  4340  4562 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,03-17 09:50:15.388  4340  4340 V TransactionService: Destroying TransactionService
03-17 09:50:15.398  4340  4562 V TransactionService: 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
03-17 09:50:15.398  1547  1586 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-17 09:50:15.398  1547  1586 D MmsSmsV2Provider:  slotId = -1000
03-17 09:50:15.398  1547  1586 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,03-17 09:50:15.398  4340  4558 D Messaging: ViewCache CreatePreload
,03-17 09:50:15.398  4340  4558 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,03-17 09:50:15.398  4340  4553 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,03-17 09:50:15.398  4529  4529 D MyReportAgent: PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,03-17 09:50:15.408  1547  2429 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,03-17 09:50:15.408  1547  2429 D AccFlag : sku_id=118
03-17 09:50:15.408  4340  4558 D Cust_MMSMS: _has_set_default_values_2=true
,03-17 09:50:15.418  4529  4568 D MyReportAgent: DatabaseHelper [DatabaseHelper constructor]
,03-17 09:50:15.418  4529  4568 D MyReportAgent: PolicyStore [Init] Get cached policy bundle
,03-17 09:50:15.428   911  1822 I ActivityManager: Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4570 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,03-17 09:50:15.428  4529  4568 D MyReportAgent: ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
03-17 09:50:15.428  4340  4558 D MsgPreferenceUtils: def_index: 0
,03-17 09:50:15.438  1547  1586 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-17 09:50:15.438  1547  1586 D AccFlag : sku_id=118
,03-17 09:50:15.438  4340  4558 D MsgPreferenceUtils: globalIndex = 1
,03-17 09:50:15.438  4340  4558 D MsgPreferenceUtils: phone state: true
,03-17 09:50:15.438  4340  4558 D MsgPreferenceUtils: sd state: false
03-17 09:50:15.438  4340  4558 D MsgPreferenceUtils: vIndex = 0
,03-17 09:50:15.448  4529  4568 D MyReportAgent: ReportServiceHandler on boot complete event 
,03-17 09:50:15.458   911   946 I PackageManager:  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=4529, uid=10083, userID:0,
03-17 09:50:15.458  4529  4568 V MyReportAgent: ReportServiceHandler unregister the PowerConnected Listener
,03-17 09:50:15.468   911  1165 I ActivityManager: Killing 3914:com.htc.csrecommend/u0a31 (adj 15): empty #17
03-17 09:50:15.468   911  1165 D Process : killProcessQuiet, pid=3914
,03-17 09:50:15.468   911  1165 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:15.498  4435  4435 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 09:50:15.568   911  2267 I ActivityManager: Recipient 3914
,03-17 09:50:15.588  4570  4570 D UpdaterAPK | UpdaterBootCompleteReceiver: onReceive() - start htcCheckinService
,03-17 09:50:15.608   911   911 I htcCheckinService: htcCheckinProvider V2.1
,03-17 09:50:15.608   911   911 D htcCheckinService: htcCheckinService() the mIsServiceRunning = true
,03-17 09:50:15.618   911   911 I htcCheckinService: Checkin service onCreate()!
,03-17 09:50:15.618   911  1822 I ActivityManager: Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4606 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
,03-17 09:50:15.628   911   911 D htcCheckinService: onStartCommand()
,03-17 09:50:15.628   911   911 D htcCheckinService: onStartCommand() the action name = null
03-17 09:50:15.628   911  4625 D htcCheckinService: InitThread start
03-17 09:50:15.628   911   911 D htcCheckinService: ConnectivityReceiver - onReceive() - original mNetworkConnected = false
03-17 09:50:15.628   911   911 D htcCheckinService: ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,03-17 09:50:15.638   451   451 I art     : Explicit concurrent mark sweep GC freed 8641(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 199us total 21.684ms
03-17 09:50:15.648   911  1585 I ActivityManager: Killing 3935:com.htc.home.personalize/1000 (adj 15): empty #17
03-17 09:50:15.648   911  1585 D Process : killProcessQuiet, pid=3935
03-17 09:50:15.648   911  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:15.668   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 224us total 28.108ms
,03-17 09:50:15.688   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 17.647ms
,03-17 09:50:15.748   911   949 I ActivityManager: Recipient 3935,
,03-17 09:50:15.798  4435  4559 D jxcore_app_log: JniHelper::setJavaVM(0xab5938f8), pthread_self() = -1400126776
,03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 09:50:15.808  4435  4559 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e72a586 added. We now have 1 listener(s)
03-17 09:50:15.818   911   949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 09:50:15.818  4435  4559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,03-17 09:50:15.818  4435  4559 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-17 09:50:15.828  4435  4559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-17 09:50:15.828  4435  4559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-17 09:50:15.828  4435  4559 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: MANUFACTURER_DATA
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 09:50:15.828  4435  4559 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220f979d added. We now have 1 listener(s)
03-17 09:50:15.828  4435  4559 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 09:50:15.838   911  1155 D WifiService: New client listening to asynchronous messages
,03-17 09:50:15.838   911   911 E WifiTrafficPoller: ADD_CLIENT: 6
,03-17 09:50:15.848  4435  4559 D BluetoothAdapter: 343099019: getState(). Returning 12
,03-17 09:50:15.848  4435  4559 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-17 09:50:15.848  4435  4559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 09:50:15.848  4435  4559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 09:50:15.848  4435  4559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 09:50:15.858  4435  4559 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 09:50:15.858  4435  4559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 09:50:15.858   911  4024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 09:50:15.858   911  1379 D PMS     : acquireWL(1cd7ecad): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4606 10090 null
,03-17 09:50:15.868  4435  4559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-17 09:50:15.878  4435  4559 D BluetoothAdapter: 343099019: getState(). Returning 12
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 09:50:15.878  4435  4559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 09:50:15.878  4435  4559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 09:50:15.878  4435  4559 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 09:50:15.878   911   911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-17 09:50:15.878   911   911 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 ,
,03-17 09:50:15.888  4606  4606 I WorldClock.Global: isHEPDevice = true
,03-17 09:50:15.888  4435  4435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:50:15.888  4435  4435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:50:15.898   911   911 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4633 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,03-17 09:50:15.898   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-17 09:50:15.898   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=79
,03-17 09:50:15.908  4435  4435 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 09:50:15.908  4606  4606 W SystemReader: Cannot find support_china_sense_feature, use default value instead
,03-17 09:50:15.928  4606  4606 I WorldClock.AlarmUtils: saveSupportOffAlarmInPreference: isSupport = false
03-17 09:50:15.928  4606  4648 W WorldClock.AlarmService: updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
,03-17 09:50:15.948  4606  4606 I WorldClock.AlarmService: isDeviceEncryptionEnabled = false,
03-17 09:50:15.948  4606  4648 I WorldClock.AlarmUtils: Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,03-17 09:50:15.948   911  1165 D PMS     : releaseWL(1cd7ecad): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
03-17 09:50:15.948   911   949 I ActivityManager: Killing 3861:com.google.android.partnersetup/u0a27 (adj 15): empty #17
03-17 09:50:15.948  4606  4648 I WorldClock.AlarmUtils: Cancel any alarm from alarm manager
03-17 09:50:15.948   911   949 D Process : killProcessQuiet, pid=3861
03-17 09:50:15.948   911   949 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 09:50:15.958  4606  4648 I WorldClock.AlarmUtils: broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,03-17 09:50:16.038   911   946 I ActivityManager: Recipient 3861
,03-17 09:50:16.048  4271  4335 D MediaScanner:  prescan time: 1267ms
,03-17 09:50:16.048  4271  4335 D MediaScanner:     scan time: 1237ms
03-17 09:50:16.048  4271  4335 D MediaScanner: postscan time: 2ms
03-17 09:50:16.048  4271  4335 D MediaScanner:    total time: 2506ms
03-17 09:50:16.048  4271  4335 D MediaScanner: -----------------------------------------------------------------
03-17 09:50:16.048  4271  4335 D MediaScanner: firstscan(media) time: 483ms
03-17 09:50:16.048  4271  4335 D MediaScanner: secondscan(non-media) time: 754ms
03-17 09:50:16.048  4271  4335 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:16.048  4271  4335 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:16.048  4271  4335 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:16.048  4271  4335 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
,03-17 09:50:16.058   911  1056 D PMS     : releaseHCC(7d1344f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-17 09:50:16.068  1217  1520 I IntentController: receive(android.intent.action.ALARM_CHANGED,1,false)
,03-17 09:50:16.068  4606  4648 I WorldClock.AlarmUtils: isDeviceEncryptionEnabled = false
,03-17 09:50:16.078  4606  4648 I WorldClock.AlarmUtils: Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,03-17 09:50:16.078  4606  4648 I WorldClock.AlarmService: resetStopwatchToDefault
03-17 09:50:16.078   911  1056 D PMS     : releaseHCC(161d87dc): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-17 09:50:16.088  4633  4633 E UpdateRequestReceiver: ignoring update request
,03-17 09:50:16.088  4606  4659 I WorldClock.DmdCmd: This version is general off mode alarm function,
,03-17 09:50:16.088  4606  4659 W WorldClock.DmdCmd: Conn: fail e = java.io.IOException: No such file or directory
03-17 09:50:16.088  4633  4633 E UpdateRequestReceiver: ignoring update request
,03-17 09:50:16.098  4271  4335 D MediaProvider: [delete][42],
03-17 09:50:16.098  4271  4335 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,03-17 09:50:16.098  4633  4633 E UpdateRequestReceiver: ignoring update request
,03-17 09:50:16.098  4271  4335 D MediaProvider: [recoverParentNodes] - 0
,03-17 09:50:16.108  4271  4335 D MediaProvider: [update][7]
03-17 09:50:16.108  4271  4335 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
,03-17 09:50:16.108  4271  4335 D MediaScannerServiceEx: [updateImage]+
,03-17 09:50:16.108  4633  4633 E UpdateRequestReceiver: ignoring update request
,03-17 09:50:16.108  4606  4648 I WorldClock.AlarmService: resetTimerToDefault
,03-17 09:50:16.108  4633  4633 E UpdateRequestReceiver: ignoring update request
,03-17 09:50:16.118  4633  4633 E UpdateRequestReceiver: ignoring update request
03-17 09:50:16.118  4271  4335 D MediaScannerServiceEx: [updateImage]-0
,03-17 09:50:16.118   911   949 D PMS     : releaseWL(1c1cceae): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
03-17 09:50:16.118  4271  4335 D MediaScannerServiceEx: [2] scan finished
03-17 09:50:16.118  4226  4226 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,03-17 09:50:16.118  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:16.118  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:16.118  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 09:50:16.118  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-17 09:50:16.118  4271  4335 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
03-17 09:50:16.128  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,03-17 09:50:16.128  4226  4226 I DeviceManagement: WorkflowService: Starting workflow service
,03-17 09:50:16.128  4226  4674 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@301d4ef6] args=[Bundle[EMPTY_PARCEL]]
,03-17 09:50:16.128  4226  4674 I DeviceManagement: BootCompletedWorkflow: ==================================================
03-17 09:50:16.128  4226  4674 I DeviceManagement: BootCompletedWorkflow: Boot completed
,03-17 09:50:16.128  4226  4674 I DeviceManagement: BootCompletedWorkflow: ==================================================
,03-17 09:50:16.138  4226  4674 I DeviceManagement: BackgroundController: *** Update after boot...
,03-17 09:50:16.138  4226  4674 I DeviceManagement: SessionStateController: Checking invariants...
,03-17 09:50:16.138  1595  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-17 09:50:16.138  1595  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3954d238 +
03-17 09:50:16.138  1595  2108 I Prism.WidgetManager: onLoadItems() +
,03-17 09:50:16.148  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,03-17 09:50:16.148  4271  4335 D MediaProvider: [update][27]#1#
,03-17 09:50:16.158  1862  4676 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 09:50:16.168   911  1585 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 09:50:16.178  4271  4335 D MediaProvider: [update][21]#0#,
,03-17 09:50:16.178  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
03-17 09:50:16.178  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:16.178  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:16.178  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 09:50:16.178  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-17 09:50:16.178  4271  4335 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
03-17 09:50:16.178  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609,
,03-17 09:50:16.188  4147  4677 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,03-17 09:50:16.188  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted
,03-17 09:50:16.188  4271  4335 D MediaProvider: [update][3]#1#
,03-17 09:50:16.188  4226  4674 I DeviceManagement: BackgroundController: Invariants are unchanged.
,03-17 09:50:16.198  4226  4674 I DeviceManagement: Perf: *** Cache update - start...
,03-17 09:50:16.198  4226  4674 I DeviceManagement: Perf: *** Enabled app cache update - start...
03-17 09:50:16.198  4226  4674 I DeviceManagement: EnabledAppController: *** Updating enabled app database...
,03-17 09:50:16.198  4226  4674 I DeviceManagement: EnabledAppController: Enabled app scan is pending...
03-17 09:50:16.198  4226  4674 I DeviceManagement: Perf: Scan enabled apps - start...
,03-17 09:50:16.308  4271  4335 D MediaProvider: [update][122]#0#,
,03-17 09:50:16.318  1314  1856 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,03-17 09:50:16.318  1314  1856 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
03-17 09:50:16.318  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
03-17 09:50:16.318  4271  4335 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
03-17 09:50:16.318  4271  4335 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,03-17 09:50:16.318  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] ext storage
,03-17 09:50:16.318  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:16.318  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:16.318  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 09:50:16.318  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
03-17 09:50:16.318  4271  4335 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
,03-17 09:50:16.328  4271  4335 D MediaProvider: [update][6]#0#
03-17 09:50:16.328  4147  4700 I htcbackup-core: CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
03-17 09:50:16.328  4271  4335 D MediaProvider: [update][2]#0#
,03-17 09:50:16.328  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 09:50:16.328   911  1143 V AlarmManager: sending alarm PendingIntent{29668c19: PendingIntentRecord{13af74de com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=18, w=1447326412457, Int=604800000
,03-17 09:50:16.328  4226  4674 I DeviceManagement: EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
,03-17 09:50:16.338  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
03-17 09:50:16.338  4271  4335 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
,03-17 09:50:16.338  4271  4335 D MediaProvider: [update][12]#1#
03-17 09:50:16.348  4271  4335 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
,03-17 09:50:16.348   911   946 D PMS     : acquireWL(239c918c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4271 10017 null
,03-17 09:50:16.348  1217  1217 I RemoteViews: apply : com.htc.backup 1 17 5 38
,03-17 09:50:16.348  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-17 09:50:16.368  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,03-17 09:50:16.368  1314  1353 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true,
03-17 09:50:16.368  1314  1353 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
03-17 09:50:16.368  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-17 09:50:16.368  4271  4335 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,03-17 09:50:16.378   911  4024 I ActivityManager: Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4708 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,03-17 09:50:16.388   911  4024 D Process : killProcessQuiet, pid=3485
03-17 09:50:16.388   911  4024 I ActivityManager: Killing 3485:com.htc.contacts/u0a38 (adj 15): empty #17
03-17 09:50:16.388  1217  1217 I RemoteViews: apply : com.htc.backup 1 13 4 5
03-17 09:50:16.388  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 09:50:16.388   911  4024 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 09:50:16.398  1217  1217 I RemoteViews: apply : com.htc.backup 1 2 6 5
03-17 09:50:16.398  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-17 09:50:16.408  1217  1217 I RemoteViews: apply : com.htc.backup 1 4 3 5
03-17 09:50:16.408  1217  1217 I RemoteViews: apply : com.htc.backup 1 14 38 50
,03-17 09:50:16.408  4340  4377 V SmsReceiverService: updateNotificationAndShortcutStatus: 
03-17 09:50:16.408  4340  4377 D MessagingNotification: New incoming message, can't cancel notification now
,03-17 09:50:16.408  4340  4377 D MessagingNotification: newMsgCnt: 0, false
,03-17 09:50:16.418  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 09:50:16.428  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
,03-17 09:50:16.468  1217  1217 I RemoteViews: reapply : com.htc.backup 3 38
,03-17 09:50:16.478  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
03-17 09:50:16.478  1217  1217 I RemoteViews: apply : com.htc.backup 0 3 0 5
,03-17 09:50:16.478  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145),
,03-17 09:50:16.488  1217  1217 I RemoteViews: apply : com.htc.backup 1 3 0 5
,03-17 09:50:16.488  1217  1217 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-17 09:50:16.488  1217  1217 I RemoteViews: apply : com.htc.backup 1 3 0 5
03-17 09:50:16.488  1217  1217 I RemoteViews: reapply : com.htc.backup 17 50
,03-17 09:50:16.498  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167,
,03-17 09:50:16.508   911  1605 I ActivityManager: Recipient 3485,
,03-17 09:50:16.568  4435  4632 W jxcore-log: Initializing JXcore engine
,03-17 09:50:16.568  4435  4632 W jxcore-log: JXcore engine is ready
03-17 09:50:16.578  4226  4674 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 09:50:16.618   911  1587 D Process : killProcessQuiet, pid=3958,
03-17 09:50:16.618   911  1587 I ActivityManager: Killing 3958:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
03-17 09:50:16.618   911  1587 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:16.638  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351,
,03-17 09:50:16.678  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,03-17 09:50:16.678  4435  4632 W jxcore-log: Starting JXcore engine,
,03-17 09:50:16.688   911  1561 I ActivityManager: Recipient 3958,
,03-17 09:50:16.728   911  1165 D PMS     : releaseWL(1e5010b0): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,03-17 09:50:16.738  4226  4674 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 09:50:16.738  4226  4674 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 09:50:16.738  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 09:50:16.748  1547  1547 D ResetNotifyBootCompleteReceiver: userSerialNumber = 0
,03-17 09:50:16.748  1547  1547 D ResetNotifyBootCompleteReceiver: Receive bootcomplete intent
03-17 09:50:16.748  1547  1547 D ResetNotifyBootCompleteReceiver: isOwnerUser = true
,03-17 09:50:16.758  4708  4729 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,03-17 09:50:16.778   911  2287 I ActivityManager: Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4732 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,03-17 09:50:16.778  4708  4729 D ActivityThread: Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
03-17 09:50:16.788  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
03-17 09:50:16.808  4435  4632 W jxcore-log: Platform android
03-17 09:50:16.808  4435  4632 W jxcore-log: 
03-17 09:50:16.808  4435  4632 W jxcore-log: Process ARCH arm
03-17 09:50:16.808  4435  4632 W jxcore-log: 
,03-17 09:50:16.848  1595  2108 E Prism.WidgetManager: The same lists. No need to update. skip it.,
03-17 09:50:16.848  1595  2108 I Prism.WidgetManager: onLoadItems() -,
03-17 09:50:16.848  1595  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3954d238 -
,03-17 09:50:16.878  4226  4674 W ResourceType: ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,03-17 09:50:16.888  4708  4729 I HtcCupdXmlParser: java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory),
,03-17 09:50:16.898   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-17 09:50:16.908   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=79
03-17 09:50:16.908   911   911 E WifiTrafficPoller: notifying of data activity 0
03-17 09:50:16.908  1217  1217 D WIFI_ICON: WifiActivity: 0
03-17 09:50:16.908  1217  1217 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 09:50:16.918  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
,03-17 09:50:16.978   911  2267 I art     : Explicit concurrent mark sweep GC freed 20173(1013KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.525ms total 152.559ms
,03-17 09:50:16.978   911   911 I AlarmManager: [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
,03-17 09:50:16.988   911   911 I AlarmManager: [AlarmQueuing] post alarm-list load task
03-17 09:50:16.988   911   911 I AlarmManager: [AlarmQueuing] init alarm queuing list
03-17 09:50:16.988  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 09:50:17.018   911   911 I ActivityManager: Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4755 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
03-17 09:50:17.018   911  1379 I ActivityManager: Killing 3979:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
03-17 09:50:17.018   911  1379 D Process : killProcessQuiet, pid=3979
03-17 09:50:17.018   911  1379 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:17.018  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:50:17.038  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,03-17 09:50:17.038  4435  4632 I jxcore-log: JXcore Cordova bridge is ready!
03-17 09:50:17.038  4435  4632 I jxcore-log: 
03-17 09:50:17.038  4435  4632 W jxcore-log: JXcore engine is started
03-17 09:50:17.048  4435  4559 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 09:50:17.048  4435  4435 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 09:50:17.058  4226  4674 W ResourcesManager: Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,03-17 09:50:17.058  4435  4632 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 09:50:17.058  4435  4632 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 09:50:17.068  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:50:17.068  4435  4435 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-17 09:50:17.068  4435  4435 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 09:50:17.138   911  1154 E WifiStateMachine: handleMessage: E msg.what=131155,
03-17 09:50:17.138  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:50:17.138   911  1154 E WifiStateMachine: processMsg: ConnectedState
03-17 09:50:17.138   911  1154 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=2.8, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2084263493] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 09:50:17.138   911  1154 E WifiStateMachine: processMsg: L2ConnectedState
03-17 09:50:17.138   911  1154 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2457 sc=60 link=150 tx=2.8, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2084263492] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-17 09:50:17.138   911  1154 E WifiStateMachine:  get link layer stats 0
03-17 09:50:17.138   911  1154 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-17 09:50:17.138  1342  1342 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-17 09:50:17.148  1342  1342 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-17 09:50:17.148   911  1154 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 150
03-17 09:50:17.148   911  1154 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-51 linkspeed=150
03-17 09:50:17.148   911  1154 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-51 "NG700"WPA_PSK
,03-17 09:50:17.148   911  1154 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.38 txretriesrate=0.00 rxrate=5.91 userTriggerdPenalty0
03-17 09:50:17.148   911  1154 E WifiStateMachine:  good link -> stuck count =0
03-17 09:50:17.148   911  1154 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-17 09:50:17.148   911  1154 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-17 09:50:17.168  4226  4674 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 09:50:17.178   911  1587 I ActivityManager: Recipient 3979
,03-17 09:50:17.178  4226  4674 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
03-17 09:50:17.198  4226  4674 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
,03-17 09:50:17.218  4226  4674 I DeviceManagement: EnabledAppBuilder: Found 8 DM enabled apps.
,03-17 09:50:17.228  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,03-17 09:50:17.228  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,03-17 09:50:17.238  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,03-17 09:50:17.238  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,03-17 09:50:17.248  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity,
03-17 09:50:17.258  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
03-17 09:50:17.258  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,03-17 09:50:17.268  4226  4674 I DeviceManagement: EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,03-17 09:50:17.268  4226  4674 I DeviceManagement: Perf: Scan enabled apps - complete: 1074 ms
03-17 09:50:17.268  4226  4674 I DeviceManagement: Perf: *** Enabled app cache update - complete: 1076 ms
,03-17 09:50:17.278  4226  4674 I DeviceManagement: Perf: *** Config cache update - start...
,03-17 09:50:17.278  4226  4674 I DeviceManagement: ConfigCacheController: *** Updating config cache...
03-17 09:50:17.278  4226  4674 I DeviceManagement: ConfigCacheController: *** Updating stale config cache entries...
,03-17 09:50:17.288   911  1165 D PMS     : acquireWL(20f5dfdb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
,03-17 09:50:17.288  4435  4559 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 212ms. Plugin should use CordovaInterface.getThreadPool().
03-17 09:50:17.288  4226  4674 I DeviceManagement: ConfigCacheController: *** Update config cache: updating 0 entries...
03-17 09:50:17.288  4226  4674 I DeviceManagement: ConfigCacheController: No changes need to be broadcasted.
,03-17 09:50:17.288   911  1822 I ActivityManager: Killing 4001:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
,03-17 09:50:17.288   911  1822 D Process : killProcessQuiet, pid=4001
03-17 09:50:17.288   911  1822 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:17.298  4226  4674 I DeviceManagement: AlarmController: Scheduling TTL alarm for: 2016.03.18 at 09:46:32.823 CET (due to: com.htc.launcher)
,03-17 09:50:17.398  4778  4781 E cutils-trace: Error opening trace file: Permission denied (13)
,03-17 09:50:17.428   911  1165 I ActivityManager: Recipient 4001,
,03-17 09:50:17.458  4778  4778 D CustomizationManager: ====startRecUseTime====
,03-17 09:50:17.458  4778  4778 D htc.customization.log.level:  is 
03-17 09:50:17.458  4778  4778 W CustomizationLogLevel: Level value is invalid, use default level 2
,03-17 09:50:17.498   911  1154 E WifiStateMachine: handleMessage: X
,03-17 09:50:17.498   911  1639 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,03-17 09:50:17.518  1217  1217 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3,
03-17 09:50:17.518  1217  1217 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-17 09:50:17.518   911   911 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@34d2e090
,03-17 09:50:17.528  4778  4778 D CustomizationManager:  Read ACC file spent 0.034 (s)
03-17 09:50:17.528   911   911 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@3d95ad89
,03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__001
03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__102
03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__032
03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__002
,03-17 09:50:17.528  4778  4778 D CIDMapFileReader: Parsing tag item name = HTC__031
03-17 09:50:17.528  4778  4778 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = system
,03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = application
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = Settings
03-17 09:50:17.528  4778  4778 I CustomizationCIDLoader: Parsing tag category name = ACC
,03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 42507
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 21902
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23420
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 22299
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 24002
03-17 09:50:17.538  1595  1595 I FeedHostManager: [onResume]
,03-17 09:50:17.538  1595  1595 I FeedProviderManager: onResume
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23210
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23205
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23806
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23430
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23408
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 27205
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
,03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-17 09:50:17.538  1595  2492 I SocialFeedProvider: +onResume
03-17 09:50:17.538  1595  2492 I SocialFeedProvider: updateAccounts - Accounts is no change
03-17 09:50:17.538  1595  2492 I SocialFeedProvider: -onResume
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-17 09:50:17.538  4778  4778 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-17 09:50:17.538  4778  4778 D CustomizationManager:  Read CID file spent 0.079 (s)
03-17 09:50:17.538  4778  4778 D CustomizationManager:  All configurations done spent 0.079 (s)
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@35d884c1
,03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.apps.maps
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.gsf
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.google.android.location
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.katana
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: jp.naver.line.android
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.viber.voip
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.tencent.mm
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.htc.android.mail
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.sina.weibo
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] add queuing package: com.facebook.orca
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
03-17 09:50:17.538   911   911 I AlarmManager: [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
03-17 09:50:17.538   911  1173 D WifiWatchdogStateMachine: RSSI current: 3 new: -51, 3
,03-17 09:50:17.538   911   911 D Process : killProcessQuiet, pid=4025,
03-17 09:50:17.538   911   911 I ActivityManager: Killing 4025:com.htc.musicenhancer/u0a49 (adj 15): empty #17
03-17 09:50:17.538   911   911 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
03-17 09:50:17.548   911  1379 I PackageManager:  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4226, uid=10099, userID:0
03-17 09:50:17.548  4226  4674 I DeviceManagement: Perf: *** Config cache update - complete: 271 ms
03-17 09:50:17.548   911  1042 D StatusBarManagerService: setSystemUiVisibility(0x8700)
,03-17 09:50:17.548   911  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:50:17.548   911  1042 D StatusBarManagerService: hiding MENU key
03-17 09:50:17.548  4226  4674 I DeviceManagement: Perf: *** Cache update - complete: 1351 ms
03-17 09:50:17.548  4226  4674 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@301d4ef6]
03-17 09:50:17.548  1595  1595 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-17 09:50:17.548  1595  1595 I ThreadedRenderer: Defer allocateBuffers to drawing time
,03-17 09:50:17.558   911  1561 I InputMethodManagerService: Disable input method client, pid=4435,
03-17 09:50:17.558  4435  4435 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
03-17 09:50:17.558   911  1561 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-17 09:50:17.558   911  1561 I InputMethodManagerService: Enable input method client, pid=1595
,03-17 09:50:17.568  1547  1547 D QXDM2SD:HtcNative: JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,03-17 09:50:17.598   911  1379 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=4778, uid=2000 userid=0
,03-17 09:50:17.608   911  1042 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-17 09:50:17.608   911  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:50:17.608   911  1042 D StatusBarManagerService: hiding MENU key
,03-17 09:50:17.658   911   949 I ActivityManager: Recipient 4025
,03-17 09:50:17.678   911  1068 W PackageSettings: Skipping PackageSetting{2e85c90a com.example.hello/10374} due to missing metadata,
,03-17 09:50:17.748  1217  1217 I PhoneStatusBar: setImeWindowStatus(false,false),
03-17 09:50:17.758  4226  4226 I DeviceManagement: WorkflowService: Stopping workflow service
,03-17 09:50:17.778   911  1587 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4798 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 09:50:17.778   911  1068 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,03-17 09:50:17.788   911  1068 D Process : killProcessQuiet, pid=4435,
03-17 09:50:17.788   911  1068 I ActivityManager: Killing 4435:com.test.thalitest/u0a195 (adj 1): stop com.test.thalitest
,03-17 09:50:17.788   911  1068 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,03-17 09:50:17.868   911   911 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-17 09:50:17.878   911  4819 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=34 rxSum=26} preTxRxSum={txSum=34 rxSum=26}
03-17 09:50:17.878   911  4819 D WifiDataStallTracker: updateDataStallInfo: NONE
03-17 09:50:17.878   911  4819 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-17 09:50:17.898   911  1822 I ActivityManager: Recipient 4435
03-17 09:50:17.898   911  1561 I WindowState: WIN DEATH: Window{1704f440 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
03-17 09:50:17.898   911  1155 D WifiService: Client connection lost with reason: 4
,03-17 09:50:17.898  1400  1400 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3907af79 uid 10195 pid 4435} (c)'
,03-17 09:50:17.908   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 09:50:17.908   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=79
,03-17 09:50:18.028   911  1021 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,03-17 09:50:18.028  1314  1314 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
03-17 09:50:18.028  1314  1314 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
03-17 09:50:18.028  1314  1314 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
03-17 09:50:18.038   911  1822 W ActivityManager: Spurious death for ProcessRecord{1e27abfd 4435:com.test.thalitest/u0a195}, curProc for 4435: null
03-17 09:50:18.038   911  1587 D PMS     : releaseWL(20f5dfdb): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
03-17 09:50:18.038   911  1585 D PMS     : acquireWL(1fb1d343): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 2036 10024 WorkSource{10024 com.google.android.gms}
03-17 09:50:18.038  2036  2306 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 09:50:18.048   911  2267 D PMS     : releaseWL(1fb1d343): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
03-17 09:50:18.048  1766  2199 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-17 09:50:18.048  1547  1547 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 09:50:18.058   911  1145 W SystemReader: Cannot find grip_rejection_width, use default value instead
,03-17 09:50:18.068   911  1020 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,03-17 09:50:18.108  1595  1595 I art     : Explicit concurrent mark sweep GC freed 54982(3MB) AllocSpace objects, 36(3MB) LOS objects, 34% free, 30MB/46MB, paused 1.082ms total 95.196ms
03-17 09:50:18.108  1595  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-17 09:50:18.108  1595  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-17 09:50:18.148   911   911 W PackageManager: Unable to load service info ResolveInfo{b8fa408 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
03-17 09:50:18.148   911   911 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-17 09:50:18.148   911   911 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:50:18.148   911   911 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-17 09:50:18.148   911   911 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-17 09:50:18.148   911   911 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-17 09:50:18.148   911   911 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:50:18.148   911   911 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:50:18.148   911   911 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-17 09:50:18.148   911   911 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-17 09:50:18.158  4271  4335 D MediaScanner:  prescan time: 809ms
03-17 09:50:18.158  4271  4335 D MediaScanner:     scan time: 908ms
03-17 09:50:18.158  4271  4335 D MediaScanner: postscan time: 70ms
03-17 09:50:18.158  4271  4335 D MediaScanner:    total time: 1787ms
03-17 09:50:18.158  4271  4335 D MediaScanner: -----------------------------------------------------------------
03-17 09:50:18.158  4271  4335 D MediaScanner: firstscan(media) time: 467ms
03-17 09:50:18.158  4271  4335 D MediaScanner: secondscan(non-media) time: 441ms
03-17 09:50:18.158  4271  4335 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:18.158  4271  4335 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:18.158  4271  4335 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-17 09:50:18.158  4271  4335 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
03-17 09:50:18.158  1766  2199 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-17 09:50:18.178  4271  4335 D MediaProvider: [delete][17]
03-17 09:50:18.178   911  1020 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 09:50:18.178  4271  4335 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,03-17 09:50:18.188   911  1587 I ActivityManager: Killing 4047:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
03-17 09:50:18.188   911  1587 D Process : killProcessQuiet, pid=4047
03-17 09:50:18.188   911  1587 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 09:50:18.188  4271  4335 D MediaProvider: [recoverParentNodes] - 0
03-17 09:50:18.188  4271  4335 D MediaProvider: [update][8]
03-17 09:50:18.188  4271  4335 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
,03-17 09:50:18.188  4271  4335 D MediaScannerServiceEx: [updateImage]+
03-17 09:50:18.188  1547  1547 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,03-17 09:50:18.198  4798  4798 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
,03-17 09:50:18.198  4271  4335 D MediaScannerServiceEx: [updateImage]-0
,03-17 09:50:18.198  1766  2199 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-17 09:50:18.218  1766  2199 E ExternalAccountType: Unsupported attribute readOnly
,03-17 09:50:18.228   911   911 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,03-17 09:50:18.238   911   946 I ActivityManager: Recipient 4047
,03-17 09:50:18.248   911  1151 D PMS     : acquireWL(472a736): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null,
03-17 09:50:18.258   911  1152 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
,03-17 09:50:18.268  4271  4335 D MediaScannerServiceEx: [3] scan finished
03-17 09:50:18.268   911  1592 D PMS     : releaseWL(239c918c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,03-17 09:50:18.268  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:18.268  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:18.268  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb
03-17 09:50:18.268  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-17 09:50:18.268  4271  4335 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
,03-17 09:50:18.268  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,03-17 09:50:18.288  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,03-17 09:50:18.288  1595  2119 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-17 09:50:18.288  4271  4335 D MediaProvider: [update][18]#1#
,03-17 09:50:18.308   911  1151 D PMS     : releaseWL(472a736): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
03-17 09:50:18.308   911  1152 V NetworkPolicy: writePolicyLocked()
,03-17 09:50:18.328  4798  4798 V Settings:HtcSettingsApplication: [4798/4798] onCreate()
,03-17 09:50:18.328   911  1152 V NetworkPolicy: updateNetworkEnabledLocked(),
,03-17 09:50:18.328  4271  4335 D MediaProvider: [update][42]#0#
03-17 09:50:18.328   911  1152 V NetworkPolicy: updateNotificationsLocked()
03-17 09:50:18.328  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 09:50:18.338  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-17 09:50:18.338  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-17 09:50:18.338  4271  4335 D MediaProviderUtils: calcVolumeId: /storage/usb,
03-17 09:50:18.338  4271  4335 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-17 09:50:18.338  4271  4335 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
03-17 09:50:18.338  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,03-17 09:50:18.348  4798  4798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 ,
03-17 09:50:18.348  4271  4335 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted
03-17 09:50:18.348  4271  4335 D MediaProvider: [update][9]#1#
,03-17 09:50:18.358   911  4820 I ActivityManager: Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 09:50:18.378  4271  4335 D MediaProvider: [update][34]#0#
,03-17 09:50:18.388  4271  4335 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-17 09:50:18.398  4798  4798 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
03-17 09:50:18.398  4798  4798 D         : Cust_ConnectToPC   : Internet_Sharing>true
,03-17 09:50:18.398  4798  4798 D         : Cust_ConnectToPC   : Modem_Link>false
03-17 09:50:18.398  4798  4798 D         : Cust_ConnectToPC   : spcsc>false
03-17 09:50:18.398  4798  4798 D         : Cust_ConnectToPC   : IPT>true
03-17 09:50:18.398  4798  4798 D         : Cust_ConnectToPC   : Singel_USB>false
,03-17 09:50:18.418  4798  4798 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 09:50:18.428   911  1068 I art     : Explicit concurrent mark sweep GC freed 28048(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 18MB/27MB, paused 1.558ms total 184.665ms,
,03-17 09:50:18.438   911  1068 W asset   : Copying FileAsset 0x5595789370 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,03-17 09:50:18.488   911  1181 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml,
03-17 09:50:18.488  4798  4798 E SmartNS_Utility: hasRemovableStorageSlot: true
03-17 09:50:18.488   911  1181 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
03-17 09:50:18.488  4798  4798 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
03-17 09:50:18.488  4798  4798 D SmartNS_NSReceiver: onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,03-17 09:50:18.488  4798  4798 I SmartNS_Utility: setISNotification
03-17 09:50:18.488  4798  4798 D SmartNS_Utility: usb_cable_connect = 1
03-17 09:50:18.488  4798  4798 D SmartNS_Utility: usb_denied = 0
03-17 09:50:18.488   911  1165 I ActivityManager: Killing 4084:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
03-17 09:50:18.488   911  1165 D Process : killProcessQuiet, pid=4084
03-17 09:50:18.488   911  1165 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-17 09:50:18.498  4798  4798 I SmartNS_PSService: usb notificaiton:true
,03-17 09:50:18.508   911  1605 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,03-17 09:50:18.508  4822  4822 V Settings:HtcSettingsApplication: [4822/4822] onCreate(),
,03-17 09:50:18.628   911  1379 I ActivityManager: Recipient 4084,
,03-17 09:50:18.698  4798  4798 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,03-17 09:50:18.708  4798  4798 D SmartNS_Utility: usb_cable_connect = 1
,03-17 09:50:18.718  4798  4798 D SmartNS_Utility: usb_denied = 0
03-17 09:50:18.718  4798  4798 I SmartNS_PSService: usb notificaiton:true
,03-17 09:50:18.718   911  1165 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,03-17 09:50:18.728  1314  1348 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
03-17 09:50:18.728  1217  1217 I RemoteViews: reapply : com.android.settings 2 36
,03-17 09:50:18.748  1314  1856 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
,03-17 09:50:18.748  1217  1217 I RemoteViews: reapply : com.android.settings 1 36
,03-17 09:50:18.758   911  1165 I ActivityManager: Killing 4123:com.htc.lmw/u0a58 (adj 15): empty #17
03-17 09:50:18.758   911  1165 D Process : killProcessQuiet, pid=4123
03-17 09:50:18.758   911  1165 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:18.778   911   911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,03-17 09:50:18.858   911  1379 I ActivityManager: Recipient 4123,
,03-17 09:50:18.868  1547  1762 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,03-17 09:50:18.868  1547  1762 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<,
,03-17 09:50:18.888   911   911 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4852 uid=9987 gids={49987, 9997} abi=arm64-v8a
,03-17 09:50:18.898   911   946 I ActivityManager: Killing 4174:com.android.managedprovisioning/u0a63 (adj 15): empty #17
03-17 09:50:18.898   911   946 D Process : killProcessQuiet, pid=4174
03-17 09:50:18.898   911   946 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-17 09:50:19.028   911  2287 I ActivityManager: Recipient 4174,
,03-17 09:50:19.118   911   911 D SmartDim: Init customizeScreenOffDelayClass error,
,03-17 09:50:19.128   911  1021 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{f83c73c u0 ReceiverList{15b5552f 911 system/1000/u0 local:32b670e}}
,03-17 09:50:19.128   911   911 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-17 09:50:19.128   911  4874 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@df1a10, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
,03-17 09:50:19.128   911  4874 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 09:50:19.128   911  4874 W SensorService: enable: get sensor name = Accelerometer Sensor
03-17 09:50:19.128   911   911 E WifiTrafficPoller:  packet count Tx=47 Rx=87
03-17 09:50:19.128   911   911 E WifiTrafficPoller: notifying of data activity 1
,03-17 09:50:19.128   911  4874 W SensorService: pid=911, uid=1000
03-17 09:50:19.128  1217  1217 D WIFI_ICON: WifiActivity: 1
,03-17 09:50:19.128   911  4874 W SensorService: Active sensors: size = 3
03-17 09:50:19.128   911  4874 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=2)
,03-17 09:50:19.128  1217  1217 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-17 09:50:19.128   911  4874 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
03-17 09:50:19.128   911  4874 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 09:50:19.128   911  4874 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@df1a10, eanble = 1, strlen(mName) = 34
03-17 09:50:19.128   911  4874 W SensorService: Active Listeners: mActiveListeners.size() = 3
03-17 09:50:19.128   911  4874 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@64d0115
03-17 09:50:19.128   911  4874 W SensorService: Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2d7ec149
,03-17 09:50:19.128   911  4874 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@df1a10
03-17 09:50:19.128   911  4874 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
03-17 09:50:19.128   911  4874 I SensorManager: registerListenerImpl: listener = com.htc.smartdim.sensor_eye@df1a10, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
03-17 09:50:19.128   911  4874 W SensorService: Following SensorService logs are not warning, just make sure they are printed
03-17 09:50:19.128   911  4874 W SensorService: enable: get sensor name = CM36686 Proximity sensor
03-17 09:50:19.128   911  4874 W SensorService: pid=911, uid=1000
03-17 09:50:19.128   911  4874 W SensorService: Active sensors: size = 4
03-17 09:50:19.128   911  4874 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=2)
,03-17 09:50:19.128   911  4874 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
03-17 09:50:19.128   911  4874 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
03-17 09:50:19.128   911  4874 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
03-17 09:50:19.128   911  4874 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@df1a10, eanble = 1, strlen(mName) = 34
03-17 09:50:19.128   911  4874 W SensorService: Active Listeners: mActiveListeners.size() = 3
,03-17 09:50:19.128   911  4874 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@64d0115
03-17 09:50:19.128   911  4874 W SensorService: Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2d7ec149
03-17 09:50:19.128   911  4874 W SensorService: Listener[2] = com.htc.smartdim.sensor_eye@df1a10
03-17 09:50:19.128   911  4874 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,03-17 09:50:19.168   911  1822 I ActivityManager: Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4875 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-17 09:50:19.168   911  1822 I ActivityManager: Killing 4381:com.htc.cs.pns/u0a71 (adj 15): empty #17
,03-17 09:50:19.168   911  1822 D Process : killProcessQuiet, pid=4381
03-17 09:50:19.168   911  1822 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 09:50:19.348   911  4024 I ActivityManager: Recipient 4381
,03-17 09:50:19.348   911   911 I SensorManager: dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@df1a10
,03-17 09:50:19.378   911  1021 I ActivityManager: Waited long enough for: ServiceRecord{11a4cc07 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,03-17 09:50:19.498  3545  3601 I HtcModeClient: handler message = 4011
,03-17 09:50:19.498  3545  3601 E HtcModeClient: Check connection and retry 3 times.
,03-17 09:50:19.518   476   476 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 09:50:19.578   911   946 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4896 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-17 09:50:19.578   911   946 I ActivityManager: Killing 4476:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,03-17 09:50:19.578   911   946 D Process : killProcessQuiet, pid=4476
03-17 09:50:19.578   911   946 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-17 09:50:19.608  1595  2108 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,03-17 09:50:19.608  1595  2108 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3954d238 +
03-17 09:50:19.608  1595  2108 I Prism.WidgetManager: onLoadItems() +
,03-17 09:50:19.638  1595  2108 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 09:50:19.678   911  1605 I ActivityManager: Recipient 4476
,03-17 09:50:19.818  1595  2108 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-17 09:50:19.888   911   946 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4896, uid=10072, userID:0
,03-17 09:50:19.898  4896  4896 W global  : [apache-http] Connection GC has been deprecated!
,03-17 09:50:19.928  4896  4896 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/

```
